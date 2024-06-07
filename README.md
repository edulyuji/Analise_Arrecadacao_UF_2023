# Análise de Arrecadação de Impostos por Estados em 2023

## Descrição
Este projeto tem como objetivo analisar a arrecadação de impostos pelos estados brasileiros durante o ano de 2023. Utilizando a linguagem de programação Python, juntamente com as bibliotecas Pandas e Matplotlib, foi realizado todo o processo de extração, tratamento e preparação dos dados para análise.

## Objetivos
- Analisar a arrecadação total de impostos por estado.
- Analisar detalhadamente os seguintes tipos de impostos:
   1. **Impostos sobre Importação e Exportação**
      - IMPOSTO SOBRE IMPORTAÇÃO
      - IMPOSTO SOBRE EXPORTAÇÃO
   2. **Impostos sobre Produtos Industrializados**
      - IPI - FUMO
      - IPI - BEBIDAS
      - IPI - AUTOMÓVEIS
      - IPI - VINCULADO À IMPORTAÇÃO
      - IPI - OUTROS
   3. **Impostos sobre Renda**
      - IRPF
      - IRPJ - ENTIDADES FINANCEIRAS
      - IRPJ - DEMAIS EMPRESAS
   4. **Impostos Retidos na Fonte**
      - IRRF - RENDIMENTOS DO TRABALHO
      - IRRF - RENDIMENTOS DO CAPITAL
      - IRRF - REMESSAS P/ EXTERIOR
      - IRRF - OUTROS RENDIMENTOS
   5. **Impostos sobre Operações Financeiras**
      - IMPOSTO S/ OPERAÇÕES FINANCEIRAS
   6. **Impostos sobre Propriedade Rural**
      - IMPOSTO TERRITORIAL RURAL
   7. **Contribuições para a Seguridade Social**
      - COFINS - FINANCEIRAS
      - COFINS - DEMAIS
      - CONTRIBUIÇÃO PARA O PIS/PASEP - FINANCEIRAS
      - CONTRIBUIÇÃO PARA O PIS/PASEP - DEMAIS
      - CSLL - FINANCEIRAS
      - CSLL - DEMAIS
      - CPSSS - Contrib. p/ o Plano de Segurid. Social Serv. Público
   8. **Contribuições de Intervenção no Domínio Econômico**
      - CIDE-COMBUSTÍVEIS
   9. **Outras Receitas**
      - OUTRAS RECEITAS ADMINISTRADAS
      - RECEITA PREVIDENCIÁRIA
      - ADMINISTRADAS POR OUTROS ÓRGÃOS

## Processo
- Foi realizada uma análise descritiva de todos os impostos, calculando o máximo, mínimo, mediana e média.
- Foi plotado os gráficos para visualização da arrecadação de cada imposto por estado em 2023.

## Fonte dos Dados
Os dados foram obtidos através do [Portal Brasileiro de Dados Abertos](https://dados.gov.br/dados/conjuntos-dados/resultado-da-arrecadacao).

## Ferramentas Utilizadas
- Python
- Biblioteca Pandas
- Biblioteca Matplotlib
