<div style="text-align: center;">
    <h1 style="color: red; font-size: 32px;">Desafio DIO</h1>
</div>

## Guia Básico de Funcionalidades do Markdown

Markdown é uma linguagem de marcação leve que permite formatar texto de maneira simples, sem a necessidade de usar HTML. Abaixo estão as funcionalidades básicas do Markdown com explicações sobre o que cada uma faz.

---

## 1. Títulos

Você pode criar títulos com diferentes níveis de hierarquia usando `#` no início da linha.

### Exemplo:

```markdown
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
#### Título de Nível 4
```

### Saída:
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
#### Título de Nível 4

---

## 2. Ênfase

Você pode usar asteriscos ou underscores para adicionar ênfase ao texto.

### Exemplo:

```markdown
*Itálico* ou _Itálico_

**Negrito** ou __Negrito__

***Itálico e Negrito*** ou ___Itálico e Negrito___
```

### Saída:
*Itálico* ou _Itálico_

**Negrito** ou __Negrito__

***Itálico e Negrito*** ou ___Itálico e Negrito___

---

## 3. Listas

### Listas não ordenadas
Para criar uma lista não ordenada, use `-`, `+` ou `*` antes de cada item.

### Exemplo:

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
* Item 3
+ Item 4
```

### Saída:
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
* Item 3
+ Item 4

### Listas ordenadas
Para listas ordenadas, basta usar números seguidos por um ponto.

### Exemplo:

```markdown
1. Primeiro item
2. Segundo item
3. Terceiro item
   1. Subitem 3.1
   2. Subitem 3.2
```

### Saída:
1. Primeiro item
2. Segundo item
3. Terceiro item
   1. Subitem 3.1
   2. Subitem 3.2

---

## 4. Links

Você pode adicionar links com o formato `[texto](URL)`.

### Exemplo:

```markdown
[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
```

### Saída:
[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

---

## 5. Imagens

Para adicionar imagens, use o formato `![texto alternativo](URL-da-imagem)`.

### Exemplo:

```markdown
![Logo do Markdown](https://markdown-here.com/img/icon256.png)
```

### Saída:
![Logo do Markdown](https://markdown-here.com/img/icon256.png)

---

## 6. Blocos de Código

Você pode incluir blocos de código com crases (\`).

### Exemplo para código inline:

```markdown
Use o comando `git status` para verificar o status do repositório.
```

### Saída:
Use o comando `git status` para verificar o status do repositório.

### Exemplo para blocos de código:

Para blocos de código, utilize três crases (\`\`\`) antes e depois do código.

```markdown
```
def hello_world():
    print("Hello, World!")
```
```

### Saída:

```
def hello_world():
    print("Hello, World!")
```

---

## 7. Citações (Blockquotes)

Use `>` para criar citações.

### Exemplo:

```markdown
> "O sucesso é ir de fracasso em fracasso sem perder o entusiasmo." – Winston Churchill
```

### Saída:
> "O sucesso é ir de fracasso em fracasso sem perder o entusiasmo." – Winston Churchill

---

## 8. Linhas Horizontais

Para adicionar uma linha horizontal, use três ou mais traços, asteriscos ou sublinhados.

### Exemplo:

```markdown
---
***
___
```

### Saída:

---
***
___

---

## 9. Tabelas

Você pode criar tabelas usando pipes (`|`) e traços (`-`).

### Exemplo:

```markdown
| Nome      | Idade | Cidade      |
|-----------|-------|-------------|
| Alice     | 30    | São Paulo   |
| Bob       | 25    | Rio de Janeiro |
| Charlie   | 35    | Belo Horizonte |
```

### Saída:

| Nome      | Idade | Cidade         |
|-----------|-------|----------------|
| Alice     | 30    | São Paulo      |
| Bob       | 25    | Rio de Janeiro |
| Charlie   | 35    | Belo Horizonte |

---

## 10. Listas de Tarefas

Você pode criar listas de tarefas com `- [ ]` para tarefas não concluídas e `- [x]` para tarefas concluídas.

### Exemplo:

```markdown
- [x] Comprar leite
- [ ] Ir à academia
- [x] Terminar o projeto
```

### Saída:
- [x] Comprar leite
- [ ] Ir à academia
- [x] Terminar o projeto

---

## 11. Links de Referência

Você pode usar referências para links em vez de inseri-los diretamente no texto.

### Exemplo:

```markdown
Este é um exemplo de [link de referência][1].

[1]: https://www.example.com
```

### Saída:
Este é um exemplo de [link de referência][1].

[1]: https://www.example.com

---

## 12. Escapando Caracteres

Para mostrar caracteres especiais como `*`, `_`, `#` sem formatá-los, use uma barra invertida (`\`).

### Exemplo:

```markdown
\*Este texto não será itálico\*
```

### Saída:
\*Este texto não será itálico\*

---

Essas são as funcionalidades básicas do Markdown, uma maneira simples de formatar textos sem complicações. Explore essas opções para criar conteúdos ricos e bem estruturados!
