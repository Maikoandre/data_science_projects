# 📊 Portfólio de Projetos de Data Science

Bem-vindo(a) ao repositório central dos meus projetos voltados à Ciência de Dados, Machine Learning e Análise de Dados! Este repositório tem como objetivo servir como um portfólio organizado e em contínua evolução, onde documento meus estudos, experimentos e resoluções de problemas usando Python.

## 📁 Estrutura do Repositório

O repositório foi organizado de forma que cada novo projeto possua sua própria pasta dedicada com os arquivos necessários (código, dados e anotações específicas). 

Atualmente, os projetos desenvolvidos (e em desenvolvimento) incluem:

| # | Projeto | Descrição Resumida |
|---|---------|--------------------|
| 1 | [🏥 DataSUS Analysis](https://github.com/Maikoandre/datasus_analysis) | Análise Exploratória e Dashboard Interativo com Streamlit sobre internações hospitalares (SIH) na Bahia. |
| 2 | [⚡ Avaliação de Desempenho de Libs](https://github.com/Maikoandre/avaliacao_desempenho_libs) | Comparação de desempenho entre Pandas, Polars, DuckDB e PySpark. |
| 3 | [🌌 Cosmic Scribe](https://github.com/Maikoandre/cosmic_scribe) | Sistema RAG especializado em worldbuilding e expansão de lore de universo fictício. |
| 4 | [🤖 Data Analysis Agent](https://github.com/Maikoandre/data_analysis_agent) | Agente autônomo que analisa datasets CSV via RAG e envia relatórios em PDF por email. |

*(Mais projetos serão adicionados com o tempo!)*

## 🚀 Como Executar Localmente

O ambiente principal baseia-se em **Python 3.12+**. 

1. **Clone o repositório:**
   Como este repositório utiliza *Git Submodules* para referenciar os projetos, use a flag `--recurse-submodules` para clonar o repositório e baixar o conteúdo das pastas ao mesmo tempo:
   ```bash
   git clone --recurse-submodules https://github.com/Maikoandre/data_science_projects.git
   cd data_science_projects
   ```
   *(Se você já clonou sem a flag, basta rodar `git submodule update --init --recursive` dentro da pasta)*

2. **Configure o ambiente virtual:**
   Na raiz do repositório, você pode inicializar um ambiente virtual padrão Python para baixar pacotes e dependências:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # No macOS/Linux
   # ou .venv\Scripts\activate no Windows
   ```

3. **Gerenciamento e Dependências:**
   Verifique na raiz do projeto (ou dentro da pasta específica de cada projeto) os requisitos específicos. A raiz inclui um `pyproject.toml` base.

---
*Repositório em constante atualização.* 🧑‍💻📈
