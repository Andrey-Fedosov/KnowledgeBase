# Knowledge base

## Запись урл репозитория с ссш

- git@github.com:Andrey-Fedosov/KnowledgeBase.git

## Basic syntax of markdown

- ## [Страница с базовым синтаксисом MD](https://www.markdownguide.org/basic-syntax/#links)

- markdown разметка удобна для написания документации, списков литературы, инструкций и т.д.
- занимает мало места. что позоляет удобно сохранить информацию либо на гитхабе либо в обсидиане - организовав тем самым базу знаний.
- использования простых синтаксических конструкция позволяет легко (при помощи только клавиатуры создать удобную для чтения структуру с буллитами, списками, ссылка, вставками кода)

---

1. Маркдаун разметка - правила написания ссылки (для примера - на строке 5 ссылка записана соответствующим образом):

```
  [text for the link](url )
```

---

2. Маркдаун разметка - правила написания изображения:

```
  ![alt-text](link to the image)
```

3. Маркдаун разметка - для написания блока кода:

````

    ```

    // between bacticks you should add a code block
    array.map(el => el.firstName)

    ```

````

## Commands for work with git

    - Команда для добавления удаленного репозитория в ГИТ при использовании SSH: git remote add origin git@github.com:Andrey-Fedosov/training.git
    - ссылка на  страницу с объяснением [как деплоить проект на gh-pages] <https://create-react-app.dev/docs/deployment>
    - git config remote.origin.url: command to see your remote repository;
    - git config user.name: command to see your user name;
    - git config user.email: command to see your user email;
    - git config --list: command to see all config information

## Commands for work with YARN

    - Команда для создания нового реакт проекта  в  YARN:  - yarn create react-app my-app --template typescript
    - Команда для добавления uuid в проект (с типизацией): - yarn add uuid @types/uuid;
    - команда для добавления Типов для css модулей в реакте: yarn add -D typescript-plugin-css-modules
    - Команда для добавления стилизованных компонент (с типизацией): -

---

    - Команда для добавления реакт роутер в проект: yarn add react-router-dom
    - Команда для добавления типов для реакт  роутер дом: yarn add @types/react-router-dom
