# 🎓 Оформление README-файла для студенческого проекта

Этот файл — пример того, как грамотно оформить `README.md`. 
Он помогает другим (и вам самим) быстро понять, что делает ваш проект, как он устроен и где найти нужные материалы.

---

## 📖 Описание проекта

Кратко опишите, что делает проект, какие задачи решает и почему он полезен.  
Например:

> Приложение помогает студентам отслеживать дедлайны по учебным курсам. Интерфейс минималистичный, всё хранится в LocalStorage.

---

## 🖼 Скриншоты

Добавьте сюда изображение интерфейса или архитектуры проекта:

![Пример интерфейса](./images/screenshot.png)

---

## ⚙️ Используемые технологии

| Технология    | Назначение               | Версия     |
|---------------|---------------------------|------------|
| HTML          | Разметка                  | 5.0        |
| CSS           | Стилизация                | 3.0        |
| JavaScript    | Логика на клиенте         | ES6+       |
| Figma         | Прототипирование UI       | n/a        |

---

## 📌 Пример использования

Простой пример вызова компонента или функции:

```js
showDeadlineAlert("Остался 1 день до дедлайна!");

## 🔗 Ссылки проекта

- [Сайт проекта](https://example.com)
- [Figma-дизайн](https://www.figma.com/file/xyz123/ProjectName)
- [Документация по API](docs/api.md)
- [Презентация проекта (PDF)](presentation.pdf)




# Типы данных в JavaScript

В JavaScript существует 8 основных типов данных, которые можно разделить на примитивные и сложные (объекты).

| **Тип данных**  | **Пример**                      | **Описание**                                                                      |
|------------------|---------------------------------|----------------------------------------------------------------------------------|
| **Number**       | `42`, `3.14`, `NaN`, `Infinity`| Числа, включая специальные значения `NaN` (не число) и `Infinity`.              |
| **BigInt**       | `123456789n`                   | Для работы с числами, превышающими диапазон `Number`.                           |
| **String**       | `'hello'`, `"world"`, `` `!` ``| Текстовые строки, включая поддержку интерполяции через шаблонные строки.         |
| **Boolean**      | `true`, `false`                | Логические значения, обычно используются в условиях.                            |
| **Undefined**    | `undefined`                   | Переменная объявлена, но значение не присвоено.                                 |
| **Null**         | `null`                        | Представляет "пустое" значение, заданное вручную.                               |
| **Symbol**       | `Symbol('id')`                | Уникальный идентификатор, полезен для создания уникальных ключей объектов.      |
| **Object**       | `{ name: "Alice" }`           | Сложная структура данных для коллекции свойств и методов.                       |

## Оператор `typeof`

Для определения типа данных в JavaScript используется оператор `typeof`:

```javascript
console.log(typeof 42);           // "number"
console.log(typeof "hello");      // "string"
console.log(typeof true);         // "boolean"
console.log(typeof undefined);    // "undefined"
console.log(typeof null);         // "object" (ошибка языка)
console.log(typeof Symbol("id")); // "symbol"
console.log(typeof {});           // "object"
console.log(typeof function(){}); // "function"

Примечание
null используется, чтобы явно указать на отсутствие значения
undefined означает, что значение переменной не было присвоено

## 👨‍💻 Автор

- [Нона Аракелян](https://github.com/yourGitHub) — преподаватель ВШЭ Школа дизайна

