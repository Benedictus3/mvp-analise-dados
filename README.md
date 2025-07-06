🧠 Contexto

Este é um projeto acadêmico desenvolvido como parte da disciplina de Análise de Dados e Boas Práticas (PUC-Rio). O objetivo é aplicar conceitos de ciência de dados na análise de atributos de campeões do jogo League of Legends, usando informações do patch 25.11 (2025). A meta é identificar padrões, possíveis desbalanceamentos e criar uma base para futuras análises de balanceamento e estratégia.

📂 Dataset

Fonte: Kaggle – League of Legends Patch 25.11 Champion Data (2025)
Contém dados detalhados sobre campeões do jogo, como:
Dano base, HP base, ataque por segundo
Armadura, resistência mágica, mana
Role (classe), escalabilidade, entre outros

🎯 Objetivos

Realizar análise exploratória de dados (EDA)
Identificar campeões com atributos fora do padrão
Explorar correlações entre atributos ofensivos e defensivos
Aplicar clusterização para categorizar campeões por estilo
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

📈 Exemplos de Insights

Campeões como X, Y, Z têm os maiores valores de dano base
Roles como Tank possuem maior HP e menor Attack Speed
Correlações fracas entre dano e defesa sugerem especializações
Clusterização dividiu campeões em perfis como ofensivo, balanceado e suporte

📚 Referências

Kaggle Dataset
League of Legends Wiki
Repositórios da trilha "mvp-analise-dados" da PUC-Rio
