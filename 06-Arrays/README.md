# Arrays
Um array é, na verdade, um mapa ordenado. Ou seja, é um tipo que relaciona valores a chaves.
Para se criar um array:

```
// Pode ser feito assim
$carros = array("GOL", "FOX", "FIESTA");

// ou
$carros = ["GOL", "FOX", "FIESTA"];

// ou
$carros = array();
$carros[] = "GOL";
$carros[] = "FOX";
$carros[] = "FIESTA";
```

Para acessar uma informação do array basta informar a posição partindo-se do inicio 0.

```
echo $carro[0];

// Imprime GOL
```

Para adicionar um elemento no array.

```
$carros[] = "ONIX";
```

É adicionado esse valor ao final do array, criando mais uma posição.
