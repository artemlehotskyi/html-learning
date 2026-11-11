# Практична робота №8
## Форматування тексту в CSS

Оформити заголовки, абзаци, список і примітку властивостями шрифту та тексту.

## Що використано

| Елемент | Властивості |
|---|---|
| `h1` | `font-family: Georgia`, `font-size`, `font-style: italic`, `text-shadow` |
| `.main-text` | `line-height: 1.6`, `text-align: justify` |
| `.highlight` | `background-color` + `:hover` з `transition: 0.3s` |
| `.note` | `rgba(0,0,0,0.5)`, `font-size: 12px`, `font-weight: 300`, `text-decoration: underline` |
| `ul`, `li` | `list-style-type: square`, `li:first-child` |
| `.caps` | `text-transform: capitalize` |

## Цікаве місце

`text-transform: capitalize` змінює лише **відображення**: у HTML речення лишається
з малої літери, а браузер малює кожне слово з великої. Якщо скопіювати цей текст зі
сторінки, вставиться той варіант, який бачиш на екрані, а в коді нічого не змінюється.

`rgba(0, 0, 0, 0.5)` — чорний з прозорістю 50%. Через це примітка виглядає сірою,
але насправді змішується з тлом під нею.

## Запуск

Відкрити [`index.html`](index.html) у браузері. Навести курсор на помаранчевий рядок.
