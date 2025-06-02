
# Gestão de Gastos Familiares – Deploy Railway

## 🚀 Deploy com 1 Clique

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/FUTURE_TEMPLATE_ID)

## 🧾 Setup

1. Configure as variáveis no painel Railway (use `.env.example` como base)
2. Supabase será usado como banco principal
3. OpenAI (Whisper + GPT-4) será usado para análise
4. Redis será usado como cache para confirmações pendentes

## 📂 Estrutura

- workflows/ → JSON do n8n
- supabase/ → SQL com estrutura do banco
- redis/ → Script para inicialização do Redis
