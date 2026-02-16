# 🌳 Aula 03 — Árvores Binárias e Percursos

📚 Disciplina: Estruturas, Pesquisa e Ordenação de Dados  
🎓 Curso: Engenharia de Software  

---

## 🎯 Objetivos da Aula

- Compreender o funcionamento de árvores binárias.
- Entender os tipos de percursos (pré-ordem, em-ordem e pós-ordem).
- Aprender o processo de busca em árvores binárias.
- Compreender o conceito de árvores AVL.
- Entender a importância do balanceamento.

---

## 🌳 Árvore Binária

Uma árvore binária é uma estrutura de dados hierárica onde:

- Existe um **nó raiz**
- Cada nó pode ter no máximo:
  - 1 filho à esquerda
  - 1 filho à direita

Se a árvore não possuir nós, ela é considerada vazia.

---

## 🔎 Árvore Binária de Busca (ABB)

Na Árvore Binária de Busca existe uma regra fundamental:

- Valores menores que o nó → ficam à esquerda
- Valores maiores que o nó → ficam à direita

Essa regra permite que a busca seja mais eficiente do que em um vetor comum.

---

## 🔁 Percursos em Árvores

O percurso (ou caminhamento) é a forma como percorremos a árvore.

### 🔹 Pré-Ordem
Ordem:
1. Raiz
2. Subárvore esquerda
3. Subárvore direita

📌 Muito utilizado para reconstrução da árvore.

---

### 🔹 Em-Ordem
Ordem:
1. Subárvore esquerda
2. Raiz
3. Subárvore direita

⚠ Importante:  
Em uma Árvore Binária de Busca, o percurso em-ordem retorna os elementos ordenados.

---

### 🔹 Pós-Ordem
Ordem:
1. Subárvore esquerda
2. Subárvore direita
3. Raiz

📌 Utilizado quando precisamos processar as subárvores antes da raiz.

---

## ⚠ Árvore Não Balanceada

Quando os elementos são inseridos em ordem crescente ou decrescente, a árvore pode se transformar praticamente em uma lista encadeada.

Consequência:
- A busca passa de O(log n) para O(n)

Isso reduz a eficiência da estrutura.

---

## ⚖ Árvore Balanceada

Uma árvore é considerada balanceada quando:


Isso garante melhor desempenho na busca.

Complexidade:
- Busca → O(log n)

---

## 🌲 Árvores AVL

AVL é um tipo especial de Árvore Binária de Busca que:

- Se auto-balanceia
- Realiza rotações quando necessário
- Mantém a altura equilibrada

Objetivo:
Garantir que a árvore permaneça eficiente.

---

## 🚀 Conclusão

As árvores binárias são fundamentais para:

- Estruturas de busca
- Organização eficiente de dados
- Sistemas que exigem alta performance

O balanceamento é essencial para manter a eficiência da busca.

---

✍️ Autor: Israel Custódio dos Santos  


| Percurso  | Ordem                     | Quando usar             |
| --------- | ------------------------- | ----------------------- |
| Pré-ordem | Raiz → Esquerda → Direita | Criar cópia da árvore   |
| In-ordem  | Esquerda → Raiz → Direita | Obter valores ordenados |
| Pós-ordem | Esquerda → Direita → Raiz | Resolver dependências   |


