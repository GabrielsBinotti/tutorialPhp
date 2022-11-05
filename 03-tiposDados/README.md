## Tipos de dados

### Dados escalares
São as que contém integer, float, string ou boolean.
```
$nome = "Gabriel"; // string
$idade = 29; // inteiro
$altura = 1.67 // float
$male = true // boleano
```

#### Função para ver o tipo dos dados.

```
var_dump($variavel)
```

#### Função para verificar se o tipo da variavel é uma string.

```
is_string($variavel) // retornar um true ou false
```

#### Função para verificar se o tipo da variavel é um int.

```
is_int($variavel) // retornar um true ou false
```

#### Função para verificar se o tipo da variavel é um float.

```
is_float($variavel) // retornar um true ou false
```

#### Função para verificar se o tipo da variavel é um boolean.

```
is_bool($variavel) // retornar um true ou false
```


### Dados compostos
Variaveis compostas são variáveis que armazenam um conjunto de dados, podendo ser elas do mesmo tipo ou não, por exemplo:

#### Array
É uma variavel composta que armazena dados do mesmo tipo ou não.
```
$array = ["Gabriel", "Carla", "Gustavo", "Amanda"];
```

#### Objeto
Quando criamos classes, irei abordar mais adiante no arquivo apenas de classe.

#### Função para verificar se é array e para verificar se é objeto

```
is_array($variavel); // retornar um true ou false
is_object($variavel); // retornar um true ou false
```
