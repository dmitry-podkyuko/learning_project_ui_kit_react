# Практическое задание (UI-kit)

## Описание:

Задание направлено на изучение принципов построения кастомного UI-kit, по его завершению вы получите небольшую переиспользуемую библиотеку копонентов для React.

## Требования к реализуемым компонентам:

- Запрещено использовать любые сторонние библиотеки, все что доступно для использования можно посмотреть в `package.json` в разделе `devDependencies` и `dependencies`
- Стили должны быть написаны с использованием `SCSS` с использованием `scss.module`
- Компоненты должны быть атомарными, то есть вся их логика и зависимости должны содержаться внутри папки с компонентом
- Компоненты должны быть пригодны для использования, все необходимые для отображения данные должны передаваться через `props`.
  (P.s Названия и типизацию пропсов разрешено подсмотреть в любой популярной библиотеке, например Mui)
- Весь код должен быть написан на TypeScript, запрещено выключать TS в файлах или на каких либо строках, запрещено менять правила в tsconfig
- Весь код должен быть написан с использованием кодстайла, указанного в eslint, запрещено выключать eslint или глушить его в файлах
- Верстка компонентов должна быть perfect pixel, проверить это можно при помощи любого вспомогательного расширения в браузере, требуемые размеры можно посмотреть в макете Figma
- Все компоненты должны быть задокументированы с использованием <a href='https://www.npmjs.com/package/jsdoc'>JsDoc</a>
- Вся цветовая гамма должны быть вынесена в переменные, разрешается создать общий файл с переменными и подключать его в каждый файл стилей

## Уточняющие требования к определенным компонентам:

- Modal:
  - Компонент всегда должен открываться ровно в центре страницы, поверх других элементов
  - Модальное окно должно вызывать колбек закрытия при нажатии вне окна
- Notification:
  - Компонент всегда должен открываться в верхнем правом углу страницы, поверх других элементов
- Table:
  - Компонент всегда должениметь возможность добавления бесконечного количества строк и столбцов
  - При большом количестве столбцов, должна появляться полоса прокрутки для таблицы (!НЕ СТРАНИЦЫ)

## Чек лист для сдачи проекта:

- [ ] Git Flow соблюдается, ветки и коммиты соответствуют всем правилам
- [ ] Компонент Dropdown реализован и соответствует вышеописанным требованиям
- [ ] Компонент Accordion реализован и соответствует вышеописанным требованиям
- [ ] Компонент Modal реализован и соответствует вышеописанным требованиям
- [ ] Компонент Notification реализован и соответствует вышеописанным требованиям
- [ ] Компонент Switch реализован и соответствует вышеописанным требованиям
- [ ] Компонент Table реализован и соответствует вышеописанным требованиям
- [ ] PullRequest из `feat/components` в `develop` создан
- [ ] Code Review проведено разработчиком лично
- [ ] Code Review проведено куратором (выделяется техническим лидером)
- [ ] Code Review проведено техническим лидером

## Полезные ссылки:

- <a href="https://www.figma.com/design/iMWtPrqpXaxvKxaCR7DQA4/UI-KIT-(Community)?node-id=135-797&t=i2c5FD1W6wkUGm1S-1">_Link to Designe_</a>
- GitFlow ( <a href='https://www.atlassian.com/ru/git/tutorials/comparing-workflows/gitflow-workflow'>Variant #1</a> )
- CheckList для React CodeReview <a href="https://gist.github.com/podkuyko/03334d1fb3cfee50df22fd55c80530c7">Link</a>
