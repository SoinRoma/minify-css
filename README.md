<h1 align="center">Base-min-css</h1>

## Описание:
Минимальный набор CSS-классов.

## Установка и подключение:

```
npm install base-min-css
```

### React

Подключить в любом месте index.js: `import 'base-min-css';`

### SASS/SCSS

Открыть самый главный файл со стилями и дописать в самом начале: `@import 'base-min-css';`

## Обозначения:

Внизу в таблице приведены примеры классов, которые можно использовать.

### Например:

| Класс               | Значение                                                      |
| ------------------- | ------------------------------------------------------------- |
| `mr-10 mb-50`       | `margin-right: 10px; margin-bottom: 50px;`                    |
| `p-25`              | `padding: 25px;`                                              |

### Очистка базовых стилей

clear - Очищает базовые стили, которые устанавливает браузер для: `<a>, <ul>, <li>`. 


### Flex, позиционирование, размер

| Класс           | Значение                        |
| --------------- | ------------------------------- |
| h100p           | height: 100%;                   |
| w100p           | width: 100%;                    |
| d-ib            | display: inline-block;          |
| d-if            | display: inline-flex;           |
| d-flex          | display: flex;                  |
| d-block         | display: block;                 |
| justify-between | justify-content: space-between; |
| justify-around  | justify-content: space-around;  |
| justify-center  | justify-content: center;        |
| align-center    | align-items: center;            |
| align-end       | align-items: flex-end;          |
| align-start     | align-items: flex-start;        |
| flex-column     | flex-direction: column;         |
| flex-row        | flex-direction: row;            |
| flex-wrap       | flex-wrap: wrap;                |
| flex-auto       | flex: 1 1 auto;                 |
| flex            | flex: 1;                        |
| m-auto          | margin: auto;                   |
| ml-auto         | margin-left: auto;              |
| mr-auto         | margin-right: auto;             |
| text-center     | text-align: center;             |
| pos-r           | position: relative;             |
| pos-a           | position: absolute;             |

### Текст

| Класс           | Значение                                                        |
| --------------- | --------------------------------------------------------------- |
| text-center     | text-align: center;                                             |
| text-capitalize | text-transform: capitalize;                                     |
| text-uppercase  | text-transform: uppercase;                                      |
| text-lowercase  | text-transform: lowercase;                                      |
| text-truncate   | white-space: nowrap; overflow: hidden; text-overflow: ellipsis; |
| fw-bold         | font-weight: bold;                                              |

### Opacity

| Класс      | Значение      |
| ---------- | ------------- |
| opacity-1  | opacity: 0.1; |
| opacity-10 | opacity: 1;   |
