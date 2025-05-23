# 🧪 X-Challenger API Testing (Postman Collection)

Проект с автоматизированным тестированием REST API X-Challenger с помощью Postman.
Включает позитивные и негативные сценарии, проверки граничных значений, 
валидации заголовков и циклы выполнения запросов.

## ✅ Что тестируется

- CRUD-операции;
- Обработка валидных и невалидных запросов;
- Граничные значения: длина полей `title`, `description`;
- Фильтрация по query-параметрам (`doneStatus=true`);
- Проверка заголовков: `Accept`, `Content-Type`, `X-Challenger`;
- Поведение при неподдерживаемых методах и форматах;
- Реализация циклов и автоматизированных сценариев с использованием динамических 
переменных (`pm.collectionVariables`) и скриптов (`pm.execution.setNextRequest()`);

---

## 🚀 Как запустить

1. Импортируй коллекцию в Postman;  
2. Запусти коллекцию через **Collection Runner**
3. Следи за логами и результатами тестов
4. Для отслеживания прогресса выполнений заданий в тренажере в строку браузера следует ввести 
https://apichallenges.herokuapp.com/gui/challenges/{{token}}, где
token - это значение заголовка X-Challenger из API-ответа на первый запрос из коллекции


SergTsys — начинающий тестировщик,  
Проект — часть моей практики и портфолио.

