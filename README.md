# Projeto: Análise de Filmes do IMDb Top 250

Este projeto realiza uma análise do ranking Top 250 Filmes do IMDb.

**Fases do Projeto:**
1.  **Web Scraping:** Coleta de dados do site do IMDb utilizando Python, Requests, Selenium e Beautiful Soup.
2.  **Limpeza de Dados:** Tratamento dos dados coletados com a biblioteca Pandas.
3.  **Análise Exploratória (EDA):** Geração de insights e visualizações sobre décadas e diretores em relação às notas.

**Estrutura do projeto**
analise_IMDb/

│── data/

    │── processed/ (Resultado do tratamento dos dados do Web Scraping)

    │── raw/ (Resultado do Web Scraping)

│── notebooks/ (Notebooks de raspagem, exploração e análise)

│── requirements.txt (Dependências, bibliotecas Python)

│── README.md (Documentação do projeto)

**Como Executar:**
1. Clone o repositório.
2. Crie um ambiente virtual: `python -m venv venv`
3. Instale as dependências: `pip install -r requirements.txt`
4. Abra e execute os notebooks na pasta `/notebooks`.