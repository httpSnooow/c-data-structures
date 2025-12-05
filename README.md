# 🚀 Estruturas de Dados em C

> Um repositório de implementações "from scratch" (do zero), focando na lógica algorítmica pura e no gerenciamento manual de memória.

<div align="center">

  ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
  ![GCC](https://img.shields.io/badge/gcc-GNU-000000?style=for-the-badge&logo=gnu-bash&logoColor=white)
  ![Algorithms](https://img.shields.io/badge/algorithms-%232d3436.svg?style=for-the-badge&logo=codeforces&logoColor=white)

</div>

---

## 🎯 Objetivo do Repositório

Este projeto não se trata apenas de código, mas de **fundamentação teórica aplicada**. O objetivo é solidificar o entendimento de como os dados são organizados na memória, abrindo mão de bibliotecas prontas para implementar cada nó, ponteiro e alocação manualmente.

### 🧠 Competências Desenvolvidas
* **Gestão de Memória:** Uso extensivo de `malloc`, `free` e aritmética de ponteiros.
* **Complexidade Algorítmica:** Foco na eficiência das operações de busca, inserção e remoção.
* **Abstração:** Implementação de Tipos Abstratos de Dados (TADs).

---

## 📚 Estruturas Implementadas

### 1. 🔗 Estruturas Lineares
O alicerce da organização de dados sequenciais.

| Estrutura | Variações Implementadas |
| :--- | :--- |
| **Listas Encadeadas** | • Simplesmente Encadeada <br> • Duplamente Encadeada <br> • Circular <br> • Com Nó Cabeça (Sentinela) |
| **Pilhas (Stacks)** | Implementações baseadas em Vetores (Arrays) e Listas Dinâmicas. |
| **Filas (Queues)** | Implementações baseadas em Vetores e Listas. |

### 2. 🌳 Estruturas Não-Lineares (Árvores)
Implementações hierárquicas focadas em performance de busca.

* **BST (Binary Search Tree):** A base das árvores, com operações de inserção, remoção e travessia.
* **AVL Tree:** Árvore auto-balanceável.
    * *Aplicação Prática:* Projeto **Dicionário**, onde a AVL é usada para garantir buscas em tempo logarítmico $O(\log n)$.
* **Red-Black Tree:** Implementação complexa de árvore rubro-negra balanceada.

### 3. ⚡ Acesso Rápido & Grafos
Estruturas avançadas para mapeamento e relações.

* **#️⃣ Tabelas Hash:** Tratamento de colisões via *Endereçamento Aberto* e *Encadeamento*.
* **🕸️ Grafos:**
    * **Representação:** Matriz de Adjacência e Lista de Adjacência.
    * **Algoritmos:** Busca em Largura (BFS) e Busca em Profundidade (DFS).

---

## 🛠️ Tecnologias & Ferramentas

<div align="left">
  <img src="https://img.shields.io/badge/Linguagem-C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Compilador-GCC-gray?style=for-the-badge&logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/OS-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</div>

> **Por que C?**
> A escolha da linguagem C foi intencional para permitir o controle total sobre a memória e entender o custo computacional de cada abstração, algo que linguagens de alto nível muitas vezes escondem.
