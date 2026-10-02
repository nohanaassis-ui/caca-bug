| Erro encontrado | Causa | Solução |

| Construtor não salvava os dados** | Falta do `this', fazendo a variável atribuir o valor a ela mesma. | Adicionado `this.nome = nome` e `this.salario = salario`. |
| Cálculo de aumento incorreto| Estava somando o valor do percentual direto no salário, sem calcular a porcentagem. | Alterado para `salario += salario * (percentual / 100)`. |