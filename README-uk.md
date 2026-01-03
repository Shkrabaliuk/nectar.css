## Nectar.css

CSS‑фреймворк без класів для семантичного HTML.

Демо: https://shkrabaliuk.github.io/nectar.css/ • Завантажити: style.css

Особливості

- Класи не потрібні — Тільки семантичний HTML
- Автоматична темна тема — Враховує системні налаштування
- Повністю адаптивний — Мобільні, планшети, десктоп
- Легкий — ~8KB у мініфікованому вигляді
- CSS‑змінні — Легке налаштування
- Сучасні браузери — Chrome, Firefox, Safari, Edge

Швидкий старт

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
  <p>Красивий семантичний HTML без жодного класу.</p>
</body>
</html>
```

Налаштування

Перевизначте CSS‑змінні, щоб змінити кольори та відступи:

```css
:root {
  --bg: #fff;
  --text: #000;
  --link: #0060a0;
  --button-bg: #e87840;
  --max-width: 1280px;
}
```

Тема

Темна тема вмикається автоматично відповідно до системних налаштувань. Для ручного перемикання:

```javascript
document.documentElement.classList.toggle('dark-theme');
```

Ліцензія

Дивіться файл `LICENSE` у репозиторії для умов ліцензії.

Створив Shkrabaliuk в Україні.
