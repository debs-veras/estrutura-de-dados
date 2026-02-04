# Estrutura de Dados

Este projeto contém implementações de diversas estruturas de dados em C, organizadas em bibliotecas e arquivos de implementação.

## Estrutura do Projeto

- **bibliotecas/**: Arquivos de cabeçalho (.h) das estruturas de dados.
- **implementações/**: Arquivos de implementação (.c) das estruturas de dados.

### Estruturas Disponíveis

- Árvore AVL
- Árvore Binária de Busca (BST)
- Árvore Rubro-Negra (Red-Black Tree)
- Lista
- Fila (Queue)
- Pilha (Stack)
- Pilha de Inteiros (StackInt)
- Grafos

## Como Utilizar

1. Inclua o arquivo de cabeçalho da estrutura desejada no seu código:
   ```c
   #include "bibliotecas/Stack.h"
   ```
2. Compile o arquivo de implementação correspondente junto ao seu projeto:
   ```sh
   gcc seu_programa.c implementações/Stack.c -o seu_programa
   ```

## Organização dos Arquivos

- Cada estrutura possui um arquivo de cabeçalho com as definições e protótipos das funções.
- As implementações das funções estão nos arquivos .c correspondentes.

## Contribuição

Sinta-se livre para sugerir melhorias ou adicionar novas estruturas de dados!
