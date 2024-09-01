

# 📚 Gerenciador de Fila Circular em C

Este repositório contém um programa em C que implementa uma fila circular usando um array fixo. A fila circular é uma estrutura de dados que permite adicionar e remover elementos de forma eficiente, "circulando" entre o início e o fim do array. Abaixo estão descritas as funcionalidades e o uso do código.

## 🚀 Funcionalidades

- **Enfileirar**: Adiciona um elemento no final da fila.
- **Desenfileirar**: Remove um elemento do início da fila.
- **Imprimir**: Exibe todos os elementos da fila.

## 🔧 Definições

- **MAX**: Tamanho máximo da fila (definido como 5).
- **FALSE**: Representa o valor lógico falso.
- **TRUE**: Representa o valor lógico verdadeiro.

## 📜 Funções

### `filaCheia()`
Verifica se a fila está cheia.
- **Retorno**: `TRUE` se a fila estiver cheia, `FALSE` caso contrário.

### `filaVazia()`
Verifica se a fila está vazia.
- **Retorno**: `TRUE` se a fila estiver vazia, `FALSE` caso contrário.

### `enfileirar(int valor)`
Adiciona um elemento ao final da fila.
- **Parâmetro**: `valor` - O valor a ser adicionado.
- **Retorno**: `TRUE` se a operação for bem-sucedida, `FALSE` se a fila estiver cheia.

### `desenfileirar(int *valor)`
Remove um elemento do início da fila e o armazena na variável fornecida.
- **Parâmetro**: `valor` - Ponteiro para armazenar o valor removido.
- **Retorno**: `TRUE` se a operação for bem-sucedida, `FALSE` se a fila estiver vazia.

### `imprimirFila()`
Imprime todos os elementos da fila.
- **Retorno**: Nenhum.


