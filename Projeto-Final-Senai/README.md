# README — Fluxee (melhorado)

## Fluxee — Sistema de Gestão de Almoxarifado Escolar

> Projeto final — Fluxee é um sistema web para gerenciar almoxarifados escolares: controle de estoque, solicitações, aprovação e módulos auxiliares.

Principais melhorias que acrescentei:
- Estrutura de README padronizada (Descrição, Tecnologias, Instalação, Uso, Licença).
- Instruções de execução local com passos claros.
- Seção de demo/comentários e contatos da equipe.

## 🚀 Funcionalidades (resumo)
- Controle de produtos: CRUD de itens de estoque.
- Solicitações de materiais com fluxo de aprovação.
- Gestão de usuários e controle de perfis (Admin, Supervisor, Técnico, Operador).
- Módulos extras: Transporte, Segurança e Limpeza.

## 🛠 Tecnologias
- Backend: Python 3.12+, Flask
- Banco: SQLite (SQLAlchemy)
- Frontend: HTML/CSS (Jinja2)
- Testes: Robot Framework + Selenium

## ⚙️ Instalação (local)
1. Clone o repositório
   ```bash
   git clone https://github.com/arthurSchgg/Projeto-Final-Senai.git
   cd Projeto-Final-Senai
   ```
2. Crie e ative um virtualenv (recomendado)
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate   # Windows
   pip install -r requirements.txt
   ```
3. Configure o banco de dados (SQLite por padrão)
   ```bash
   flask db upgrade  # se usar Flask-Migrate
   ```
4. Rode a aplicação
   ```bash
   flask run
   ```

## 👥 Equipe
- Arthur Miguel Schlichting — arthurms2904@gmail.com
- Bianca Vaz
- Lucas Schlei

## 📖 Documentação
Manual do usuário: https://www.notion.so/Manual-do-Usu-rio-Fluxee-Sistema-de-Gest-o-de-Almoxarifado-2b0b27af51e38053b741f6875215e40c

## License
MIT
