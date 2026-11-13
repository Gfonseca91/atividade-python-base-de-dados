```markdown
# 🎤 Análise de Shows e Eventos com Pandas

Este projeto realiza uma análise exploratória de dados e engenharia de recursos simples sobre um conjunto de dados de shows e eventos musicais no Brasil. O objetivo é extrair insights valiosos sobre vendas, capacidade e faturamento dos eventos.

## 🚀 Funcionalidades

- **Carga de Dados:** Leitura e estruturação da base de dados (`shows_eventos.csv`).
- **Exploração e Estatística Descritiva:** Análise quantitativa (`describe`) e qualitativa dos eventos, artistas, gêneros e cidades.
- **Engenharia de Recursos (Feature Engineering):**
  - Cálculo de **Receita** gerada por show.
  - Cálculo da **Taxa de Ocupação** de cada evento (relação entre ingressos vendidos e capacidade do local).
- **Exportação:** Salvamento dos dados enriquecidos para um novo arquivo (`shows_eventos_novo.csv`).

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas** (Análise e manipulação de dados)

## 📊 Estrutura dos Dados

A base de dados contém as seguintes colunas principais:
- `Artista`: Nome do artista/banda.
- `Genero`: Gênero musical.
- `Cidade`: Cidade onde ocorreu o show.
- `Ingressos_Vendidos`: Total de ingressos comprados.
- `Capacidade_Local`: Capacidade total do estabelecimento.
- `Preco_Medio_Ingresso`: Valor médio cobrado por ingresso.
- `receita` *(Nova)*: Faturamento total calculado (`Ingressos_Vendidos * Preco_Medio_Ingresso`).
- `Taxa de ocupação` *(Nova)*: Porcentagem de ocupação do espaço público.

---
*Desenvolvido em ambiente Google Colab.*
```
