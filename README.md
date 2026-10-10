# Blog HTML - Semana 01

Projeto desenvolvido como entregável da Semana 01 da disciplina de Desenvolvimento Web.

## Objetivo

Construir a estrutura base de um blog utilizando HTML semântico e implementar um formulário de inscrição utilizando recursos nativos de validação do HTML5.

## Tecnologias utilizadas

- HTML5

## Funcionalidades

O projeto possui:

- cabeçalho com título e menu de navegação;
- estrutura semântica utilizando `header`, `nav`, `main`, `article`, `aside` e `footer`;
- dois artigos com título, texto e imagem;
- formulário de inscrição utilizando o método GET;
- campo de nome com mínimo de 3 caracteres;
- campo de e-mail com validação;
- campo de idade limitado entre 18 e 120 anos;
- seleção de assunto de interesse;
- aceite obrigatório dos termos;
- validações nativas do HTML5.

## Estrutura do projeto

```text
blog-html-semana-01/
│
├── index.html
└── README.md
```

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador.

Também é possível utilizar a extensão Live Server no Visual Studio Code.

## Teste do formulário

Como o formulário utiliza:

```html
method="get"
```

os dados preenchidos aparecem na URL após o envio.

Exemplo:

```text
?nome=Rafael&email=teste%40email.com&idade=18&assunto=html&termos=on
```

## Autor

Rafael Tajra
