# Nectar.css

A classless CSS framework for semantic HTML.

Demo: https://shkrabaliuk.github.io/nectar.css/ • Download: style.css

Features

- No classes required — Just semantic HTML
- Automatic dark mode — Respects system preferences
- Fully responsive — Mobile, tablet, desktop
- Lightweight — ~8KB minified
- CSS variables — Easy customization
- Modern browsers — Chrome, Firefox, Safari, Edge

Quick Start

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Page</title>
  <link rel="stylesheet" href="nectar.css">
</head>
<body>
  <h1>Hello World</h1>
  <p>Beautiful semantic HTML without classes.</p>
</body>
</html>
```

Customization

Override CSS variables to change colors and spacing:

```css
:root {
  --bg: #fff;
  --text: #000;
  --link: #0060a0;
  --button-bg: #e87840;
  --max-width: 1280px;
}
```

Dark mode

Dark mode follows system preferences automatically. To toggle manually:

```javascript
document.documentElement.classList.toggle('dark-theme');
```

License

See the `LICENSE` file in this repository for license terms.

Created by Shkrabaliuk in Ukraine.
