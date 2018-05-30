# Примеры Lit-html
Репозиторий с примерами и шаблонами проектирования для создания веб-компонентов с использованием базового класса LitElement и создание шаблонов с использованием lit-html.

# Для кого?
Этот репозиторий можно рассматривать отправной точкой для всех людей, которые хотят писать веб-компоненты с помощью LitElement. Есть и специальны разделы для тех, кто ранее работал с PolymerElement

# Как использовать
Исходный код примеров находится в папке src. Примеры делятся на категории сложности и упорядочены. Понятия вводятся один за другим, только по одному новому понятию на пример.

Все примеры - это рабочий код, поэтому можно клонировать репозиторий и запускать `npm install` +` npm start`.

# Часто задаваемые вопросы
People starting with LitElement, especially those coming from PolymerElement, often have these questions:
* How to set default properties:
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/1-basic/04-default-property.js
* How to handle conditional logic (dom-if from PolymerElement):
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/1-basic/09-conditional-logic.js
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/2-intermediate/08-conditional-templates.js
* How to repeat templates (dom-repeat from PolymerElement):
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/1-basic/10-repeat-templates.js
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/2-intermediate/11-dynamic-repeated-templates.js
* How to compute properties (computed properties from PolymerElement)
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/2-intermediate/01-computed-properties.js
* How to observe property changes (property observers from PolymerElement)
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/2-intermediate/07-did-render.js
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/3-advanced/01-property-setter-observer.js
* How to render templates from external sources, such as a back-end API or html files imported through webpack
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/3-advanced/07-external-template.js
* How to separate CSS, HTML and JS in different files:
  * https://github.com/LarsDenBakker/lit-html-examples/blob/master/src/3-advanced/09-separate-css-html-js-element.js

# Дальнейшее чтение
* Use https://github.com/web-padawan/awesome-lit-html as a starting pointer for further documentation.

# Примечание
This project is a community effort. The authors of this repository are not affiliated with Google or the Polymer team. Because LitElement and lit-html are still in early stages of development, best practices and examples will change and evolve over time.

# Содействие
Contributions are appreciated, feel free to submit issues and PRs.

# Какие примеры надо сделать
* subclassing
* _shouldRender
* upwards data flow
* link to documentation on design choices (unidirectional data flow etc.)
* Implement other components (Polymer) in intermediate
