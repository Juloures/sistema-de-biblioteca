📚 Sistema de Biblioteca em Python (Tkinter + SQLite)

Este projeto é um sistema simples de gerenciamento de biblioteca, feito em Python, utilizando Tkinter para a interface gráfica e SQLite como banco de dados.
Permite cadastrar autores, livros, empréstimos e visualizar tudo pela interface.

🚀 Funcionalidades

Cadastro de autores com nome e nacionalidade

Cadastro de livros com título, autor, ano e gênero

Cadastro de empréstimos com data de empréstimo, devolução e usuário

Listagem completa de autores, livros e empréstimos

Detecção de empréstimos atrasados

Interface gráfica em Tkinter

Banco de dados SQLite criado automaticamente

🛠 Tecnologias utilizadas

Python 3

Tkinter (interface gráfica)

SQLite3 (banco de dados local)

📂 Estrutura do Banco

O banco biblioteca.db cria automaticamente as tabelas:

Autores

Livros

Emprestimos

Com relacionamento via chave estrangeira.

▶ Como executar

Instale o Python 3.

Baixe o arquivo do projeto.

Execute no terminal:

python biblioteca.py


Importante: Tkinter só funciona em ambiente com interface gráfica.
Se estiver usando Jupyter, Colab ou servidor remoto, a interface não abrirá.

📌 Observação

O sistema ativa PRAGMA foreign_keys = ON para garantir integridade nos relacionamentos.
Certifique-se de preencher IDs corretamente ao cadastrar livros e empréstimos.
