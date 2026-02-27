# 🧩 Maze Runner

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![React](https://img.shields.io/badge/React-18.2.0-61dafb.svg)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-1.9.5-764abc.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

Лабіринт-гра, де гравець керує персонажем у сітці-лабіринті. Мета — дійти від стартової точки до виходу, уникаючи тупиків. Проект створено в рамках курсу "Компонентно-орієнтоване програмування".

---

## 🎮 Про гру

- **Керування**: клавіші стрілок / WASD або кнопки на екрані
- **Рівні складності**: легкий (9x9), середній (13x13), складний (17x17)
- **Статистика**: час, кроки, успішність
- **Рейтинг гравців**: таблиця результатів з топ-3 медалями

---

## 🛠 Технології

- **Frontend**: React 18 (functional components + hooks)
- **Стейт менеджмент**: Redux Toolkit (3 слайси: settings, gameStats, user)
- **Стилізація**: Styled Components
- **Маршрутизація**: React Router v6 (динамічні маршрути з :userId)
- **Форми**: React Hook Form (з валідацією)
- **Збереження даних**: LocalStorage
- **Збірка**: Create React App

---

## 📁 Структура проекту

```
src/
├── components/          # Перевикористовувані компоненти
│   ├── UI/              # Button, Modal, Loader
│   ├── layout/          # Header, Footer
│   └── game/            # MazeGrid, GameControls, GameOverDialog
├── pages/               # StartPage, GamePage, ResultsPage, UserProfile, ResultsTable
├── hooks/               # useGame, useGameControls, useNavigation
├── store/               # Redux store
│   └── slices/          # settingsSlice, gameStatsSlice, userSlice
├── styles/              # Глобальні стилі
└── utils/               # Допоміжні функції
```

---

## 🚀 Встановлення та запуск

```bash
# Клонувати репозиторій
git clone https://github.com/your-username/maze-runner.git

# Перейти в папку проекту
cd maze-runner

# Встановити залежності
npm install

# Запустити проект
npm start
```

Після запуску проект буде доступний за адресою: `http://localhost:3000`

---

## 📦 Команди

| Команда | Опис |
|---------|------|
| `npm start` | Запуск в режимі розробки |
| `npm run build` | Збірка для продакшну |
| `npm test` | Запуск тестів |
| `npm run storybook` | Запуск Storybook |
| `npm run docs` | Генерація документації |

---

## 📜 Ліцензія

Цей проект ліцензовано під ліцензією MIT. Див. файл [LICENSE](LICENSE).

---

## ✍️ Автор

**Студентка**: [Твоє Ім'я]
**Група**: [Твоя група]
**Предмет**: Компонентно-орієнтоване програмування
**Рік**: 2025

---

## 🎯 Функціональні можливості

- ✅ Генерація лабіринтів різної складності
- ✅ Керування клавішами / кнопками
- ✅ Система статистики та результатів
- ✅ Налаштування гри (складність, тип керування)
- ✅ Профіль користувача з редагуванням
- ✅ Таблиця рейтингів з медалями
- ✅ Збереження даних в LocalStorage

---

## 📖 Документація

- [JSDoc документація](./docs/index.html)
- [Storybook](./storybook-static/index.html)
- [Політика конфіденційності](./PRIVACY.md)
- [Умови використання](./EULA.md)

---

## 🍪 Cookie Popup

Проект відповідає вимогам GDPR. При першому відвідуванні з'являється повідомлення про використання cookies.

---

## 🐛 Відомі проблеми

*Якщо знайдеш баги — створи Issue у репозиторії!*

---

## 🌟 Подяки

Дякую викладачам курсу "Компонентно-орієнтоване програмування" за допомогу та натхнення!
