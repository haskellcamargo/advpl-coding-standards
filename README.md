# AdvPL Coding Standards

### Estilo

- Espaços ao invés de tabs
- 3 espaços
- Sempre use notação húngara em nomes de variáveis
- Evite nomes de variáveis como `nX` ou `nY`. Seja mais descritivo
- Palavras-chave da linguagem devem usar **UpperCamelCase** (exemplos: `If`, `EndIf`, `While`)
- Nomes de variáveis locais devem ser em **lowerCamelCase** (exemplos: `cName`, `nAge`)
- Nomes de funções em notação húngara devem usar **lowerCamelCase** (exemplo: `aAdd`)
- Nomes de funções sem notação húngara devem usar **UpperCamelCase** (exemplo: `RetSqlName`)
- Deve haver 1 espaço entre os argumentos de função e arrays (exemplo: `RetSqlName( 'STJ' )`)
- Deve haver 1 espaço após cada vírgula (exemplo: `{ 1, 2, 3 }`)
- Evite ultrapassar 80 colunas horizontalmente. Quebre o código quando necessário
- Valores lógicos devem usar caixa alta (exemplo: `.F.`)

### Redundância

- Não faça `== .T.`

### Operadores

- Use `!=` ao invés de `<>`

