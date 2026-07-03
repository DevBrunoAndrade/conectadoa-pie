cat > README.md << 'EOF'
# ConectaDoa – Sistema de Gestão de Doações

Sistema web desenvolvido como Projeto Integrador (PIE I – ADS)
para a ONG ConectaDoa, com o objetivo de centralizar o cadastro
de doadores e o registro de doações.

## Stack
- Backend: Python + Flask + PostgreSQL
- Frontend: React (ou HTML/CSS/JS)
- Auth: JWT (Flask-JWT-Extended)

## Como rodar localmente
1. Clone o repositório
2. Copie `.env.example` para `.env` e preencha as variáveis
3. `pip install -r backend/requirements.txt`
4. Execute: `python backend/app.py`
5. Acesse: http://localhost:5000
EOF