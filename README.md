# 1. Trabalhando com títulos

input:

```markdown
# Título 1
```

output:

# Título 1

---

input:

```markdown
## Título 2
```

output:

## Título 2

---

input:

```markdown
### Título 3
```

output:

### Título 3

---

input:

```markdown
#### Título 4
```

output:

#### Título 4

---

input:

```markdown
##### Título 5
```

output:

##### Título 5

---

input:

```markdown
####### Título 6
```

output:

###### Título 6

---

# 2. Trabalhando com parágrafos
O parágrafo não precisa de uma tag específica para utilizá-lo. Basta escrever normalmente que ele já é identificado como um parágrafo. Para quebrar linha, basta que você dê 2 espaços ao final de um parágrafo anterior. Para pular linha e dar um espaço maior, basta que você deixe uma linha em branco entre os parágrafos.  
Parágrafo após 2 espaços ao final do anterior.

Parágrafo após uma linha em branco do anterior. 

# 3. Trabalhando com ênfase

### 3.1 Texto em negrito

input:

```markdown
**texto em negrito**
```

output:

**texto em negrito**  

### 3.2 Texto em itálico

input:

```markdown
*texto em itálico*
```

output:

*texto em itálico*

### 3.3 Texto em negrito e itálico

input:

```markdown
***Texto em negrito e itálico***
```

output:

***Texto negrito e itálico***

### 3.4 Texto riscado

input:

```markdown
~~texto riscado~~
```

output:

~~texto riscado~~

### 3.5 Bloco de citação

input:

```markdown
  > Aqui vem uma citação
```

output:

> Aqui vem uma citação

### 3.6 Citação com negrito e itálico

input:

```markdown
  > Citação com **negrito** e *itálico*
```

output:

> Citação com **negrito** e *itálico*

### 3.7 Linha horizontal

input:

```markdown
  ---
```

output:

---

# 4. Listas ordenadas e não-ordenadas

### 4.1 Lista não-ordenada

input:

```markdown
  * Item 1
  * Item 2
  * Item 3
```

output:

* Item 1
* Item 2
* Item 3

### 4.2 Subitem em um lista não-ordenada

input:

```markdown
  * Item 1
    * Subitem 1
    * Subitem 2
  * Item 2
  * Item 3
```

output:

* Item 1
  * Subitem 1
  * Subitem 2
* Item 2
* Item 3

## 4.3 Lista ordenada

input:

```markdown
  1. Item 1
  2. Item 2
  3. Item 3
```

output:

1. Item 1
2. Item 2
3. Item 3

## 4.4 Subitem em uma lista ordenada

input:

```markdown
1. Item 1
  1.1 Subitem 1
  1.2 Subitem 2
2. Item 2
3. Item 3
```

output:

1. Item 1  
  1.1 Subitem 1  
  1.2 Subitem 2  
2. Item 2
3. Item 3

## 4.5 Lista ordenada (customizada)

input:

```markdown
1\. Item 1
1\. Item 2
1\. Item 3
```

output:

1\. Item 1
1\. Item 2
1\. Item 3

# 5. Trabalhando com links

input:

```markdown
[Link aqui](https://github.com/carlozfilipe "Github de Carlos Filipe")
```

output:

[Link aqui](https://github.com/carlozfilipe "Github de Carlos Filipe")

# 6. Trabalhando com imagens

### 6.1 Imagem sem link

input:

```markdown
![Imagem](https://randomuser.me/api/portraits/lego/8.jpg)
```

output:

![Imagem](https://randomuser.me/api/portraits/lego/8.jpg)

### 6.2 Imagem com link

input:

```markdown
  [![Imagem](https://randomuser.me/api/portraits/lego/8.jpg)](https://randomuser.me/api/portraits/lego/8.jpg "Imagem de um lego")
```

output:

[![Imagem](https://randomuser.me/api/portraits/lego/8.jpg)](https://randomuser.me/api/portraits/lego/8.jpg "Imagem de um lego")

# 7. Trabalhando com tabelas

input:

```markdown
| Nome | Idade | Profissão |
| :---:  |  :---:  |    :---:    |
| Carlos | 26  | Desenvolvedor  |
| Filipe | 30 | DevOps | 
```

output:

| Nome | Idade | Profissão |
| :---:  |  :---:  |    :---:    |
| Carlos | 26  | Desenvolvedor  |
| Filipe | 30 | DevOps | 

# 8. Trabalhando com códigos

input:

Abaixo temos uma função chamada `sum` que soma dois números.

    ```js
      // Função que soma dois números
      const sum = (x, y) => {
        return x + y;
      }
      console.log(`A soma é ${sum(10, 20)}.`);
    ```

output:

Abaixo temos uma função chamada `sum` que soma dois números.

```js
// Função que soma dois números
const sum = (x, y) => {
  return x + y;
}
console.log(`A soma é ${sum(10, 20)}.`);
```

# 9. Trabalhando com emojis e checkbox

### 9.1 Emojis

input:

```markdown
:smile: :snowflake: :ghost: :rocket: :sos: :br:
```

output:

:smile: :snowflake: :ghost: :rocket: :sos: :brazil:

### 9.2 Checkbox

input:

```markdown
* [x] Item 1
* [] Item 2
```

output:

* [x] Item 1
* [ ] Item 1

<br>

Por enquanto é isso! :smile:
