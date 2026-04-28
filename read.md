Макет сайта - https://www.figma.com/design/7KDxobww8bmdTb1FhKJUyM/09---HTML-и-CSS?node-id=2-1063&p=f

landing/
├── index.html
├── css/
│   ├── main.css              # Точка входа (импорты)
│   ├── base/                 # Глобальные стили
│   │   ├── variables.css     # CSS-переменные, токены
│   │   ├── reset.css         # Нормализация
│   │   └── typography.css    # Заголовки, текст, списки
│   ├── layout/               # Сетки, контейнеры, header/footer
│   ├── components/           # UI-блоки (кнопки, карточки, формы)
│   └── utilities/            # Утилиты (скрытие, отступы, цвета)
├── img/                      # WebP/AVIF + fallback
├── fonts/                    # Локальные шрифты (woff2)
└── js/                       # (опционально) минимальный скрипт для меню/анимаций