# BuscadorRI
Esse projeto é um buscador completo. Inclui a coleta, armazenamento e compressão de arquivos, indexação e compressão do índice de termos, além de usar um modelo de busca que disponibiliza um retorno rankeado para pesquisas. O objetivo é que a busca seja completamente concluída em um determinado domínio, com otimização das ferramentas técnicas utiizadas.

É necessário que:
1. Para crawler:
  - Seja registrada a proposta de responsabilidade do buscador e critérios a serem usados
  - As boas práticas usadas sejam registradas conjuntamente
  - Sejam listados os domínios a serem explorados (um mapa de sublinks para cada domínio, até o momento)
  - O html de cada ramificação de cada domínio seja lido
  - Condição de parada de coleta
2. Para indexação:
  - Limpeza de termos
  - Tratamento léxico
  - Indexação de termos com índice invertido
  - Declarar tamanho da indexação
3. Para retorno de buscas e ranking:
