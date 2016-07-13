# Introdução

O projeto começou como um script em Python para baixar os ZIPs da Bovespa e manipular os dados disponíveis, balanços e demonstrativos em geral. Com isso seria feita a mineração de dados com o objetivo final de tornar simples o batimento e consolidação de informações.

No entanto, no meio do projeto o foco se tornou a criação de scripts para backtesting voltado para a cotação dos papéis. A versão Alpha provavelmente terá apenas esse fim com uma pequena parcela de seleção de ativos.

Atualmente, todo tipo de controle de valores está nesse repositório (ações, finanças, bitcoins).


# Todo

- Exportar facilmente todos os dados usados no backtesting (para análise) em CSV
  - www.gadzmo.com/python/reading-and-writing-csv-files-with-python-dictreader-and-dictwriter/
  - Começando pelo quote
    - Atualmente um dicionário com cada coluna sendo uma lista de elementos
    - Deve virar o formato que o pyCsv escreve e lê
- Facilitar inclusão de diferentes backtesting (como venda)
  - Suportar venda
  - Suporte a contratos futuros
- Agilizar cálculo para seleção atual de papéis (modo não-backtesting)
- Implementar o BovespaBacktesting das minhas ações atuais.

