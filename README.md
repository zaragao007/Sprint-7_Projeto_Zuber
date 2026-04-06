# 🚖 Análise de Mercado de Táxis e Estratégia de Lançamento Zuber - Chicago

## 🎯 Contexto do Projeto
A Zuber, uma nova empresa de partilha de viagens (ride-sharing), está a preparar o seu lançamento no competitivo mercado de Chicago. Para garantir uma entrada estratégica e otimizar a alocação de recursos, foi necessário analisar o comportamento dos passageiros, mapear os principais concorrentes e entender o impacto de fatores meteorológicos na operação.

Neste projeto, conduzi uma análise exploratória de dados e testes de hipóteses estatísticos para identificar padrões de mobilidade urbana e ditar o direcionamento de negócio para a direção da empresa.

## 🔗 Links Rápidos
* **[Dashboard Interativo no Tableau Public](https://public.tableau.com/app/profile/marcelo.aragao/viz/Dashboard_Zuber_Analytics_Chicago/DashboardExecutivoZuber?publish=yes)**
* **[Apresentação Executiva (PDF)](Apresentacao_Executiva_Zuber.pdf)**

## 🛠️ Ferramentas e Tecnologias
* **Linguagem:** Python
* **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
* **Ambiente:** Jupyter Notebook
* **Visualização:** Tableau
* **Técnicas:** Testes de Hipóteses (Welch's t-test), Análise Exploratória de Dados (EDA), Limpeza e Estruturação de Dados, Storytelling de Dados.

## 📂 Estrutura do Repositório
* `notebook_Sprint7.ipynb`: Código-fonte com a análise exploratória, tratamento de dados e testes estatísticos (incluindo Violinplots de densidade).
* `moved_project_sql_result_01.csv`: Base de dados de viagens por empresa (Market Share).
* `moved_project_sql_result_04.csv`: Base de dados de média de viagens por destino.
* `moved_project_sql_result_07.csv`: Base de dados de viagens (Loop -> O'Hare) com condições climáticas.
* `Apresentacao_Executiva_Zuber.pdf`: Relatório visual contendo a estratégia de negócios e recomendações de lançamento.
* `requirements.txt`: Lista de dependências para reprodução do ambiente.

## 💡 Principais Insights Comerciais
1. **O Domínio da Concorrência:** O mercado é liderado isoladamente pela **Flash Cab**. Contudo, existe uma vasta "cauda longa" de pequenas empresas com fatias de mercado consideráveis que podem ser absorvidas por um player tecnológico.
2. **O Centro do Lucro:** Os bairros **Loop** e **River North** não são apenas os mais populares; eles concentram a esmagadora maioria dos destinos, provando ser o verdadeiro motor corporativo e financeiro de Chicago.
3. **O Fator Chuva:** Testes estatísticos rigorosos confirmaram que o clima afeta severamente a mobilidade. Nos sábados chuvosos, uma viagem entre o centro (Loop) e o aeroporto (O'Hare) demora, em média, **7 minutos a mais**.

## 🚀 Recomendação Final de Lançamento
A estratégia de entrada da Zuber não deve tentar um combate direto de frota contra a líder atual de imediato. A alocação de orçamento de marketing e a captação de motoristas devem focar quase exclusivamente no eixo Loop/River North. Adicionalmente, o algoritmo da aplicação deve ser configurado para ativar **precificação dinâmica (surge pricing)** automaticamente ao detetar chuva aos sábados nestas rotas críticas, compensando os motoristas pelo tempo de viagem estendido e garantindo a oferta corporativa.

---
*Desenvolvido por Marcelo - Analista de Dados*
