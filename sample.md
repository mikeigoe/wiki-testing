# Markdown Cheatsheet

## Headings

Headings are preceeded by one or more `#` characters followed by a `space`.

> | HTML | Markdown|
> |------|---------|
> |`<h1>Heading 1</h1>`|`# Heading 1`|
> |`<h2>Heading 2</h2>`|`## Heading 2`|
> |`<h3>Heading 3</h3>`|`### Heading 3`|
> |`<h4>Heading 4</h4>`|`#### Heading 4`|
> |`<h5>Heading 5</h5>`|`##### Heading 5`|
> |`<h6>Heading 6</h6>`|`###### Heading 6`|



## Text Emphasis
### Italic
Text can be given an _italic_ emphasis by adding `*` or `_` at the start and finish of the required segment of text.

> `I want the following words *to be in italics* but not these ones`

I want the following words *to be in italics* but not these ones

> `I want the following words _to be in italics_ but not these ones`

I want the following _words to be in italics_ but not these ones

### Strong
Text can be given a **Strong**  emphasis by adding `**` or `__` at the start and finish of the required segment of text.

> `I want the following words **to be strong** but not these ones`

I want the following words **to be strong** but not these ones

> `I want the following words __to be strong__ but not these ones`

I want the following words __to be strong__ but not these ones.

### Strikethrough
Text can be given a ~~Strikethrough~~  emphasis by adding `~~` at the start and finish of the required segment of text.

> `I want the following words ~~to be strikethrough~~ but not these ones`

I want the following words ~~to be strikethrough~~ but not these ones

<!-- Escape -->

\* \~ \_

<!-- Horizontal Rule -->

---
___

<!-- Blockquotes -->

> This is a block quote

<!-- links -->

[Link Text](https://www.google.ie/)

[Link Text Alternative Mouse over](https://www.google.ie/ "Bing")

<!-- UL -->

* Item 1
  * Nested Item 1
    * More nesting
* Item 2

<!-- OL -->

1. Item 1
1. Item 1 
1. Item 2

<!-- Codeblocks -->

`<p>This is a paragraph</p>`

<!-- Images -->

![Markdown Logo](https://markdown-here.com/img/icon256.png)

___

# Github Markdown
## Code blocks

Code blocks can be created by

Bash

```bash
  npm install

  npm start
```

C#
```csharp
  public int Add(int x, int y)
  {
    return x + y;
  }
```

Javacsript
```javascript
  function Sum(x, y) {
    return x + y;
  };
```
Python
```python
  def Sum(x, y):
    return x + y
```
SQL
```sql
  -- Note
  CREATE TABLE names (
    id int NOT NULL AUTO_INCREMENT,
    name varchar(40) NULL,
    PRIMARY KEY (id)
  )
```


## Tables

| Name      | Email              |
|-----------|--------------------|
|Joe Bloggs | mikeigoe@gmail.com |
|Mike Igoe  | mikeigoe@gmail.com |

## Task Lists

* [X] Completed Task 1
+ [X] Completed Task 2
* [] Uncompleted Task 3

## Mention another user
use the @name