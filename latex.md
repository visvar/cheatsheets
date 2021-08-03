# Latex 

## How to use this sheet

Syntax highlighting with three ```:

  ```latex
  e^{i \pi} = -1
  ```
Render latex through this trick:

```html
<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">
```

<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">

## Colored Comments

```latex
\usepackage{color}
\definecolor{mycolor}{rgb}{0,0.5,0.9}
\newcommand\mycomment[1]{{\color{mycolor}Comment: #1}}
```

## Links

```latex
\usepackage{hyperref}
\href{https://example.com/}{Example}
```
