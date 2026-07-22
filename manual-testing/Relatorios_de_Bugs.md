</> Markdown
# Relatório de Bugs

Projeto: E-commerce Demo Sauce Demo

Data: 20/07/2026

Responsável: Pâmela Sales Toledo Dias

--

## BUG-001

**Título**
Botão "Adicionar ao Carrinho" não adiciona o produto.

**Módulo**
Carrinho

**Severidade**
Alta

**Prioridade**
Alta

**Ambiente**
Google Chrome 138
Windows 11

### Passos para reproduzir

1. Acessar a página inicial.
2. Abrir um produto.
3. Clicar em **Adicionar ao Carrinho**.

### Resultado esperado

O produto deve ser adicionado ao carrinho e o contador deve ser atualizado.

### Resultado obtido

O botão é clicado, porém nenhum produto é adicionado ao carrinho.

### Evidência

`manual-testing/IMG_2002.jpeg`

---

## BUG-002

**Título**
Campo de e-mail aceita formato inválido.

**Módulo**
Cadastro

**Severidade**
Média

**Prioridade**
Média

### Passos para reproduzir

1. Abrir a tela de cadastro.
2. Digitar `teste@`.
3. Preencher os restantes campos.
4. Clicar em **Cadastrar**.

### Resultado esperado

O sistema deve informar que o e-mail é inválido.

### Resultado obtido

O cadastro é realizado normalmente.

### Evidência

`manual-testing/IMG_2001.jpeg`

---

## BUG-003

**Título**
Valor total do carrinho não atualiza ao alterar a quantidade.

**Módulo**
Carrinho

**Severidade**
Alta

**Prioridade**
Alta

### Passos para reproduzir

1. Adicionar um produto ao carrinho.
2. Alterar a quantidade de 1 para 3.

### Resultado esperado

O valor total deve ser recalculado automaticamente.

### Resultado obtido

A quantidade é alterada, mas o valor permanece o mesmo.

### Evidência

`manual-testing/IMG_2003.jpeg`
