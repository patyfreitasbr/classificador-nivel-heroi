# Classificador de Nível de Herói

[Sobre](#sobre) • [Descrição](#descricao) • [Tecnologias Utilizadas](#tecnologias-utilizadas) • [Objetivo](#objetivo) • [Funcionalidade](#funcionalidades) • [Como  Usar](#como-usar) • [Estrutura do projeto](#-estrutura-do-projeto)• [Exemplo de código](#-exemplo-de-código) • [Referências](#referências) • [Contato](#contato)


## Sobre 

Este projeto é um  **Classificador de Nível de Herói** desenvolvido em JavaScript. Ele utiliza variáveis, operadores, laços de repetição e estruturas de decisão para classificar um herói em diferentes níveis de acordo com sua quantidade de experiência (XP).

## 📝 Descrição

O projeto classifica um herói em diferentes níveis com base no valor de sua experiência (XP) e exibe uma mensagem com o nome do herói e o nível correspondente. É um exercício prático para quem está aprendendo JavaScript e deseja se familiarizar com estruturas de controle e manipulação de variáveis.

## 🛠️ Tecnologias Utilizadas
- HTML
- JavaScript

## 🎯 Objetivo

O objetivo é praticar o uso de:
- Variáveis
- Operadores
- Estruturas de decisão (`if...else if...else`)
- Saída de dados no console

## ⚙️ Funcionalidades

O programa classifica o herói com base nos seguintes níveis de experiência:

- **XP < 1000**: Nível **Ferro**
- **XP entre 1001 e 2000**: Nível **Bronze**
- **XP entre 2001 e 5000**: Nível **Prata**
- **XP entre 5001 e 7000**: Nível **Ouro**
- **XP entre 7001 e 8000**: Nível **Platina**
- **XP entre 8001 e 9000**: Nível **Ascendente**
- **XP entre 9001 e 10000**: Nível **Imortal**
- **XP >= 10001**: Nível **Radiante**

## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/classificador-nivel-heroi.git

2. Navegue até a pasta do projeto:

   ```bash
   cd classificador-nivel-heroi

3. Abra o arquivo `heroi.html` em um navegador para ver o  no console (F12).

4. Para alterar o nome e a quantidade de experiência (XP) do herói, edite o arquivo `nivelHeroi.js`.

## 📂 Estrutura do Projeto

heroi.html: Página HTML principal do projeto, que carrega o script JavaScript.
nivelHeroi.js: Script JavaScript que contém a lógica de classificação de nível do herói.

## 📜 Exemplo de Código

Abaixo está um exemplo de como a classificação de nível é feita em JavaScript:

```
let nomeHeroi = "Viking";
let xpHeroi = 9001;
let nivelHeroi;

if (xpHeroi < 1000) {
    nivelHeroi = "Ferro";
} else if (xpHeroi >= 1001 && xpHeroi <= 2000) {
    nivelHeroi = "Bronze";
} else if (xpHeroi >= 2001 && xpHeroi <= 5000) {
    nivelHeroi = "Prata";
} else if (xpHeroi >= 5001 && xpHeroi <= 7000) {
    nivelHeroi = "Ouro";
} else if (xpHeroi >= 7001 && xpHeroi <= 8000) {
    nivelHeroi = "Platina";
} else if (xpHeroi >= 8001 && xpHeroi <= 9000) {
    nivelHeroi = "Ascendente";
} else if (xpHeroi >= 9001 && xpHeroi <= 10000) {
    nivelHeroi = "Imortal";
} else if (xpHeroi >= 10001) {
    nivelHeroi = "Radiante";
}

console.log(`O Herói de nome ${nomeHeroi} está no nível de ${nivelHeroi}`);

```

## 📌 Referências

Este projeto foi desenvolvido como parte do desafio do Bootcamp "R iHappy - Front-end do zero" da [Dio - Digital Innovation One]( https://www.dio.me/sign-up?ref=2772EA2C589E462BB0C382518E0ACBA2), 

Se você achou esse projeto interessante, sinta-se à vontade para dar uma ⭐ no repositório!
</br>

## Contato

👩‍💻 Patrícia Freitas

📬 brpatyfreitas@gmail.com

 <div><a href="https://www.linkedin.com/in/patyfreitasbr"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></>
  <a href="https://www.instagram.com/patyfreitasbr"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></></div>

  <br>

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/patyfreitasbr/Google-Search-Page-Clone/blob/main/LICENSE)
