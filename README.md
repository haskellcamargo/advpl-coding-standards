# AdvPL Coding Standards

### Arquivo

- A extensão deve ser minúscula (exemplo: `.prw`)

### Estilo

- Espaços ao invés de tabs
- 3 espaços e indentação contextual
- Sempre use notação húngara em nomes de variáveis
- Evite nomes de variáveis como `nX` ou `nY` (exceto para índices). Seja mais descritivo
- Palavras-chave da linguagem devem usar **UpperCamelCase** (exemplos: `If`, `EndIf`, `While`)
- Nomes de variáveis locais devem ser em **lowerCamelCase** (exemplos: `cName`, `nAge`)
- Nomes de funções em notação húngara devem usar **lowerCamelCase** (exemplo: `aAdd`)
- Nomes de funções sem notação húngara devem usar **UpperCamelCase** (exemplo: `RetSqlName`)
- Deve haver 1 espaço entre os argumentos de função, blocos e arrays (exemplo: `RetSqlName( 'STJ' )`)
- Deve haver 1 espaço após cada vírgula (exemplo: `{ 1, 2, 3 }`)
- Evite ultrapassar 80 colunas horizontalmente. Quebre o código quando necessário
- Valores lógicos devem usar caixa alta (exemplo: `.F.`)
- Espaço entre operadores. Use `nValue > nExpected` ao invés de `nValue>nExpected`
- `Return` indentado, já que faz parte da estrutura da função e **não** é um terminador
- Em comentários, 1 espaço após `//`
- Idioma padronizado. Evite misturar português e inglês quando possível
- Deixar 1 linha em branco para cada *statement*, exceto conjuntos de *statements*
- Deixar 1 linha vazia no final de cada arquivo
- Prefira aspas simples `'` ao invés de duplas `"`
- Para acesso de índices múltiplos, evite `aList[ nI ][ nJ ]`. Use `aList[ nI, nJ ]`
- Funções **não** devem receber mais que 6 parâmetros
- Evite aninhamentos com mais de 3 statements (exemplo: `If` dentro de `If` dentro de `If`)
- Use `!=` ao invés de `<>`
- Não faça `== .T.`
