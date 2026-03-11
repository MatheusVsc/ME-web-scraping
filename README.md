# 🐦 Twitter/X Scraper com Playwright

Script Python para coletar tweets de qualquer perfil público do X (Twitter) e salvar em Excel (.xlsx).

## 📦 Requisitos

pip install playwright openpyxl
playwright install chromium


## 🚀 Como usar

python twitter_scraper.py --usuario th3hydrogen
python twitter_scraper.py --usuario th3hydrogen --quantidade 50


## 📊 Dados coletados

| Campo | Descrição |
|---|---|
| Autor | Nome do usuário |
| Usuário | @ do perfil |
| Descrição | Texto do tweet |
| Data | Data e hora |
| Visualizações | Número de views |
| Likes | Curtidas |
| Comentários | Respostas |
| Retweets | Compartilhamentos |
| Link | URL do tweet |

## ⚠️ Aviso
Este script é para fins educacionais. Respeite os Termos de Uso do X.
