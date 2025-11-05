# 🏅 Projeto Notas dos Atletas

Aplicação desenvolvida em **JavaScript** como parte da **Jornada DEV SENAI**, um programa de capacitação em Desenvolvimento Front-End promovido pelo SENAI-RN.

---

## 🧭 Introdução

O SENAI-RN lançou a “Jornada DEV SENAI”, um programa de capacitação 100% online e gratuito voltado para a formação de novos talentos em Desenvolvimento Front-End.

Com 300 horas de conteúdo prático e teórico, o programa tem como objetivo preparar os alunos para o mercado de tecnologia. Este projeto faz parte das atividades práticas da Jornada, integrando os conceitos de lógica de programação e JavaScript básico.

---

## 💡 Descrição do Projeto

O projeto visa criar uma aplicação em **JavaScript puro** capaz de:

1.  Receber o nome e as notas de vários atletas.
2.  **Calcular a média válida** das notas, descartando a maior e a menor.
3.  Exibir os resultados formatados no console.

A aplicação simula a avaliação de uma competição de ginástica artística, onde a média final é calculada com base apenas nas três notas do meio, garantindo uma avaliação mais justa.

### Critérios de Avaliação (5 Notas de 1 a 10)

* Tempo de duração da apresentação
* Originalidade da coreografia
* Postura do atleta
* Dificuldade das acrobacias
* Sincronismo

---

## 🧠 Regras de Cálculo

* Cada atleta recebe 5 notas (entre 1 e 10).
* A **maior** e a **menor** nota são **descartadas**.
* A média é calculada com as **3 notas restantes**.
* O resultado é apresentado com **seis casas decimais**.

---

## 🧩 Estrutura da Entrada

A aplicação utiliza a seguinte matriz de objetos:

```javascript
let atletas = [
  {
    nome: "Cesar Abascal",
    notas: [10, 9.34, 8.42, 10, 7.88]
  },
  {
    nome: "Fernando Puntel",
    notas: [8, 10, 10, 7, 9.33]
  },
  {
    nome: "Daiane Jelinsky",
    notas: [7, 10, 9.5, 9.5, 8]
  },
  {
    nome: "Bruno Castro",
    notas: [10, 10, 10, 9, 9.5]
  }
];
```
---

## ⚙️ Lógica da Solução

O código implementa a seguinte sequência lógica:

1. Percorre a lista de atletas com um laço `for.

2. Ordena as notas em ordem crescente usando `.sort()`.

3. Remove a maior e menor nota com `.slice(1, 4)`.

4. Calcula a média das três notas do meio com `.forEach()`.

5. Exibe o nome, as notas obtidas e a média válida no console.

---

## ✨ Aprendizados

* Manipulação de arrays e objetos.

* Uso de métodos nativos (`sort`, `slice`, `forEach`, `join`).

* Estruturas de repetição (`for`).

* Cálculo de médias e formatação de números.

* Exibição estruturada de dados no console.

---

## 📜 Licença

Este projeto é de uso educacional e foi desenvolvido como parte da Jornada DEV SENAI-RN. Você pode utilizar o código livremente para fins de estudo e aprendizado.