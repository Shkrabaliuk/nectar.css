# Nectar.css

A classless CSS framework for semantic HTML.  
CSS-фреймворк без класів для семантичного HTML.

---

<details>
<summary><strong>English</strong></summary>

## Features

- No classes required — semantic HTML only
- Automatic dark mode (system preference)
- Responsive by default
- Lightweight (~8 KB minified)
- Customizable via CSS variables
- Supports modern browsers

## Quick start

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My page</title>
  <link rel="stylesheet" href="nectar.css">
</head>
<body>
  <h1>Hello world</h1>
  <p>Semantic HTML without classes.</p>
</body>
</html>
```

## Customization

Override CSS variables:

```css
:root {
  --bg: #ffffff;
  --text: #000000;
  --link: #0060a0;
  --button-bg: #e87840;
  --max-width: 1280px;
}
```

## Dark mode

Dark mode follows system settings automatically.  
Manual toggle:

```js
document.documentElement.classList.toggle('dark-theme');
```

</details>

<details>
<summary><strong>Українська</strong></summary>

## Особливості

- Без класів — лише семантичний HTML
- Автоматична темна тема
- Адаптивний дизайн за замовчуванням
- Легкий (~8 KB у мініфікованому вигляді)
- Налаштування через CSS-змінні
- Підтримка сучасних браузерів

## Швидкий старт

```html
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Моя сторінка</title>
  <link rel="stylesheet" href="nectar.css">
</head>
<body>
  <h1>Привіт, світ</h1>
  <p>Семантичний HTML без класів.</p>
</body>
</html>
```

## Налаштування

Перевизначення CSS-змінних:

```css
:root {
  --bg: #ffffff;
  --text: #000000;
  --link: #0060a0;
  --button-bg: #e87840;
  --max-width: 1280px;
}
```

## Темна тема

Темна тема вмикається автоматично.  
Ручне перемикання:

```js
document.documentElement.classList.toggle('dark-theme');
```

</details>

---

## License

Public domain.  
See the LICENSE file for details.

---

Created by Shkrabaliuk.
