# 💻 Desafio — Busca binaria

A busca binária é um algoritmo eficiente para encontrar um item em uma lista ordenada de elementos.

Diferente da busca linear (que verifica um por um), a busca binária funciona dividindo repetidamente pela metade a porção da lista que deve conter o item, até reduzir as localizações possíveis a apenas uma.

Como funciona (Passo a Passo)
Pré-requisito: A lista deve estar em ordem (crescente ou decrescente).

Meio: O algoritmo olha para o elemento exatamente no meio da lista.

Comparação: * Se o valor do meio for o que você procura, a busca termina.

Se o valor que você procura for menor que o do meio, a busca continua apenas na metade esquerda.

Se for maior, a busca continua apenas na metade direita.

Repetição: O processo se repete até encontrar o valor ou a lista se esgotar.

Exemplo Prático
Imagine que você quer encontrar o número 7 em uma lista de 1 a 10:
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

Chute Inicial: O meio da lista é o 5.

Comparação: 7 é maior que 5? Sim. Então, ignore tudo do 5 para baixo.

Nova lista: [6, 7, 8, 9, 10]

Novo Chute: O meio agora é o 8.

Comparação: 7 é menor que 8? Sim. Então, ignore do 8 para cima.

Nova lista: [6, 7]

Último Chute: O meio é o 7. Encontrado!

📘 **Instruções Gerais**

Resolva os exercícios abaixo **na linguagem que preferir** (C, Python, JavaScript, Java, etc).  
Você deve exibir o resultado de cada exercício **no console ou terminal**, usando o comando de saída da sua linguagem (ex: `print`, `console.log`, `printf`, `System.out.println`, etc).  

---

## 🧠 Exercício 1
Crie uma um algoritimo de busca binaria da seguinte lista [1,2,3,4,5,6,7,8,9,10,11,12]
Exiba quantos passos teve essa busca no console.

---

## 🧠 Exercício 2

Crie uma um algoritimo de busca binaria da seguinte lista [30,44,55,23,12,9,44,56,77,88,12,34]
obs:ordene a lista e mostre o resultado

---

### 💬 Dica
Crie um arquivo de código (ex: `main.py`, `app.c`, `script.js`, `Main.java`)  
e execute pelo terminal para testar seus resultados.  

Use comentários (`//`, `#`, ou `/* ... */`) para explicar cada parte do seu código!  
