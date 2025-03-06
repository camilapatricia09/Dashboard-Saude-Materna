# Dashboard de Monitoramento da Saúde Materna

Sistema de Business Intelligence (BI) desenvolvido para monitoramento da saúde materna em Cidades Inteligentes. O objetivo é facilitar a análise de dados e apoiar a gestão pública na tomada de decisões.

## Objetivo

O sistema permite o monitoramento da mortalidade materna, fornecendo indicadores visuais e relatórios interativos que auxiliam na análise dos dados.

## Como Usar

1. Baixe e instale o [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Abra o arquivo `dashboard-saude-materna.pbix`.
3. Conecte os dados de entrada conforme descrito no Manual do Usuário.
4. Explore os relatórios e dashboards para visualizar os indicadores de saúde materna.

## Tecnologias Utilizadas

- **Power BI Desktop** - Construção do dashboard interativo.
- **Power Query** - Processo de ETL (Extração, Transformação e Carga de dados).
- **DAX (Data Analysis Expressions)** - Criação de métricas e cálculos analíticos.

## Estrutura do Projeto

📁 Dashboard-Saude-Materna

│── 📂 dados/ # Conjunto de dados utilizados (CSV)

│── 📂 documentacao/ # Manuais do usuário e desenvolvimento

│── 📜 Dashboard_Saude_Materna.pbix # Arquivo principal do Power BI

│── 📜 README.md # Documentação principal do projeto


## Fontes de Dados

O dashboard utiliza dados de mortalidade materna, estruturados no seguinte formato:

| Campo            | Tipo    | Descrição                                      |
|-----------------|--------|----------------------------------------------|
| Ano            | Inteiro | Ano da ocorrência                            |
| Município      | Texto   | Nome do município                           |
| ÓbitosMaternos | Inteiro | Número total de óbitos maternos             |
| NascidosVivos  | Inteiro | Total de nascidos vivos                     |
| TaxaMortalidade | Decimal | (ÓbitosMaternos / NascidosVivos) * 100.000 |

## Processos de ETL (Power Query)

1. **Extração**: Importação dos arquivos CSV.
2. **Transformação**: Limpeza, padronização e criação de indicadores.
3. **Carga**: Armazenamento e relacionamento dos dados no Power BI.

## Melhorias Futuras

Integração com APIs para atualização automática dos dados.
Expansão dos indicadores para incluir dados socioeconômicos.
Melhorias na interface para otimizar a experiência do usuário.

## Como Contribuir

Caso queira sugerir melhorias ou reportar problemas, abra uma issue ou envie um pull request.
Contato: camilaufs1@gmail.com
