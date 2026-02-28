# Dashboards de Vendas – Intensivão de Power BI

Repositório com os dashboards desenvolvidos ao longo das 4 aulas do Intensivão de Power BI da Hashtag Treinamentos, partindo do zero até a construção de painéis de vendas mais completos.

---

## Objetivo do projeto

- Praticar construção de dashboards de vendas no Power BI Desktop.  
- Exercitar etapas de importação, tratamento de dados (Power Query), modelagem simples e criação de visuais.  
- Construir um portfólio público de estudos em Business Intelligence.

---

## Estrutura do repositório

- `aula-1/`  
  - `Aula 1 - Dashboard de Vendas.pbix`  
  - `baseVendas.xlsx` (base de exemplo da aula)  
  - `img-dashboard1.png` (print do dashboard)  
- `aula-2/`  
  - `Aula 2 - Dashboard de Produção.pbix` 
  - `baseProdução.xlsx` (base de exemplo da aula)
  - `img-dashboard2.png` (print do dashboard)
- `aula-3/`
  - `Aula 3 - Dashboard de RH.pbix` 
  - `baseFuncionarios.xlsx` (base de exemplo da aula)
  - `img-dashboard3.png` (print do dashboard)
- `aula-4/`  
  - `Aula 4 - Dashboard Financeiro.pbix`
  - `Base de Dados - Financeiro.xlsx` (base de exemplo da aula)
  - `img-dashboard4.png` (print do dashboard)

> Observação: os nomes dos arquivos e pastas podem ser ajustados conforme o andamento das aulas, mantendo a mesma ideia de separar cada aula em seu próprio diretório.

---

## Como visualizar os dashboards

1. Baixe o arquivo `.pbix` da pasta da aula desejada.  
2. Abra com o **Power BI Desktop** (versão mais recente).  
3. Se necessário, aponte a conexão de dados para o arquivo Excel correspondente (mantendo mesma estrutura de colunas).  

---

## Aula 1 – Dashboard de Vendas do Zero

Primeira aula focada em sair do zero até um dashboard de vendas interativo.

### Conteúdo trabalhado

- Instalação e introdução ao Power BI Desktop.  
- Importação de dados de vendas a partir de um arquivo Excel (`baseVendas.xlsx`).  
- Tratamento de dados no **Power Query**:
  - Remoção de colunas e linhas em branco.  
  - Criação de coluna de **Cliente** (Nome Sobrenome) usando *Coluna de Exemplos*.  
  - Separação da coluna de **Localidade** em **País** e **Continente**.  
  - Criação da coluna calculada de **Faturamento** (Preço Unitário × Quantidade Vendida).  
  - Ajuste de tipos de dados e boas práticas de renomeação de colunas e tabela.  
- Construção do relatório:
  - Cartão de **Faturamento Total**.  
  - Cartão com **Produto mais vendido** (filtro Top N).  
  - Gráfico de **Colunas + Linha** com Faturamento × Quantidade Vendida por Ano/Mês.  
  - Gráfico de **Barras** com Faturamento por Marca.  
  - Mapa (Azure Maps) com Faturamento por Continente (ou gráfico alternativo, caso o mapa não esteja disponível).  
- Noções de interatividade: filtros entre visuais e uso de rótulos de dados, títulos e formatações para melhorar a leitura.

### Imagem do dashboard – Aula 1

<img width="694" height="390" alt="img-dashboard1" src="Aula 1/img-dashboard1.png" />

---

## Aula 2 – Dashboard de Produção do Zero

Nesta aula, o foco foi a criação de um Dashboard de Produção, explorando novas métricas e visualizações de eficiência e produtividade.

### Conteúdo trabalhado

- Importação e Tratamento de Dados:
  - Importação da base de produção (baseProdução.xlsx).
  - Uso do Power Query para limpeza e padronização.
- Cálculos e Indicadores (DAX):
  - Criação de medidas para Total Produzido, Total Rejeitado e Total de Horas.
  - Cálculo de Eficiência (%) e Índice de Rejeição.
