# Dashboards de Vendas – Intensivão de Power BI

Repositório com os dashboards desenvolvidos ao longo das 4 aulas do Intensivão de Power BI da Hashtag Treinamentos, partindo do zero até a construção de painéis de vendas mais completos.

> Status: em andamento – atualmente documentada a **Aula 1**. As seções das Aulas 2, 3 e 4 serão preenchidas conforme forem avançando.

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
  - (arquivos da segunda aula – a definir)  
- `aula-3/`  
  - (arquivos da terceira aula – a definir)  
- `aula-4/`  
  - (arquivos da quarta aula – a definir)

> Observação: os nomes dos arquivos e pastas podem ser ajustados conforme o andamento das aulas, mantendo a mesma ideia de separar cada aula em seu próprio diretório.

---

## Como visualizar os dashboards

1. Baixe o arquivo `.pbix` da pasta da aula desejada.  
2. Abra com o **Power BI Desktop** (versão mais recente).  
3. Se necessário, aponte a conexão de dados para o arquivo Excel correspondente (mantendo mesma estrutura de colunas).  

No futuro, alguns dashboards podem ser publicados também via URL (Power BI Service) e os links serão adicionados nas seções de cada aula.

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
<img width="694" height="390" alt="img-dashboard1" src="https://github.com/user-attachments/assets/ae88fb28-ec3e-49fb-ae02-286f065f3ea8" />


```markdown


