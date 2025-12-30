TODO-лист по результатам анализа index.html

(основа — структура и элементы из index.html, просмотрено командой cat index.html)
TODO: Основные блоки/компоненты

    Language toggle: оформить переключатель языка .language-toggle, .language-btn.

    Header: типографика для аватара/имени/теглайна (.avatar, <h1>, .tagline).

    Contacts: единый стиль для .contact-item, ссылок внутри (<a>).

    About section: заголовок <h2> и абзацы <p>.

    Experience section:

        <h2> заголовок секции

        .experience-header (компания .company, .date)

        <h3> роль

        <p> описание

        .context-description (список-подобное оформление)

    Contributions section:

        <h2> заголовок

        вводные <p>

        .badges + .badge + ссылки <a>

    Availability section:

        <h2> заголовок

        .availability блок

        .context-description с параметрами

    Footer: <footer>, <p> копирайт.

TODO: Элементы, требующие типографики

    Заголовки: <h1>, <h2>, <h3> (иерархия, кегли, отступы).

    Лид/теглайн: .tagline (крупнее/контрастнее, иной интерлиньяж).

    Абзацы: <p> (кегль, line-height, вертикальные интервалы).

    Списки/перечни: .context-description (визуальный список).

    Ссылки: <a> (цвет, подчёркивание, hover, читабельность).

    Контакты: .contact-item (кегль и интервалы).

    Бейджи: .badge (компактный кегль, отступы).

    Выделенные блоки: .availability, .context-description (контраст/типографика).

TODO: Practical Typography паттерны

    Иерархия заголовков: подтвердить визуальное различие <h1> → <h2> → <h3>.

    Крупный лид-абзац: выделить лид в header (.tagline) или в #about.

    Длина строки: ограничить ширину текстовых блоков (например, max-width для <p>, .context-description).
