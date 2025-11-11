# Лабораторная работа №4: CSS-библиотеки

## Описание
Лендинг "AI Assistant Pro" — ИИ-помощник для мам. Реализован на Bootstrap 5 (компонентный) и Tailwind CSS (utility-first). Тема: нежная, бежевая, с шрифтом Sitka. Структура: навбар, hero, about, advantages (карточки), footer.

## Скриншоты
### Bootstrap 5
![Bootstrap](screenshots/bootstrap-landing.png)

### Tailwind CSS
![Tailwind](screenshots/tailwind-landing.png)

## Ответы

### Удобнее подход?
Tailwind (utility-first). Почему: гибкая кастомизация цветов/эффектов без !important, быстрая responsive (префиксы md:). Bootstrap проще для базовых, но меньше контроля.

### Пример кода кнопки
**Bootstrap:**
```html
<button class="btn btn-primary">Попробовать бесплатно</button>
```
(Стили в CSS с переопределением.)

**Tailwind:**
```html
<button class="bg-beige-300 hover:bg-beige-400 text-beige-800 font-semibold py-3 px-8 rounded-full shadow-lg hover:shadow-xl transform hover:-translate-y-1 transition-all duration-300">
  Попробовать бесплатно</button>
```

**Различие:** Bootstrap — семантические классы (кратко, но кастом CSS). Tailwind — атомарные утилиты (verbose HTML, inline стили).

### Сложности
**Bootstrap:** Кастом цветов (!important), мобильное меню (JS-хак).  
**Tailwind:** Длинные классы (отладка), ручная сборка компонентов.

### Дополнительный блок
Мобильная навигация (гамбургер): Bootstrap — `.navbar-toggler`; Tailwind — SVG + `hidden md:flex`.

### Запросы ИИ
1. "Бежевые цвета Tailwind для мам-темы" — config, 10/10.  
2. "Hero на Bootstrap с Unsplash" — базовый код, 8/10.  
3. "Навбар Tailwind mobile" — готовый, 9/10.  
4. "Карточки Bootstrap vs Tailwind" — примеры, 10/10.  
Полезно: 70% стилей покрыто, точные ответы на русском.
