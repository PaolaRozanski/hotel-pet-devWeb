# ESTUDO ASSÍNCRONO

### 1. O que é uma função assíncrona? Por que buscar dados de uma API é uma operação assíncrona?

É uma função que consegue esperar uma tarefa terminar sem parar o resto da página. Buscar dados de uma API é assíncrono porque precisa esperar o servidor responder.

### 2. O que é uma Promise? O que significam `pending`, `fulfilled` e `rejected`?

Promise é algo que representa uma tarefa que ainda está acontecendo ou que vai ter um resultado.

- **pending:** está esperando.
- **fulfilled:** deu certo.
- **rejected:** deu errado.

### 3. Para que servem `async` e `await`? O que acontece enquanto espera?

O `async` mostra que a função é assíncrona e o `await` faz ela esperar uma resposta antes de continuar. Enquanto isso, o resto da página continua funcionando.

### 4. O que a Fetch API faz? Qual a diferença entre `fetch(url)` e `resposta.json()`?

A Fetch API serve para buscar informações de uma API. O `fetch(url)` faz a busca e o `resposta.json()` pega os dados recebidos e transforma para podermos usar no JavaScript.

### 5. Como podemos tratar um erro?

Podemos usar `try...catch` para pegar os erros. Também podemos verificar o `resposta.ok` para saber se a resposta da API deu certo.

