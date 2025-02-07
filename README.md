# Análise de Sentimentos com Microsoft Azure

## Visão Geral
Este repositório documenta a experiência com a API de Análise de Sentimentos do Microsoft Azure, utilizada para processar e classificar textos com base em suas emoções predominantes.

## Passos Realizados
1. **Configuração do Ambiente:**
   - Acesso ao portal do [Azure](https://portal.azure.com/)
   - Criação de um recurso do **Azure AI Language**
   - Obtenção da chave de API e endpoint

2. **Integração com a API:**
   - Uso do SDK do Azure para Python ou chamadas REST
   - Envio de frases para análise
   
3. **Processamento dos Dados:**
   - Classificação dos textos como **positivo, negativo ou neutro**
   - Análise de sentimento por frase e texto completo
   
4. **Visualização dos Resultados:**
   - Prints das respostas da API
   - Comparativos entre diferentes entradas de texto

## Insights e Possibilidades
- **Precisão da IA:** A API consegue identificar nuances emocionais no texto, mas textos curtos podem ser classificados de forma menos precisa.
- **Possibilidade de Integração:** Pode ser usada em chatbots, monitoramento de redes sociais, feedback de clientes e automação de análise textual.
- **Limitações:** Algumas frases ambíguas podem ter classificação imprecisa, exigindo refinamento do input.

## Prints


![Captura de tela 2025-02-07 144837](https://github.com/user-attachments/assets/d3bb26a3-e40f-41dd-b2c3-17f98e75a014)
![Captura de tela 2025-02-07 144838](https://github.com/user-attachments/assets/5fad5d40-c92a-46f9-8b6e-1146d22a92d8)
![Captura de tela 2025-02-07 145039](https://github.com/user-attachments/assets/d10b5cb5-b673-4bf0-a8b8-6f693f8669e8)
![Captura de tela 2025-02-07 145140](https://github.com/user-attachments/assets/5d5f2f1f-8b74-4dca-9cc9-09f16e77f6fc)



---
**Referências:** [Documentação do Azure AI Language](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)
