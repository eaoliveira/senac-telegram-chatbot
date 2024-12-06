# Projeto de Assistente Virtual para Consultas de Voos

Este repositório contém o código desenvolvido como parte do trabalho de pós-graduação em Inteligência Artificial no SENAC. O objetivo principal do projeto é criar um assistente virtual para consulta de voos, que utiliza tecnologias como processamento de linguagem natural (PNL), APIs externas (como Amadeus e Groq), e integração com o Telegram para interação com o usuário.

## Contribuidores

Este projeto tem contribuições de:

- Bruna Xavier
- [@eaoliveira](https://github.com/eaoliveira) - Edna Paula
- [@Leonardofsm](https://github.com/Leonardofsm) Leonardo Mendonca
- [@matheusgsilva](https://github.com/matheusgsilva) - Matheus Graciando
- [@vinicius-ledesma](https://github.com/vinicius-ledesma) -  Vinicius Ledesma
## Tecnologias Utilizadas

- Python 3.x
- Google Colab para uso de variáveis de ambiente
- API Groq para NLP
- API Amadeus para consultas de voos
- Telegram Bot API para interação com o usuário
- Bibliotecas de Machine Learning (Scikit-learn)
- Asyncio para operações assíncronas
- Nest_asyncio para permitir o uso de asyncio no Google Colab

## Funcionalidades

O assistente virtual implementado oferece as seguintes funcionalidades:

1. **Consulta de Voos**: O usuário pode consultar detalhes de voos, como preço, horário de partida, e companhia aérea.
2. **Recomendações de Voos**: O assistente pode sugerir voos com base em preferências de preço.
3. **Informações sobre Destinos**: O assistente fornece detalhes sobre destinos turísticos, incluindo clima, tempo de estadia e atividades culturais.

## Configuração do Ambiente

1. Defina as variáveis de ambiente necessárias para as APIs no seu ambiente de desenvolvimento:

GROQ_API_KEY: Chave de API da Groq

CLIENT_AMADEUS: Client ID para a API Amadeus

SECRET_AMADEO: Client Secret para a API Amadeus

TELEGRAM_BOT: Token do bot do Telegram 
