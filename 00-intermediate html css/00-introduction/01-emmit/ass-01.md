### 1. Basic Syntax Rules (Yeh sabse zaroori hain)

| Operator       | Matlab                          | Example                          | Result (Expanded) |
|----------------|---------------------------------|----------------------------------|-------------------|
| `>`            | Child (andar)                   | `nav>ul>li`                      | `<nav><ul><li></li></ul></nav>` |
| `+`            | Sibling (side mein)             | `div+p+bq`                       | `<div></div><p></p><blockquote></blockquote>` |
| `^`            | Climb-up (upar jaao)            | `div>p>span^div`                 | `<div><p><span></span></p></div><div></div>` |
| `()`           | Grouping (group banana)         | `(div>p)+footer`                 | `<div><p></p></div><footer></footer>` |
| `*`            | Multiplication (kitni baar)     | `ul>li*5`                        | 5 `<li>` ban jayenge |
| `$`            | Numbering (1,2,3...)            | `li.item$*3`                     | `item1`, `item2`, `item3` |
| `$$`           | Zero padded (01,02...)          | `li.item$$*3`                    | `item01`, `item02` |
| `{}`           | Text content                    | `p{Hello World}`                 | `<p>Hello World</p>` |
| `.`            | Class                           | `div.header`                     | `<div class="header"></div>` |
| `#`            | ID                              | `div#content`                    | `<div id="content"></div>` |

### 2. Important HTML Abbreviations

| Abbreviation          | Expanded HTML |
|-----------------------|---------------|
| `!` or `html:5`       | Full HTML5 boilerplate (`<!DOCTYPE html>` + `<html>` + `<head>` etc.) |
| `a`                   | `<a href=""> </a>` |
| `a:link`              | `<a href="http://"> </a>` |
| `img`                 | `<img src="" alt="">` |
| `link:css`            | `<link rel="stylesheet" href="style.css">` |
| `script:src`          | `<script src=""></script>` |
| `meta:vp`             | Viewport meta tag (mobile friendly) |
| `ul>li*5`             | 5 list items |
| `table>tr*3>td*3`     | 3x3 table |
| `form>input[type=text]` | Form with text input |

**Implicit Tags** (class ya id likho to automatically div ban jata hai):
- `.header` → `<div class="header"></div>`
- `#main` → `<div id="main"></div>`
- `ul>.item` → `<ul><li class="item"></li></ul>`

### 3. CSS Abbreviations (Properties short forms)

| Emmet     | CSS Property |
|-----------|--------------|
| `w100`    | `width: 100px;` |
| `h50`     | `height: 50px;` |
| `m20`     | `margin: 20px;` |
| `p10`     | `padding: 10px;` |
| `bd1`     | `border: 1px;` |
| `c#f00`   | `color: #f00;` |
| `bgc#fff` | `background-color: #fff;` |
| `fsz16`   | `font-size: 16px;` |
| `dib`     | `display: inline-block;` |
| `fl`      | `float: left;` |
| `posa`    | `position: absolute;` |
| `ai:c`    | `align-items: center;` |
| `jc:sb`   | `justify-content: space-between;` |

**Common CSS Examples**:
- `m:a` → `margin: auto;`
- `ta:c` → `text-align: center;`
- `fsb` → `font-style: bold;`