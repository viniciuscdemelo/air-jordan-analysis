# Análise do Mercado de Revenda de Air Jordan (2023-2026)

## Contexto

O mercado de revenda de tênis evoluiu para uma indústria global de bilhões de dólares, com os Air Jordans no centro da cultura e da economia. Embora grande parte dos dados existentes foque exclusivamente em plataformas online massivas, entender o ciclo completo de vida de um tênis exige olhar tanto para mercados globais quanto para canais de varejo independentes.
Este conjunto de dados oferece uma visão abrangente do mercado moderno de tênis, fazendo a ponte entre a dinâmica do varejo tradicional e o altamente volátil mercado secundário.

## Projeto

Este projeto tem como objetivo apresemtar uma análise exploratoria de dados (EDA) de um database (ver item **fonte**) aplicado ao mercado de revenda de tênis **Air Jordan** no período de 2023 a 2026.
O objetivo é investigar as variáveis e suas relções, sendo tais variáveis: modelo, estado de conservação, preço de varejo, preço de revenda e margem de lucro. 

## Fonte

### Nota do Analista

O dataset utilizado para este projeto encontra-se disponível via Kaggle pelo link "https://www.kaggle.com/datasets/abdullahmeo/air-jordan-sneaker-market-and-resale-data2023-2026" dados acessados em 11/04/2026.

### Nota do Autor*

#### Origem
Este conjunto de dados foi criado especificamente para o Kaggle para fornecer um ambiente limpo e estruturado para modelagem preditiva e análise de mercado.
giy 
#### Material de Origem
Embora os registros específicos de transações sejam sintéticos, os parâmetros base (por exemplo, MSRPs originais, coloras populares, canais de varejo e os prêmios gerais de preço aplicados a tênis em condição "deadstock") são modelados com base em tendências históricas e reais observadas em grandes plataformas secundárias como StockX e GOAT entre 2023 e 2026.

#### Metodologia de Coleção
Nenhum dado real do usuário, informações pessoais identificáveis (PII) ou registros financeiros proprietários foram extraídos para criar esse conjunto de dados. Ele foi gerado usando um script Python personalizado com a seguinte metodologia: Inicialização de Parâmetros: Preços base de varejo e métricas de popularidade foram estabelecidos para cinco grandes silhuetas do Air Jordan (por exemplo, AJ1 High, AJ4 Retro). Geração Algorítmica: As bibliotecas pandas e numpy do Python foram utilizadas para gerar 5.000 linhas únicas de dados de transação. Lógica Condicional: Probabilidades ponderadas foram aplicadas para garantir um comportamento realista do mercado. Por exemplo: Tênis classificados como "Deadstock (Brand New)" foram programados para acionar multiplicadores de revenda maiores (até 3,5x o preço de varejo) em comparação com pares "usados". Transações atribuídas a canais online de alto volume (StockX, GOAT) foram programadas para ter uma contagem de Days_in_Inventory menor do que aquelas atribuídas ao varejo tradicional sem agendamento. Distribuição por Séries Temporais: O Sale_Date de cada transação foi distribuído aleatoriamente ao longo de um cronograma contínuo de 3 anos (2023–2026) para permitir a previsão de séries temporais e a análise de tendências sazonais.





*Traduzido do inglês para o Portguês, tradução livre.