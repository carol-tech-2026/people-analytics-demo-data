# people-analytics-demo-data

**Dados FICTÍCIOS.** Nenhuma pessoa aqui existe: nomes, salários, datas,
gênero, raça e desligamentos saem de um gerador com semente fixa.

Servem para carregar o banco de demonstração do People Analytics. Gerados por
`scripts/demo/empresa/exportar.ts` (repositório do app) e carregados por
`scripts/demo/empresa/carregar.sql`, que baixa os arquivos daqui.

`empresa/<tabela>.json` — um array de linhas por tabela, com as colunas da tabela.
