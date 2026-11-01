<h1 align="center">📊 parse-tracker</h1>

<p align="center">
  Автономный локальный веб-интерфейс для отслеживания источников парсинга, статусов задач и дедлайнов
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Single--File-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Dependencies-Zero-brightgreen" alt="Dependencies">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
</p>

---

## ✨ Возможности

- 📋 **Учет источников**: добавление сайтов и ссылок с указанием планируемого начала и окончания сбора.
- 🚦 **4 понятных статуса**: `Не начат`, `В процессе`, `Готово`, `Ошибка`.
- ⏰ **Контроль дедлайнов**: автоматическая подсветка просроченных задач, если запланированное время прошло.
- 🔍 **Фильтрация и аналитика**: мгновенный фильтр по статусам и счетчики задач в реальном времени.
- 💾 **Экспорт и импорт**: выгрузка в CSV (для Excel/Google Таблиц) и JSON (для резервных копий и переноса).
- 🌓 **Адаптивная тема**: автоматическая поддержка светлой и темной темы оформления.
- ⚡ **Zero-Setup**: работает без сервера, сборки и внешних библиотек прямо в браузере.

---

## 🛠 Стек технологий

- **HTML5 / CSS3** (CSS Variables, Flexbox, Grid)
- **Vanilla JavaScript** (ES6+)
- **LocalStorage API** — сохранение данных на вашем устройстве

---

## 🚀 Быстрый старт

Установка не требуется. Достаточно открыть файл `index.html` в любом браузере:

```bash
# 1. Клонирование репозитория
git clone https://github.com/egorfm/parse-tracker.git
cd parse-tracker

# 2. Открытие в браузере (macOS)
open index.html

# Для Linux: xdg-open index.html
# Для Windows: start index.html
```

---

## 💻 Хранение данных

Все данные сохраняются локально в `localStorage` вашего браузера:
- Данные не отправляются во внешнюю сеть и остаются строго конфиденциальными.
- Для резервного копирования или переноса на другое устройство используйте кнопку **«Экспорт JSON»**.

---

## 📁 Структура проекта

```
parse-tracker/
├── index.html     # Полный интерфейс (разметка, стили и логика)
├── LICENSE        # Лицензия MIT
└── README.md      # Документация проекта
```

---

## 📄 Лицензия

Проект распространяется под лицензией [MIT](LICENSE).
