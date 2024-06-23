# Análise de Dados de Tickets de TI

Este projeto visa otimizar a gestão de tecnologia através da análise dos dados de tickets de suporte de TI. Utilizando bibliotecas de análise de dados e estatística, como pandas e statsmodels, foram realizadas várias análises para identificar padrões e previsões futuras.

## Visão Geral
Dados fictícios

Visando otimizar recursos de tecnologia como o tempo, faço aqui uma análise dos dados de tickets de TI. Criei um exemplo de um arquivo xlsx, simulando um arquivo de uma plataforma de ticket padrão. O arquivo tem 51 linhas com 50 tickets simulando demandas do dia 01/06 até 07/06.

Vejo essa análise necessária para empresas onde tem essa função de suporte de TI.

Visto que podemos perceber o fluxo de horário que mais tem problema, quais colaboradores tem mais dificuldade com tecnologia, onde focar nossa atenção no ti e fazer uma previsão de como será o restante de dias as demandas de TI. Podendo assim estar mais preparados e diminuir o tempo decorrido até a resolução.

## Funcionalidades

- Análise do horário com mais criação de tickets.
- Cálculo do tempo médio demorado por ticket.
- Previsão de demandas futuras utilizando o modelo ARIMA.
- Distribuição de prioridade dos tickets.
- Análise dos tipos de problemas mais comuns.
- Identificação dos nomes com mais tickets criados.

## Uso

1. Certifique-se de que você tem o arquivo `tickets_ti.xlsx` no diretório especificado no script ou atualize o caminho do arquivo conforme necessário.
2. Execute o Jupyter Notebook para visualizar as análises.
    ```bash
    jupyter notebook
    ```
3. No Jupyter Notebook, abra o arquivo `analise_tickets_ti.ipynb` e execute as células para ver os gráficos e análises.

## Resultados Esperados

O notebook fornece várias visualizações e análises:
- **Número de tickets diários**: Um gráfico que mostra a quantidade de tickets criados por dia.
- **Previsão do número de tickets**: Um gráfico com a previsão de tickets para os próximos 30 dias utilizando o modelo ARIMA.
- **Distribuição de Prioridade dos Tickets**: Um gráfico de barras mostrando a quantidade de tickets por nível de prioridade.
- **Tipos de Problemas Mais Comuns**: Um gráfico de barras dos 10 tipos de problemas mais comuns reportados.
- **Nomes com Mais Tickets Criados**: Um gráfico de barras mostrando os nomes ou categorias com mais tickets criados.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões ou encontrar algum problema, por favor, abra uma issue ou envie um pull request.

## Contato

Para mais informações, entre em contato pelo Linkedin https://www.linkedin.com/in/willian-felipe-barbão-56aa5829b/.
