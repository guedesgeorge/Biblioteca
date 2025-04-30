# 📚 Sistema de Gestão de Biblioteca

Bem-vindo ao projeto **Sistema de Gestão de Biblioteca**!  
Este projeto foi desenvolvido como parte de um desafio da trilha de Java do **Ignite**.  
O objetivo principal é aplicar conceitos fundamentais da linguagem Java, como:

- Herança
- Polimorfismo
- Estruturas de repetição
- Manipulação de datas

---

## 🔧 Funcionalidades

### 📖 Gerenciamento de Livros
- **Listar todos os livros disponíveis**  
  Exibe apenas os livros que estão disponíveis para empréstimo.

- **Realizar empréstimo de um livro**  
  Permite que um usuário escolha um livro disponível e registre o empréstimo.

---

## 🏗 Estrutura do Projeto

O projeto é dividido nas seguintes classes principais:

- **`Livro`**  
  Representa os livros da biblioteca, com atributos como:
  - `id`, `titulo`, `autor`, `disponivel`, `dataCadastro`, `dataAtualizacao`.

- **`Autor`**  
  Representa os autores dos livros, com atributos como:
  - `id`, `nome`, `dataNascimento`.

- **`Emprestimo`**  
  Gerencia os empréstimos de livros, incluindo:
  - Dados do livro emprestado, data de empréstimo e data de devolução.

- **`Biblioteca`**  
  Gerencia a coleção de livros, autores e empréstimos disponíveis.

---

## 💻 Requisitos

- Java Development Kit (JDK) 8 ou superior
- IDE de sua preferência:  
  (Eclipse, IntelliJ IDEA, NetBeans, etc.)

---

## ▶️ Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-biblioteca.git
