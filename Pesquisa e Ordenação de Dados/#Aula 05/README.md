# 📘 Aula 02 – Algoritmos de Ordenação

Nesta aula foram apresentados três algoritmos clássicos de ordenação:

- 🔵 Bubble Sort  
- 🟡 Selection Sort  
- 🔴 Insertion Sort  

Esses algoritmos são fundamentais no estudo de **Estruturas, Pesquisa e Ordenação de Dados**.

---

## 🎯 Metas de Aprendizagem

- Compreender a importância da ordenação
- Entender como funcionam algoritmos simples de ordenação
- Comparar eficiência entre eles
- Identificar qual utilizar dependendo do cenário

---

# 🔵 Bubble Sort

## 📌 Conceito

O **Bubble Sort** percorre a lista comparando elementos adjacentes e trocando-os de posição quando necessário.

A cada passagem, o maior valor “sobe” para o final da lista.

## ⚙ Funcionamento

1. Compara dois elementos vizinhos  
2. Se estiverem fora de ordem, troca  
3. Repete até que não existam mais trocas  

## 📊 Complexidade

- Melhor caso: **O(n)**
- Pior caso: **O(n²)**

## ✅ Vantagens

- Simples de entender
- Fácil de implementar

## ❌ Desvantagens

- Muito lento para grandes volumes de dados

---

# 🟡 Selection Sort

## 📌 Conceito

O **Selection Sort** seleciona o menor elemento da lista e o coloca na posição correta.

Ele divide a lista em duas partes:
- Parte ordenada
- Parte não ordenada

## ⚙ Funcionamento

1. Procura o menor valor
2. Troca com a primeira posição
3. Repete o processo para o restante da lista

## 📊 Complexidade

- Melhor caso: **O(n²)**
- Pior caso: **O(n²)**

## ✅ Vantagens

- Número reduzido de trocas
- Fácil implementação

## ❌ Desvantagens

- Sempre executa O(n²), mesmo se a lista já estiver quase ordenada

---

# 🔴 Insertion Sort

## 📌 Conceito

O **Insertion Sort** constrói a lista ordenada inserindo um elemento por vez na posição correta.

Muito eficiente para listas pequenas ou quase ordenadas.

## ⚙ Funcionamento

1. Considera o primeiro elemento como ordenado
2. Pega o próximo elemento
3. Insere na posição correta dentro da parte ordenada
4. Repete até o final

## 📊 Complexidade

- Melhor caso: **O(n)**
- Pior caso: **O(n²)**

## ✅ Vantagens

- Muito eficiente para listas pequenas
- Excelente quando os dados já estão quase ordenados
- Usado internamente em alguns sistemas híbridos

## ❌ Desvantagens

- Ineficiente para grandes volumes de dados

---

# 🃏 Aplicação em um Jogo de Cartas

Para um aplicativo de jogo de cartas, o **Insertion Sort** costuma ser o mais indicado, pois:

- A quantidade de cartas é pequena
- Muitas vezes as cartas já estão quase ordenadas
- Possui bom desempenho nesses cenários

---

## 📌 Conclusão

Os três algoritmos são importantes para compreender os fundamentos da ordenação.

Embora não sejam os mais eficientes para grandes sistemas, são essenciais para:

- Entender complexidade de algoritmos
- Desenvolver raciocínio lógico
- Base para algoritmos mais avançados

---

📚 Disciplina: Estruturas, Pesquisa e Ordenação de Dados  
🎓 Curso: Engenharia de Software