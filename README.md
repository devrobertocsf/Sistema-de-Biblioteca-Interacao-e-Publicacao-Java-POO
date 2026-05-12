---

# 📚 Sistema de Biblioteca - Interação e Publicação (Java POO)

Este repositório contém um sistema de simulação de leitura desenvolvido para aprofundar o conhecimento em **Agregação** e **Interfaces** em Java. O projeto modela a relação entre leitores e livros, controlando o progresso da leitura através de um contrato de métodos bem definido.

## 🚀 Conceitos Chave Explorados

Este projeto consolida a base necessária para o desenvolvimento de sistemas complexos, utilizando:

* **Interfaces**: Implementação da interface `Publicacao`, que estabelece os comportamentos padrão para qualquer obra literária.
* **Agregação (Has-a)**: A classe `Livro` possui um atributo do tipo `Pessoa`, demonstrando como objetos independentes se associam para formar uma funcionalidade completa.
* **Encapsulamento**: Uso rigoroso de modificadores de acesso `private` para proteger o estado do livro (página atual, se está aberto, etc.).
* **Sobrescrita de Métodos (@Override)**: Implementação personalizada dos métodos da interface para controlar a navegação nas páginas.

## 🛠️ Funcionalidades e Regras

O sistema permite realizar as seguintes ações de forma segura:

* **Abrir e Fechar**: Altera o estado de disponibilidade do livro para leitura.
* **Folhear**: Permite saltar para uma página específica, com validação para não ultrapassar o total de páginas do livro.
* **Avançar/Voltar Página**: Navegação sequencial que altera o atributo `pagAtual`.
* **Detalhes**: Um método que gera um resumo textual completo do estado do livro e quem o está lendo no momento.

## 📂 Estrutura do Repositório

* `Publicacao.java`: Interface com as assinaturas dos métodos de controle de leitura.
* `Pessoa.java`: Classe que define o leitor (Nome, Idade, Sexo).
* `Livro.java`: Classe principal que agrega o leitor e implementa as lógicas de publicação.
* `Principal.java`: Classe de execução que utiliza arrays de objetos para gerenciar múltiplos leitores e obras simultaneamente.

## 💻 Exemplo de Saída (Status do Objeto)

```text
Livro [titulo=Aprendendo Java, 
autor=José da Silva, 
totPaginas=300, 
pagAtual=250, 
aberto=true, 
leitor=Pedro]

```

---

*Projeto desenvolvido por Roberto Carlos, graduando em Ciência da Computação, como parte do portfólio de estudos em Java.*

---

