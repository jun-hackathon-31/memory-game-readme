# Memory Game для Джун-Хакатона

## Команда #31
| Роль | Имя | Телеграм |
| ----------- | ----------- | ----------- |
| Backend | Дарья | [@darya_koval93](https://t.me/darya_koval93) |
| Frontend | Таисия | [@ieriel](https://t.me/ieriel) |
| Frontend | Валентина | [@danilova_v_v](https://t.me/danilova_v_v) |

## Стек проекта
Frontend: React, JavaScript, React-Bootstrap, Bootstrap \
Backend: Java, Gradle, Spring Boot, GNU Make, Docker, H2 (development), PostgreSQL (production),  deploy on Render.

## Описание проекта
Игра с карточками, которые открываются попарно. Задача - открыть все карточки за наименьшее количество ходов.

## Локальное развертывание бэкенд части проекта
* ### Setup
```bash
make setup
```
* ### Run server
```bash
make start
# Open http://localhost:8080/welcome
```

## Локальное разветывание фронтенд части проекта
Склонируйте репозиторий на свой компьютер.

В терминале перейдите в директорию склонированного проекта.

Введите команду для установки зависимостей:
```bach
npm i
```
Затем введите команду для запуска фронтенд-части:
```bach
npm run dev
```
После запуска в терминале будет сопутствующая информация и адрес, по которому проект был запущен, либо перейдите по этой ссылке в своём браузере: 
```bach
http://localhost:5173/
```

### Фичи
#### Базовые
- [x] вывод поля с рандомно расположенными карточками (каждый раунд - новая позиция карточек);
- [x] возможность открывать карточки;
- [x] закрытие непарных карточек, парные - остаются открытыми;
- [x] подсчет количества ходов;
- [x] возможность начать игру заново;
- [x] экран поздравления с окончанием игры.

**Вывод поля с рандомно расположенными карточками (каждый раунд - новая позиция карточек)**

![generate-field](https://github.com/jun-hackathon-31/memory-game-readme/assets/93980203/c644dd5d-370f-4e9c-82c7-eedfcd46f928)

**Возможность открывать карточки**

![open-card](https://github.com/jun-hackathon-31/memory-game-readme/assets/93980203/bb2604bc-a1d6-424e-975b-51a080571cd8)

**Закрытие непарных карточек, парные - остаются открытыми** и **Подсчет количества ходов**

![flipping-card](https://github.com/jun-hackathon-31/memory-game-readme/assets/93980203/60bc41e6-ac4c-478f-bde2-0e20587badd7)

**Возможность начать игру заново**

![restart](https://github.com/jun-hackathon-31/memory-game-readme/assets/93980203/a8043b4f-a2d9-4c02-b034-9ebb5dd0723f)

**Экран поздравления с окончанием игры**

![final](https://github.com/jun-hackathon-31/memory-game-readme/assets/93980203/407380a0-0810-4c6b-bd2c-e14c2f9dc6ff)

#### Дополнительные
Для расширения взяли лидерборд. \
Реализация лидерборда полностью готова на бэкенде, фронтенд подключить не успели. \
[OPEN API реализации лидерборда](https://memory-game-j84d.onrender.com/swagger-ui/index.html#/Users%20controller/index_2) : выводит список игроков с их лучшим результатом по количеству ходов в игре, отсортированный по возрастанию ходов. Уровень сложности базовый.

# Ссылки на деплой

* ## Деплой бэкенд части проекта
  [Demo on Render](https://memory-game-j84d.onrender.com/welcome)

* ## Деплой фронтенд части проекта
  [link]()
