# Assistente Financeiro GenAI

Este projeto é um assistente virtual focado em finanças pessoais, construído com IA generativa e interface web em Streamlit.  
O objetivo é oferecer uma experiência de conversa simples e educativa sobre dinheiro, juros, dívidas, produtos financeiros e simulações demonstrativas.

## Funcionalidades

- Conversa em linguagem natural sobre finanças pessoais.
- Explicações de conceitos básicos (juros, orçamento, dívidas, reserva de emergência).
- Visão geral de produtos financeiros comuns (cartão de crédito, empréstimo, financiamento, poupança, renda fixa básica).
- Exemplos de simulações simples de parcelamento e juros.
- Uso de um prompt específico para evitar respostas inventadas e manter o foco em finanças.

## Estrutura do projeto

- `documentacao_agente.md`: documentação da Etapa 1, descrevendo o agente (missão, público-alvo, escopo, tom de voz e limitações).
- `prompt_agente.md`: instruções detalhadas usadas como prompt de sistema para o modelo de IA.
- `base_conhecimento/`
  - `conceitos_basicos_financas.md`
  - `produtos_financeiros.md`
  - `simulacoes_exemplos.md`
- `app.py`: aplicação web em Streamlit para interação com o assistente.
- `requirements.txt`: dependências do projeto.

## Como executar localmente

1. **Clonar o repositório**

   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   cd SEU-REPOSITORIO
