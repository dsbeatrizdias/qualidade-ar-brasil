# 🌬️ Análise de Qualidade do Ar — Brasil

Projeto de análise de dados usando a API pública da OpenAQ.

## O que o projeto faz
- Conecta à API OpenAQ v3
- Busca estações de monitoramento no Brasil
- Coleta medições de poluentes como PM2.5, PM10, O3 e NO2

## Status
🚧 Em desenvolvimento

## Tecnologias
- Python 3
- pandas
- requests
- matplotlib
- seaborn

## Como rodar
1. Clone o repositório
2. Crie um arquivo `.env` com sua chave: `OPENAQ_API_KEY=sua_chave`
3. Instale as dependências: `pip3 install pandas requests matplotlib seaborn python-dotenv jupyter`
4. Abra o `analise.ipynb` no VS Code