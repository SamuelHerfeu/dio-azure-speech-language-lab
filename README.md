## 1. Objetivo
Documentar o processo de configuração dos recursos necessários no Azure para análise de sentimentos.

## 2. Recursos Criados
- **Serviço de Linguagem**: Cognitive Services > Language Service
  - Nome: sentiment-analysis-dio
  - Região: eastus
  - Camada de preço: Free F0 (para testes)

## 3. Configurações Realizadas
1. Autenticação:
   - Chave de acesso gerada: [REDACTED]
   - Endpoint: https://sentiment-analysis-dio.cognitiveservices.azure.com/

2. Funcionalidades ativadas:
   - Análise de Sentimentos
   - Reconhecimento de Entidades
   - Extração de Frases-chave

## 4. Capturas de Tela
![Configuração do Serviço](images/config-service.png)
![Painel de Chaves](images/keys-dashboard.png)

## 5. Observações
- Tempo de provisionamento: ~2 minutos
- Limitações da camada gratuita: 5.000 chamadas/mês
