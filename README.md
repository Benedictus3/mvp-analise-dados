🧠 Contexto

Este é um projeto acadêmico desenvolvido como parte da disciplina de Análise de Dados e Boas Práticas (PUC-Rio). O objetivo é aplicar conceitos de ciência de dados na análise de atributos de campeões do jogo League of Legends, usando informações do patch 25.11 (2025). A meta é identificar padrões, possíveis desbalanceamentos e criar uma base para futuras análises de balanceamento e estratégia.

📂 Dataset

Fonte: Kaggle – League of Legends Patch 25.11 Champion Data (2025) - https://www.kaggle.com/datasets/laurenainsleyhaines/patch-25-11-league-of-legends-champion-data-2025
Contém dados detalhados sobre campeões do jogo, como:
Dano base, HP base, ataque por segundo
Armadura, resistência mágica, mana
Role (classe), escalabilidade, entre outros

🎯 Objetivos

Realizar análise exploratória de dados (EDA)
Identificar campeões com atributos fora do padrão
Explorar correlações entre atributos ofensivos e defensivos
Prever taxas de vitória de campeões
Criar visualizações interativas para facilitar a leitura dos dados

🛠️ Ferramentas Utilizadas

Python: Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn
Ambientes: Google Colab, Jupyter Notebook
Documentação: Markdown, GitHub

📊 Pipeline de Análise

Carregamento e limpeza dos dados: correção de colunas, remoção de duplicatas
Exploração de atributos: histograma, boxplots, estatísticas
Identificação de outliers: atributos extremos e campeões OP
Correlações entre variáveis: mapa de calor e insights
Clusterização com K-Means: agrupamento baseado em atributos
Dashboard interativo com Plotly: visualizações filtráveis por campeão e atributo

Restrições:
Dados limitados ao patch 25.11 (2025)
Apenas dados de campeões, sem informações de jogadores ou partidas
Estatísticas agregadas, não por partida individual

