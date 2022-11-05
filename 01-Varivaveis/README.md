## Variáveis

Para fazer uma declaração de variável em PHP é simples, basta usar o sinal <strong>$</strong> seguida do nome da variável e por fim atribuit um valor.

```
$nome = "Gabriel Binotti";
```

### Alguns detalhes:
 * O PHP não permite a declaração de variável sem atribuir valor.
 * Não é necessario atribuir o tipo da variável.
 * Possui tipagem dinamica, o tipo da variável é definido de acordo com o valor atribuido.

## Regras para nomeação de variável
 * Sempre começar com cifrão <strong>$</strong>
 * São sensiveis, ou seja, $nome é diferente de $Nome
 * Não pode começar com número ou caracterer especial
 * $this é uma variavel especial
 
 ```
$nome = "Elton Fonseca";

echo gettype($nome); // string

$nome = 28;

echo gettype($nome); // integer

$nome = 78.500;

echo gettype($nome); // float

$nome = true;

echo gettype($nome); //boolean
 ```
 
