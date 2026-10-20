# Sistema de Biblioteca em C

Aplicação em linguagem C desenvolvida via linha de comando (CLI) para gerenciamento básico de acervo bibliotecário e controle de empréstimos.

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com foco no aprendizado prático de estruturas de dados e manipulação de memória em C. A lógica de controle, fluxo de menu, gerenciamento de registros e regras de negócio foram implementados de forma autoral, recorrendo a ferramentas externas apenas para consultas pontuais de documentação e sintaxe da linguagem.

---

## ⚙️ Funcionalidades

- **Cadastro de Livros:** Registro de obras contendo título, autor e editora, com tratamento de buffer e quebra de linha (`fgets` e `strcspn`).
- **Listagem de Livros:** Exibição do acervo cadastrado.
- **Controle de Empréstimos:** Rotina para realizar empréstimo e acompanhar o status dos títulos.
- **Interface via Terminal:** Menu interativo estruturado em loop de execução.

---

## 🛠️ Tecnologias e Conceitos Utilizados

- **Linguagem C**
- **Estruturas de Dados (`struct`):** Modelagem de dados para livros e registros.
- **Ponteiros e Passagem por Referência:** Manipulação eficiente de arrays e contadores de controle.
- **Manipulação de Strings:** Sanitização de entradas com funções padrão da biblioteca `<string.h>`.

---

## 🚀 Como Compilar e Executar

### Pré-requisitos
- Compilador C instalado (`gcc` ou `clang`).

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Jonathanmkv/Sistema-biblioteca.git](https://github.com/Jonathanmkv/Sistema-biblioteca.git)
   cd Sistema-biblioteca