- Construção do Relatório:
  - Cartões: KPIs principais (Total Produzido, Eficiência, Horas).
  - Gráfico de Velocímetro: Para visualização de metas de produção com formatação condicional.
  - Gráfico de Linhas: Acompanhamento da produção ao longo do tempo.
  - Gráfico de Barras: Comparativo de produção por turno ou máquina.
- Design e Interatividade:
  - Aplicação de temas e cores para um dashboard industrial/profissional.
  - Configuração de filtros interativos para análise por período e setor.

### Imagem do dashboard – Aula 2

<img width="694" height="390" alt="img-dashboard2" src="Aula 2/img-dashboard2.png" />

---

## Aula 3 – Dashboard de RH do Zero

Nesta aula, o foco foi o desenvolvimento de um Dashboard de Recursos Humanos (People Analytics), focado em indicadores de contratação, retenção e perfil dos colaboradores.

### Conteúdo trabalhado

- Importação e Modelagem de Dados:
  - Importação de bases de RH (Base de Dados - RH.xlsx).
  - Tratamento de dados no Power Query para garantir a integridade das informações de funcionários.
- Métricas de People Analytics (DAX):
 - Cálculo de Total de Funcionários, Contratações e Desligamentos.
 - Desenvolvimento do cálculo de Turnover (Rotatividade).
 - Análise de Salarial Médio e distribuição por departamento.
- Construção do Relatório e Visuais Avançados:
 - Cartões de KPI: Exibição clara do Headcount e taxa de Turnover.
 - Gráfico de Árvore de Decomposição: Para análise detalhada (drill-down) dos motivos de saída ou distribuição por área.
 - Gráficos de Rosca/Pizza: Perfil demográfico e diversidade.
- Recursos de Experiência do Usuário (UX):
 - Tooltips (Dicas de Ferramenta): Criação de janelas flutuantes personalizadas para detalhar dados ao passar o mouse.
 - Configuração de botões de navegação e filtros por status (Ativo/Inativo).

## Imagem do dashboard – Aula 3
<img width="694" height="390" alt="img-dashboard3" src="Aula 3/img-dashboard3.png" />

## Aula 4 – Dashboard Financeiro do Zero

A última aula do curso foi dedicada à criação de um Dashboard Financeiro completo, focado em análise de fluxo de caixa, rentabilidade e performance bancária.

### Conteúdo trabalhado

- **Tratamento de Dados Financeiros:**
  - Importação e consolidação de bases de receitas e despesas no **Power Query**.
  - Ajustes de categorias financeiras e tratamento de datas.
- **Análises e Fórmulas DAX:**
  - Criação de medidas para **Receita Total**, **Despesas**, **Impostos** e **Lucro Líquido**.
  - Cálculo de **Margem de Lucro (%)**.
  - Análise comparativa de movimentações entre diferentes instituições bancárias.
- **Visualizações e Storytelling:**
  - **Gráfico Scroller:** Implementação de uma barra de indicadores animada para monitoramento em tempo real.
  - **Gráficos de Área e Linhas:** Acompanhamento da evolução histórica do lucro e fluxo de caixa.
  - **Storytelling:** Organização do layout para facilitar a leitura rápida de KPIs financeiros.

### Imagem do dashboard – Aula 4

<img width="694" height="390" alt="img-dashboard4" src="Aula 4/img-dashboard4.png" />

---

## Conclusão

A conclusão deste intensivo permitiu consolidar conhecimentos fundamentais de Business Intelligence, desde o tratamento de dados brutos (ETL) até a criação de dashboards estratégicos para cada setor. O projeto reforça a importância da visualização de dados para a tomada de decisão assertiva no ambiente corporativo.

## Próximos Passos

Como estudante de Data Science, o próximo objetivo para este repositório será:
- **Análise com Python:** Utilizar as bases de dados `.xlsx` disponibilizadas nas aulas para realizar análises exploratórias (EDA) utilizando bibliotecas como **Pandas**, **Matplotlib** e **Seaborn**.
- **Comparação de Ferramentas:** Validar os insights gerados no Power BI através de scripts em Python, unindo o poder da visualização com a profundidade da análise estatística.


```markdown



