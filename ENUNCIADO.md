# Atividade Avaliativa em Dupla — Página de Evento

## Objetivo

Em dupla, vocês deverão desenvolver uma página web para divulgar um evento fictício, utilizando **HTML** e **CSS externo**.

A atividade deve aplicar os conteúdos vistos até agora em aula, principalmente:

- estrutura básica do HTML;
- tags semânticas;
- títulos e parágrafos;
- listas;
- links internos;
- imagens;
- tabelas;
- formulários;
- containers;
- box model;
- `margin`, `padding`, `border` e `background-color`.

---

## Tema

A dupla pode escolher o tema do evento. Alguns exemplos:

- feira de tecnologia;
- festival de games;
- mostra cultural;
- workshop;
- campeonato;
- feira de profissões;
- evento musical;
- evento criado pela própria dupla.

---

## Arquivos do projeto

O projeto já possui uma estrutura inicial com:

```txt
index.html
style.css
img/evento-tecnologia.png
```

A dupla deve editar os arquivos existentes, completando o conteúdo e a estilização.

---

## Requisitos obrigatórios

A página deve conter:

### 1. Cabeçalho

O cabeçalho deve ter:

- nome do evento;
- uma frase curta de apresentação;
- menu com links internos para as seções da página.

---

### 2. Seção “Sobre o evento”

Essa seção deve ter:

- título;
- texto explicando o evento;
- imagem com atributo `alt`;
- lista com pelo menos 4 informações importantes.

Exemplos de informações:

- data;
- horário;
- local;
- público-alvo;
- entrada gratuita ou paga.

---

### 3. Seção de atividades

A página deve ter pelo menos **2 cards de atividades**, usando a tag `article`.

Cada card deve conter:

- nome da atividade;
- descrição;
- horário.

---

### 4. Tabela de programação

A página deve ter uma tabela com a programação do evento.

A tabela deve conter:

- cabeçalho com `th`;
- pelo menos 3 linhas de programação;
- colunas de horário, atividade e local.

---

### 5. Formulário de inscrição

O formulário deve conter:

- campo de nome;
- campo de e-mail;
- campo de turma;
- campo de seleção com `select`;
- campo de mensagem com `textarea`;
- checkbox de confirmação;
- botão de envio.

Todos os campos devem ter `label`.

---

### 6. Rodapé

O rodapé deve conter:

- nome da dupla com RM;
- turma;
- disciplina.

---

## Tags semânticas obrigatórias

A página deve usar:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

---

## Regras importantes

Não é permitido usar:

```css
display: flex;
display: grid;
```

Também não é permitido usar:

- Bootstrap;
- Tailwind;
- bibliotecas prontas;
- templates prontos copiados da internet.

A proposta é praticar os conteúdos vistos em aula.

---

## Entrega

A atividade deve ser entregue em dupla até **domingo, às 23h59**.

A dupla deve entregar o projeto completo e zipado, mantendo os arquivos:

```txt
index.html
style.css
img/
```

