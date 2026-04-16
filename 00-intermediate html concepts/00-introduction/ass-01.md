
### HTML Elements Cheat Sheet

| Tag                  | Description (Simple)                                      | Common Attributes                  | Notes                  |
|----------------------|-----------------------------------------------------------|------------------------------------|------------------------|
| **Main Root**        |                                                           |                                    |                        |
| `<html>`            | Puri HTML document ka root element                        | -                                  | -                      |
| **Document Metadata**|                                                           |                                    |                        |
| `<head>`            | Metadata (title, styles, scripts) ke liye                 | -                                  | -                      |
| `<title>`           | Browser tab mein dikhne wala title                        | -                                  | -                      |
| `<meta>`            | Meta information (charset, description, etc.)             | `name`, `content`, `http-equiv`    | -                      |
| `<link>`            | CSS, favicon, etc. link karne ke liye                     | `rel`, `href`                      | -                      |
| `<style>`           | Page ke andar CSS likhne ke liye                          | -                                  | -                      |
| `<base>`            | Sab relative URLs ke liye base URL set karta hai          | `href`, `target`                   | -                      |
| **Sectioning**       |                                                           |                                    |                        |
| `<body>`            | Visible content ka main container                         | -                                  | -                      |
| `<header>`          | Introduction / navigation area                            | -                                  | -                      |
| `<nav>`             | Navigation links                                          | -                                  | -                      |
| `<main>`            | Document ka main important content                        | -                                  | -                      |
| `<article>`         | Independent content (blog post, news, etc.)               | -                                  | -                      |
| `<section>`         | Generic section with heading                              | -                                  | -                      |
| `<aside>`           | Sidebar / related content                                 | -                                  | -                      |
| `<footer>`          | Footer content                                            | -                                  | -                      |
| `<h1>` to `<h6>`    | Headings (h1 sabse bada, h6 sabse chhota)                 | -                                  | -                      |
| **Text Content**     |                                                           |                                    |                        |
| `<p>`               | Paragraph                                                 | -                                  | -                      |
| `<div>`             | Generic block container (CSS ke liye)                     | `class`, `id`                      | Bohot common           |
| `<span>`            | Generic inline container                                  | `class`, `id`                      | Bohot common           |
| `<ul>`              | Unordered (bulleted) list                                 | -                                  | -                      |
| `<ol>`              | Ordered (numbered) list                                   | `type`, `start`, `reversed`        | -                      |
| `<li>`              | List item                                                 | -                                  | -                      |
| `<dl>`, `<dt>`, `<dd>` | Description list (terms + definitions)                 | -                                  | -                      |
| `<figure>`, `<figcaption>` | Image/video with caption                             | -                                  | -                      |
| `<pre>`             | Preformatted text (whitespace preserve)                   | -                                  | -                      |
| **Inline Text**      |                                                           |                                    |                        |
| `<a>`               | Hyperlink                                                 | `href`, `target`, `rel`            | Sabse important        |
| `<strong>`          | Strong importance                                         | -                                  | -                      |
| `<em>`              | Emphasized text                                           | -                                  | -                      |
| `<code>`            | Inline code                                               | -                                  | -                      |
| `<mark>`            | Highlighted text                                          | -                                  | -                      |
| `<small>`           | Small print / side comments                               | -                                  | -                      |
| `<br>`              | Line break                                                | -                                  | -                      |
| `<hr>`              | Horizontal line / thematic break                          | -                                  | -                      |
| **Media**            |                                                           |                                    |                        |
| `<img>`             | Image embed                                               | `src`, `alt`, `width`, `height`    | -                      |
| `<audio>`           | Audio player                                              | `src`, `controls`                  | -                      |
| `<video>`           | Video player                                              | `src`, `controls`, `width`, `height` | -                    |
| `<picture>`         | Responsive images ke liye                                 | -                                  | -                      |
| `<source>`          | Media sources (video/audio/picture ke andar)              | `src`, `type`                      | -                      |
| **Table**            |                                                           |                                    |                        |
| `<table>`           | Table banane ke liye                                      | -                                  | -                      |
| `<tr>`              | Table row                                                 | -                                  | -                      |
| `<th>`              | Table header cell                                         | `colspan`, `rowspan`               | -                      |
| `<td>`              | Table data cell                                           | `colspan`, `rowspan`               | -                      |
| `<thead>`, `<tbody>`, `<tfoot>` | Table ke parts                                   | -                                  | -                      |
| **Forms**            |                                                           |                                    |                        |
| `<form>`            | Form container                                            | `action`, `method`                 | -                      |
| `<input>`           | Text, password, checkbox, radio, etc.                     | `type`, `name`, `value`, `placeholder` | Bohot common       |
| `<label>`           | Form control ka label                                     | `for`                              | -                      |
| `<button>`          | Clickable button                                          | `type`                             | -                      |
| `<textarea>`        | Multi-line text input                                     | `rows`, `cols`                     | -                      |
| `<select>`, `<option>` | Dropdown list                                          | -                                  | -                      |
| **Others**           |                                                           |                                    |                        |
| `<script>`          | JavaScript code                                           | `src`                              | -                      |
| `<noscript>`        | Jab JavaScript disable ho                                 | -                                  | -                      |
| `<iframe>`          | Dusri website/page embed karein                           | `src`                              | -                      |
| `<canvas>`          | JavaScript se drawing ke liye                             | `width`, `height`                  | -                      |
| `<svg>`             | SVG graphics                                              | `width`, `height`                  | -                      |