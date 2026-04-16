
### CSS Cheat Sheet (Simple & Easy)

| Category          | Property                  | Common Values                                      | Description (Simple) |
|-------------------|---------------------------|----------------------------------------------------|----------------------|
| **Layout & Positioning** | `display`                | `block`, `inline`, `inline-block`, `flex`, `grid`, `none` | Element ka display type set karta hai |
|                   | `position`               | `static`, `relative`, `absolute`, `fixed`, `sticky` | Positioning method define karta hai |
|                   | `top` / `right` / `bottom` / `left` | `px`, `%`, `auto`                                 | Positioned element ki location |
|                   | `z-index`                | `1`, `10`, `-1` etc.                               | Stack order (upar-neeche) |
|                   | `overflow`               | `visible`, `hidden`, `scroll`, `auto`              | Overflow content kaise handle ho |
|                   | `float`                  | `left`, `right`, `none`                            | Element ko left/right float karna |
|                   | `clear`                  | `left`, `right`, `both`                            | Float ke baad clear karna |
| **Box Model**     | `width` / `height`       | `px`, `%`, `auto`, `fit-content`                   | Element ki width aur height |
|                   | `min-width` / `max-width` | `px`, `%`                                         | Minimum/Maximum width |
|                   | `margin`                 | `px`, `%`, `auto` (shorthand: top right bottom left) | Bahar ki spacing |
|                   | `padding`                | `px`, `%` (shorthand)                              | Andar ki spacing |
|                   | `border`                 | `width style color` (e.g. `1px solid black`)      | Border add karna |
|                   | `border-radius`          | `px`, `%`                                          | Corners round karna |
|                   | `box-shadow`             | `offset-x offset-y blur spread color`              | Shadow daalna |
|                   | `box-sizing`             | `content-box`, `border-box`                        | Width/height calculation ka tarika |
| **Text & Font**   | `color`                  | `red`, `#ff0000`, `rgb(255,0,0)`                   | Text ka color |
|                   | `font-family`            | `Arial`, `Helvetica`, `sans-serif`                 | Font choose karna |
|                   | `font-size`              | `16px`, `1rem`, `1em`                              | Text ka size |
|                   | `font-weight`            | `normal`, `bold`, `700`                            | Text bold ya light |
|                   | `font-style`             | `normal`, `italic`                                 | Italic text |
|                   | `text-align`             | `left`, `center`, `right`, `justify`               | Text alignment |
|                   | `line-height`            | `1.5`, `20px`                                      | Lines ke beech distance |
|                   | `text-decoration`        | `none`, `underline`, `line-through`                | Underline, strikethrough etc. |
| **Background**    | `background-color`       | `color`, `transparent`                             | Background color |
|                   | `background-image`       | `url('image.jpg')`                                 | Background mein image |
|                   | `background-size`        | `cover`, `contain`, `100%`                         | Background image ka size |
|                   | `background-position`    | `center`, `top left`                               | Image ki position |
|                   | `background-repeat`      | `no-repeat`, `repeat`, `repeat-x`                  | Image repeat na ho |
| **Flexbox**       | `display: flex`          | -                                                  | Flex container banana |
|                   | `flex-direction`         | `row`, `column`, `row-reverse`                     | Items ki direction |
|                   | `justify-content`        | `center`, `space-between`, `flex-start`            | Main axis pe alignment |
|                   | `align-items`            | `center`, `stretch`, `flex-start`                  | Cross axis pe alignment |
|                   | `flex-wrap`              | `wrap`, `nowrap`                                   | Items wrap ho ya na ho |
|                   | `flex`                   | `1`, `0 1 auto`                                    | Grow, shrink, basis shorthand |
| **Grid**          | `display: grid`          | -                                                  | Grid container |
|                   | `grid-template-columns`  | `repeat(3, 1fr)`, `200px auto`                     | Columns define karna |
|                   | `grid-template-rows`     | `repeat(2, 100px)`                                 | Rows define karna |
|                   | `gap` / `grid-gap`       | `20px`, `1rem`                                     | Cells ke beech space |
|                   | `grid-column`            | `span 2`, `1 / 3`                                  | Item ko kitne columns mein rakhna |
| **Others (Common)** | `cursor`               | `pointer`, `default`, `move`                       | Mouse cursor change |
|                   | `opacity`                | `1`, `0.5`, `0`                                    | Transparency (0 = invisible) |
|                   | `visibility`             | `visible`, `hidden`                                | Dikhna ya chhupana (space rakhta hai) |
|                   | `transition`             | `all 0.3s ease`                                    | Smooth change (hover effects) |
|                   | `transform`              | `rotate(45deg)`, `scale(1.2)`, `translate(50px)`   | Rotate, scale, move element |
