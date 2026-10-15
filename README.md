# Dashboard de Vendas Porsche

Dashboard interativa desenvolvida para o desafio educacional da DIO,
utilizando uma base fictícia de 100 vendas. O projeto foi criado em
HTML, CSS e JavaScript em um único arquivo, com os dados incorporados ao
próprio HTML.

> **Atenção:** os dados são fictícios e destinados exclusivamente ao
> exercício. Os valores financeiros são exibidos em dólares americanos
> (US\$), conforme a interpretação adotada para a base do desafio.

## Perguntas de negócio

### 1. Quais modelos geram maior receita registrada e maior volume de vendas?

A comparação entre receita somada e quantidade de registros ajuda a
identificar modelos que concentram o valor financeiro e aqueles que
aparecem com maior frequência nas vendas. Essa leitura pode apoiar a
investigação de prioridades comerciais por modelo.

### 2. Quais estados concentram as vendas e a receita registrada?

A análise geográfica compara a quantidade de vendas e a soma dos preços
por estado. Isso permite observar diferenças entre mercados com maior
volume de transações e mercados com maior valor financeiro registrado.

### 3. Qual é a situação das vendas e das entregas?

A distribuição por status mostra quantos registros estão entregues, em
trânsito ou em outras situações existentes na base, além do valor
associado a cada status. Isso ajuda a acompanhar a situação operacional
registrada, sem presumir que uma venda corresponda necessariamente a um
pagamento recebido.

## Indicadores e filtros

A dashboard apresenta indicadores de vendas registradas, receita
registrada, preço médio por venda e percentual de vendas entregues.

Filtros disponíveis: - Data inicial e data final da venda; - Modelo
Porsche; - Estado; - Forma de pagamento; - Status da entrega.

Os gráficos e indicadores são atualizados conforme os filtros aplicados.
Há também opções para alterar a métrica de ordenação nos gráficos de
modelos e estados e um controle para limpar os filtros.

## Prompt utilizado e refinamentos

O pedido inicial foi elaborado a partir do enunciado da DIO e refinado
durante a conversa com o ChatGPT. A orientação central foi:

> Crie uma dashboard executiva interativa de vendas da Porsche em um
> único arquivo HTML, com CSS e JavaScript incorporados e os dados da
> planilha incluídos no próprio arquivo. A interface deve estar
> integralmente em português brasileiro, preservando os nomes próprios
> de cidades e estados. Use uma identidade visual executiva inspirada na
> Porsche, com fundo escuro, contraste alto e detalhes discretos em
> vermelho. Inclua indicadores de vendas registradas, receita
> registrada, preço médio por venda e percentual de vendas entregues;
> filtros por intervalo de datas, modelo, estado, forma de pagamento e
> status da entrega; e gráficos que respondam às três perguntas de
> negócio definidas neste README. Faça com que os indicadores e gráficos
> reajam aos filtros, inclua a opção de limpar os filtros e trate os
> casos sem resultados. Não dependa de bibliotecas externas nem de
> arquivos adicionais. Identifique claramente a base como fictícia e não
> apresente a soma dos preços como dinheiro efetivamente recebido.

### O que foi refinado

-   As análises foram reduzidas a três perguntas de negócio: modelos e
    receita, desempenho por estado e situação das entregas.
-   A interface foi especificada em português brasileiro, mantendo nomes
    de cidades e estados como aparecem na base.
-   Foram definidos filtros que permitem explorar diferentes recortes da
    amostra.
-   Os indicadores foram descritos como valores registrados na base,
    evitando afirmar que representam recebimentos efetivos.
-   Foi solicitado um arquivo HTML autossuficiente, sem dependência de
    arquivos ou bibliotecas externos.

## Tratamento da base de dados

Foi utilizada a planilha sanitizada disponibilizada para o exercício,
com 100 registros de vendas e campos relativos a data, modelo, ano do
veículo, preço, quilometragem, forma de pagamento, cidade, estado,
vendedor e status da entrega.

O tratamento aplicado para a dashboard incluiu: - Uso dos campos
sanitizados da base, em vez dos campos crus; - Conversão dos registros
para uma estrutura de dados incorporada ao HTML; - Padronização dos
rótulos de campos e categorias exibidos na interface para português; -
Interpretação de data, preço, ano do modelo e quilometragem em formatos
adequados aos filtros e cálculos; - Cálculo dos indicadores e agregações
diretamente no navegador; - Identificação visual da base como fictícia.

As datas futuras existentes na base foram mantidas por fazerem parte da
simulação educacional. Nenhum dado pessoal real foi intencionalmente
incluído.

## Ferramenta utilizada

O projeto foi elaborado com **ChatGPT**, a partir da planilha e das
instruções do desafio. A versão entregue foi gerada diretamente como
arquivo HTML; não foi utilizado um agente com skill própria. O fluxo
documentado não depende do Canvas.

## Arquivos do projeto

-   `index.html` --- dashboard completa, com estilos, lógica interativa
    e dados incorporados.
-   `README.md` --- documentação do projeto.

## Publicação

**Repositório público:** `https://github.com/KukielSCBr/dashboard-porsche-vendas/`

**Dashboard publicada no GitHub Pages:**
`COLE_AQUI_O_LINK_DO_GITHUB_PAGES`

Após criar o repositório público e ativar o GitHub Pages nas
configurações, substitua os dois campos acima pelos endereços reais. O
arquivo principal deve estar nomeado `index.html` na raiz do
repositório.

## Validação antes da entrega

-   [ ] O repositório está público.
-   [ ] O arquivo principal se chama `index.html` e está na raiz.
-   [ ] O GitHub Pages está ativado e a página abre pelo link publicado.
-   [ ] Os filtros de data, modelo, estado, forma de pagamento e status
    funcionam.
-   [ ] Os indicadores e gráficos mudam quando os filtros são aplicados.
-   [ ] O botão para limpar filtros funciona.
-   [ ] O README contém os links reais do repositório e da dashboard.
-   [ ] Foi capturada uma imagem da dashboard aberta e, se possível,
    outra com um filtro aplicado.
