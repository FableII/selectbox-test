# Тестовое задание Компонент Select для выбора стран

## Задача

Разработать компонент `Select` таким образом, чтобы:
- Компонент в свернутом состоянии показывал выбранное значение, либо отображал сообщение "Выберите страну"

- При нажатии на компонент показывать снизу дропдаун, который содержит в себе элементы списка и поле поиска по элементам

- Элементы списка должны фильтроваться при вводе текста в поле поиска

- При выборе элемента из списка необходимо скрыть дропдаун и отобразить выбранное значение в компоненте Select

- При наличии у компонента Select выбранного значения подсвечивать его в списке элементов

- Отображать выбранное значение списка в компоненте ResultArea

### Необязательные задачи:
- После открытия дропдауна автоматически устанавливать фокус в поле поиска

- Закрывать дропдаун при нажатии на область вне дропдауна

- Закрывать дропдаун при нажатии клавиши ESC

## Условия

- склонируйте репозиторий, решением будет являтся предоставленная вами ссылка
- испопльзуйте БЭМ подход при разработке компонентов (пример БЭМ компонента, использующий CSS Modules, `ResultArea`)
- один компонент - один файл, декомпозиция - это хорошо, создавайте любое количество файлов с любым количеством стилей, если это требуется для решения задачи
- не используйте тип `any` при разработке компонентов
- не используйте сторонние библиотеки готовых компонетов, основная задача этого тестового задания понять как вы организуете код, логику компонетов и их верстку
- список стран находится в файле `src/data/countries.ts`

## `npm run start`
