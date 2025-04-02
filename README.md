## atividade-de-machine-learning


Link do kaggle: https://www.kaggle.com/datasets/piterfm/2022-ukraine-russian-war

Para essa atividade eu selecionei o dataset "2022 Russia Ukraine War", pois eu me interesso bastante por geopolítica e  economia mundial. Esse dataset contém dados de:

Pessoal
Prisioneiro de Guerra (POW) - - não foi rastreado desde 2022-04-28
Aeronave
Helicóptero
- Tanque
- Transportador Blindado de Pessoal (APC)
- Lançador de Foguetes Múltiplos (MRL)
- Artilharia de Campanha
- Automóvel Militar - não foi rastreado desde 2022-05-01; unido ao Tanque de Combustível em Veículos e Tanques de Combustível
- Tanque de Combustível - não foi rastreado desde 2022-05-01; unido ao Automóvel Militar em Veículos e Tanques de Combustível
- Guerra Antiaérea
- Drone - UAV+RPA
- Navio Naval - Navios de Guerra, Barcos
- Guerra Antiaérea
- Sistema SRBM Móvel - não foi rastreado desde 2022-05-01; juntou-se a Mísseis de Cruzeiro
- Veículos e Tanques de Combustível - aparecem desde 2022-05-01 como uma soma de Tanque de Combustível e Automóvel Militar
- Mísseis de Cruzeiro - aparecem desde 2022-05-01
- Direção das Maiores Perdas - aparecem desde 2022-04-25
# O objetivo de análise

Tem como necessidade explicar por meio de dados como a guerra prujudica a economia e as pessoas não só da Russia e da Ucrânia, mas tambem geopolíticamente.

# Machine learning

Uma IA de Machine Learning (ML) para regressão pode ser extremamente útil para analisar e comparar dados da guerra entre Rússia e Ucrânia, fornecendo insights quantitativos e preditivos sobre diversos aspectos do conflito. Aqui estão algumas aplicações importantes:

1. Previsão de Deslocamento de População e Refugiados
- Modelos de regressão podem prever o fluxo de refugiados com base em variáveis como intensidade de combates, bombardeios e controle territorial.

- Exemplo: Relacionar ataques a cidades com aumentos repentinos no número de deslocados.

2. Análise de Impacto Econômico
- Regressão linear ou polinomial pode estimar perdas econômicas (PIB, destruição de infraestrutura) com base em dados históricos de guerras ou sanções.

- Exemplo: Correlacionar sanções ocidentais à Rússia com a inflação ou desvalorização do rublo.

3. Evolução Territorial e Mapas de Conflito
- Modelos de séries temporais podem prever avanços/recuos militares usando dados geolocalizados de batalhas.

- Exemplo: Prever quais regiões têm maior probabilidade de serem ocupadas com base em histórico de movimentação de tropas.

4. Mortes e Baixas Militares
- Regressão pode estimar o número de mortos ou feridos com base em relatórios parciais, identificando subnotificações.

- Exemplo: Relacionar ataques a hospitais com aumento indireto de mortes civis.

5. Impacto em Commodities (Energia, Alimentos)
- Algoritmos como Random Forest Regression ou XGBoost podem prever variações no preço do trigo, gás e petróleo devido a interrupções na cadeia de suprimentos.

- Exemplo: Modelar como bloqueios a portos ucranianos afetam o preço global de cereais.

6. Análise de Sentimento e Opinião Pública
- Embora não seja regressão clássica, técnicas de regressão logística podem classificar apoio político (na Rússia, Ucrânia ou globais) com base em redes sociais.

7. Eficácia de Sanções Internacionais
- Regressão multivariada pode medir o impacto real das sanções ao correlacioná-las com dados macroeconômicos russos (reservas internacionais, importações/exportações).

Técnicas de ML Aplicáveis:
- Regressão Linear (para relações diretas, como bombardeios × mortes).

- Regressão Polinomial (para comportamentos não lineares, como escaladas repentinas).

- SVR (Support Vector Regression) (útil para dados com outliers, como ataques isolados com grande impacto).

- Redes Neurais (para padrões complexos, como interação entre múltiplas variáveis).

Fontes de Dados Úteis:
- Dados de satélite (ex.: NASA FIRMS para incêndios em zonas de conflito).

- Relatórios da ONU, ACLED (Armed Conflict Location & Event Data Project).

- Dados econômicos (IMF, World Bank).

- Mídia e redes sociais (ex.: GDELT para eventos geopolíticos).
