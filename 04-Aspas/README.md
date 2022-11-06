# Aspas no PHP

No PHP pode-se usar tanto aspas simples como duplas, pórem tem algumas diferenças.

```
$aspaSimples = 'Gabriel';
$aspaDupla   = "Carla";
```

A diferença está em que na aspas duplas eu posso escrever variáveis dentro da string e ele ira mostrar o valor da variavel, nas aspas simples não, sendo necessario fazer concatenação. Veja abaixo:

```
$nome = "Gabriel";

echo "O seu nome é {$nome}";

echo 'O seu nome é ' . $nome;
```

Veja que foi usado {} dentro das aspas duplas, não é obrigátorio, apenas serve para mostrar que aquela parte é uma variavel e não um texto.
