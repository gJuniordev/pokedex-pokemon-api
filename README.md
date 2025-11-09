# 📖 Pokedex Interativa com PokeAPI

[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)](https://github.com/gJuniordev/pokedex-pokemon-api)
[![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20CSS%20%7C%20JavaScript-blue)](https://developer.mozilla.org/pt-BR/docs/Web)
[![API](https://img.shields.io/badge/API-Pok%C3%A9API-red)](https://pokeapi.co/)

Uma Pokedex dinâmica e interativa desenvolvida com **HTML, CSS e JavaScript puro**, consumindo dados da **PokeAPI**. Este projeto foca em boas práticas de programação assíncrona, manipulação do DOM e design responsivo.

---

## ✨ Funcionalidades

* **Listagem de Pokémon:** Exibe uma lista dos Pokémon com seus nomes, números e tipos.
* **Design Responsivo:** O layout se adapta a diferentes tamanhos de tela (mobile e desktop) usando **Media Queries**.
* **Cores por Tipo:** O fundo de cada card de Pokémon muda de cor de acordo com seu **tipo principal** (ex: `fire`, `water`, `grass`), facilitando a identificação.
* **"Load More" (Paginação):** Carrega mais Pokémon sob demanda (10 por vez), utilizando o parâmetro `offset` da API, otimizando a performance inicial.
* **Consumo de API Eficiente:** Utiliza `fetch` e `Promise.all` para buscar os detalhes de múltiplos Pokémon de forma assíncrona e rápida na PokeAPI.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura básica da Pokedex.
* **CSS3 (Global e Pokedex):** Estilização, definição das cores de tipos e layout responsivo.
* **JavaScript (ES6+):** Lógica principal, manipulação do DOM e a camada de serviço (`poke-api.js`).
* **[PokeAPI](https://pokeapi.co/):** API RESTful que fornece os dados dos Pokémon.

---

## 🚀 Como Executar o Projeto

Para visualizar a Pokedex em seu ambiente local, siga estas etapas:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/gJuniordev/pokedex-pokemon-api.git](https://github.com/gJuniordev/pokedex-pokemon-api.git)
    ```
2.  **Navegue até o Diretório:**
    ```bash
    cd pokedex-pokemon-api
    ```
3.  **Abra no Navegador:**
    * Simplesmente abra o arquivo **`index.html`** em seu navegador favorito.
    * Como o projeto usa apenas arquivos estáticos (HTML, CSS e JS) e `fetch` para a API, não é necessário um servidor local.

---
## 📸 Preview

<img width="1095" height="667" alt="image" src="https://github.com/user-attachments/assets/a5d46128-b47b-437b-8d61-a26df552a3b1" />

## 🎓 Contexto Educacional
Este projeto foi desenvolvido como parte da **Formação CSS Web Developer** da [DIO.me](https://www.dio.me), com o objetivo de praticar:

## 👨‍💻 Autor
**Gilcélio Júnior - Juntamente a DIO.ME**
- 💼 [LinkedIn](https://www.linkedin.com/in/gilc%C3%A9lio-j%C3%BAnior-ab032924a/)
- 🐙 [GitHub](https://github.com/gJuniordev)

<div align="center">
Desenvolvido com 💙 por [Gilcélio Júnior] como projeto da [DIO.me](https://www.dio.me)
</div>
