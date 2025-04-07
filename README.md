<b>Análise de Dados de Veículos<b>
Projeto de Análise Exploratória de Dados (EDA) e Estatística Descritiva

Este repositório contém um projeto de análise de dados focado em veículos, explorando características como preço, modelos, anos e outras métricas relevantes. O objetivo é demonstrar habilidades em análise estatística, visualização de dados e limpeza de dados usando Python (Pandas, Seaborn, Matplotlib).

📌 Visão Geral do Projeto
O projeto consiste em:

✔️Análise Básica: Estatísticas descritivas (média, mediana, moda, etc.).<br>
✔️Análise Avançada: Identificação de outliers, correlações e distribuições.<br>
✔️Visualizações: Gráficos para entender padrões e tendências nos dados.<br><br>

Ferramentas Utilizadas:

✔️Python (Pandas, NumPy, Matplotlib, Seaborn)<br>
✔️Jupyter Notebook (.ipynb)<br><br>

📊 Técnicas e Métricas Aplicadas<br><br>
📈 Estatística Descritiva<br><br>
Métrica	Descrição:<br>
✔️Média	Valor médio dos preços/veículos.<br>
✔️Mediana	Valor central (evita distorções por outliers).<br>
✔️Moda	Valor mais frequente na base.<br>
✔️Variância	Medida de dispersão dos dados.<br>
✔️Desvio Padrão	Indica a variação em torno da média.<br>
✔️Quantis	Divisão dos dados em percentis (25%, 50%, 75%).<br>
✔️IQR	Intervalo Interquartil (diferença entre Q3 e Q1).<br>
✔️Assimetria (Skew)	Indica se os dados são assimétricos (positivo ou negativo).<br>
✔️Curtose	Mede o "achatamento" da distribuição (caudas pesadas ou leves).<br><br>
🔍 Filtros e Agregações
loc: Filtragem de veículos com preço > R$800.000.

groupby: Agrupamento por modelo, ano ou categoria para análises comparativas.

📊 Visualizações<br><br>
✔️Gráfico	Objetivo.<br>
✔️Countplot	Contagem de veículos por categoria (ex: modelo, ano).<br>
✔️Boxplot	Identificação de outliers e distribuição dos preços.<br>
✔️Histograma	Distribuição de frequência (ex: preços, quilometragem).<br>
✔️Heatmap	Correlação entre variáveis (ex: preço x ano x quilometragem).<br>
✔️Scatter Plot	Relação entre duas variáveis (ex: preço x quilometragem).<br><br>
📂 Estrutura do Repositório
Copy
📁 veiculos-analysis/  
├── 📄 analise_veiculos.ipynb          # Jupyter Notebook com a análise completa  
├── 📄 dados_veiculos.csv              # Dataset utilizado (se disponível)  
├── 📄 README.md                       # Este arquivo  
└── 📁 images/                         # Pasta com gráficos exportados (opcional) <br><br> 
🚀 Como Executar o Projeto:<br><br>
Pré-requisitos:<br> 
✔️Python 3.x<br> 
✔️Jupyter Notebook<br> 
✔️Bibliotecas: pandas, numpy, matplotlib, seaborn<br> <br> 

Instalação:<br><br>
✔️bash<br>
✔️Copy<br>
✔️pip install pandas numpy matplotlib seaborn jupyter<br><br>
Execução:<br>

Abra o Jupyter Notebook:<br>
✔️bash<br>
✔️Copy<br>
✔️jupyter notebook analise_veiculos.ipynb<br><br>

🔎 Principais Insights<br><br>
✔️Veículos mais caros: Identificação dos modelos com preço acima de R$800.000.<br>
✔️Correlações: Relação entre preço, ano e quilometragem.<br>
✔️Distribuição: Assimetria e curtose dos preços (dados concentrados ou dispersos?).<br>
✔️Outliers: Possíveis erros ou veículos com valores atípicos.<br><br>

🎯 Objetivos do Projeto<br><br>
✔️ Demonstrar habilidades em análise exploratória de dados (EDA).<br>
✔️ Aplicar conceitos estatísticos em um dataset real.<br>
✔️ Criar visualizações claras e informativas.<br>
✔️ Documentar o processo para portfólio profissional.<br><br>

📌 Contato:<br><br>
Feito por Victor Tintel Martins.

LinkedIn: https://www.linkedin.com/in/victor-tintel/

GitHub: https://github.com/victortintel
