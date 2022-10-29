---
title: Доступность
slug: Learn/Accessibility
tags:
  - CSS
  - HTML
  - JavaScript
  - Удобство
  - доступность
translation_of: Learn/Accessibility
original_slug: Learn/Доступность
---
{{LearnSidebar}}

Изучение HTML, CSS, и JavaScript полезно, если вы хотите стать веб-разработчиком, но ваши знания должны быть глубже обычного использования технологий — вы должны быть ответственны и максимизировать доступность ваших веб-приложений, не лишая никого возможности их использования. Чтобы достигнуть этого, вы можете следовать общепринятым лучшим практикам (которые демонстрируются в статьях посвящённых [HTML](/ru/docs/Learn/HTML), [CSS](/ru/docs/Learn/CSS) и [JavaScript](/ru/docs/Learn/JavaScript)), проводить [кросс-браузерное тестирование](/ru/docs/Learn/Tools_and_testing/Cross_browser_testing) и обращать внимание на доступность с самого начала. В этом модуле мы рассмотрим эту тему в деталях.

## Прежде чем начать

Чтобы разобраться с большей частью материалов этого модуля, хорошей идеей будет проходить одновременно один или несколько из модулей других тем ([HTML](/ru/docs/Learn/HTML), [CSS](/ru/docs/Learn/CSS) или [JavaScript](/ru/docs/Learn/JavaScript)), или, что ещё лучше, пройти соответствующие части данного модуля во время изучения этих технологий.

> **Примечание:** Если вы работаете на компьютере/планшете/другом устройстве, на котором у вас нет возможности создавать файлы, вы можете попробовать большую часть примеров кода в онлайн программах, таких как [JSBin](http://jsbin.com/) или [Thimble](https://thimble.mozilla.org/).

## Справочники

- [Что такое доступность?](/ru/docs/Learn/Accessibility/What_is_accessibility)
  - : Данная статья открывает модуль, в котором рассматривается, что такое доступность на самом деле — она включает в себя группы людей, которые нам нужно учитывать и почему, какие инструменты используют разные пользователи для взаимодействия с вебом, и как мы можем сделать доступность частью нашего рабочего процесса веб-разработки.
- [HTML: Хорошая основа для доступности](/ru/docs/Learn/Accessibility/HTML)
  - : Большая часть содержимого интернета может быть сделана доступной просто благодаря использованию HTML-элементов по назначению. В этой статье подробно рассмотрено как HTML может быть использован для обеспечения максимальной доступности.
- [Лучшие практики CSS и JavaScript для обеспечения доступности](/ru/docs/Learn/Accessibility/CSS_and_JavaScript)
  - : CSS и JavaScript, при правильном использовании, также имеют потенциал для обеспечения доступности, но при неправильном использовании они могут существенно ухудшить доступность. Эта статья раскрывает некоторые из лучших практик CSS и JavaScript которые должны помочь сделать даже очень сложное содержимое как можно более доступным.
- [Основы WAI-ARIA](/ru/docs/Learn/Accessibility/WAI-ARIA_basics)
  - : _Web Accessibility Initiative - Accessible Rich Internet Applications_ — это технологический стандарт для предоставления возможности полноценного использования Интернета людьми с физическими ограничениями.
    Исходя из предыдущей статьи, иногда создание сложных элементов управления пользовательским интерфейсом, которые включают в себя не семантический HTML и динамический контент, обновляемый с помощью JavaScript, может быть затруднено. WAI-ARIA — это технология, которая может помочь в решении таких проблем, добавляя дополнительную семантику, которую браузеры и вспомогательные технологии могут распознавать и использовать, чтобы пользователи знали, что происходит. Здесь мы покажем, как использовать его на базовом уровне для улучшения доступности.
- [Доступный мультимедиа контент](/ru/docs/Learn/Accessibility/Multimedia)
  - : Другая категория контента, которая может создавать проблемы с доступностью, это мультимедиа — видео, аудио и изображения, которые должны быть предоставлены с надлежащей текстовой альтернативой, чтобы их могли понять с помощью вспомогательных технологий и их пользователи. В этой статье показано, как это можно сделать.
- [Доступность на мобильных устройствах](/ru/docs/Learn/Accessibility/Mobile)
  - : Поскольку веб-доступ на мобильных устройствах является настолько популярным, и на популярных платформах, таких как iOS и Android, есть полноценные средства обеспечения доступности, важно учитывать доступность вашего веб-контента для этих платформ. В этой статье рассматриваются соображения доступности для мобильных устройств.

## Проверка знаний

- [Найди недочёты в доступности](/ru/docs/Learn/Accessibility/Accessibility_troubleshooting)
  - : В этом блоке представлен достаточно простой сайт, в котором, однако, есть множество недочётов в доступности. Необходимо найти их и починить.

## Также советуем посмотреть

- [Начать создание доступных веб-приложений сегодня](https://egghead.io/courses/start-building-accessible-web-applications-today) — отличная серия видеоуроков Марси Саттона.
- [Ресурсы университета Deque](https://dequeuniversity.com/resources/) — включает примеры кода, ссылки для чтения с экрана и другие полезные ресурсы.
- [Ресурсы WebAIM](http://webaim.org/resources/) — включает руководства, контрольные списки, инструменты и многое другое.