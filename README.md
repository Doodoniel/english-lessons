# English Lessons

Интерактивные надстройки к урокам английского: страницы учебника в центре,
вокруг — задания, справка и игровые механики.

## Уроки

| # | Урок | Что внутри |
|---|------|-----------|
| 1 | [All About Me](unit1-all-about-me/) | Describing people, adverbs, prom culture, reading «Birth order» |
| 2 | [In Fashion](unit2-in-fashion/) | Clothes adjectives, listening (Ashley/Molly/Luke), reading «Fashion and music», домашка p.8–9 с отправкой PDF |
| 2.2 | [Past Simple & Adverbs](unit2-part2-past-simple/) | SB p.16–17: past simple (правила, выбор формы, вопросы, диалог), adverbs of manner, listening про The Beatles, speaking «talking about yourself». Домашка WB p.10–11. Аудио SB и WB в разных папках |
| 3 | [My Way of Life](unit3-my-way-of-life/) | SB p.20–21: life events, квиз про возраст, reading «Is teenage life better now?». Начинается с игры на память (повторение Units 1–2, 5 мин). Домашка WB p.12–13. Аудио SB track 13 — папка готова |
| ★ | [Revision Checkpoint](revision-units-1-2/) | Повторение Units 1–2, все скиллы, 12 этапов: timed vocabulary blitz, collocations, MC cloze, open cloze, proofreading, word order, произношение `-ed`, reading True/False/Doesn't say, writing, speaking по карточкам с таймером, диагностический отчёт по скиллам. Без страниц учебника |
| T | [Unit Tests 1 & 2: Plus](unit-tests-1-2-plus/) | Два печатных теста (Unit 1 Test: Plus и Unit 2 Test: Plus) в одной интерактивной работе, 9 упражнений, задания повторены дословно. По 8 баллов за упражнение: Unit 1 — из 40, Unit 2 — из 32. Одна проверка на упражнение, потом поля блокируются; правильные ответы не показываются. В конце — балл и процент отдельно по каждому тесту и отчёт для печати |
| 3 | [People & Style](unit3-people-and-style/) | Review & beyond Units 1–2 (12 этапов, ~90 мин): vocab sort, word building (un-/im-/dis-), comparatives, relative clauses, sentence transformation, оригинальный reading, word stress, proofreading, dialogue ordering, writing, speaking, self-assessment. Без страниц учебника |

## Как пользоваться

Открыть `index.html` в браузере — сервер не нужен. Прогресс, ответы и рисунки
хранятся в localStorage браузера.

### Возможности урока

- Страницы учебника с вкладками, полноэкранный просмотр
- **✍️ Write on page** — печатать ответы прямо поверх страницы, поля перетаскиваются за уголок
- **🖊 Draw** — обводить, подчёркивать, выделять маркером; ластик и Ctrl+Z
- **🖨 Print** — печать страницы вместе с ответами и рисунками
- Аудио с плеерами и текстовым аудиоскриптом (открывается по кнопке, чтобы не подглядывать)
- 6 интерактивных заданий, XP, уровни и медали
- Тёмная тема

### Отличия Unit 2

- Интерактивные задания **дублируют упражнения учебника** с той же нумерацией.
  Кнопка **Show on page** приближает страницу и подсвечивает нужное упражнение.
- Дополнительные задания (spelling, decades, odd one out, writing, speaking) вынесены
  **в конец**, после упражнений учебника.
- Домашка (Workbook p.8–9) выполняется **только письмом и рисованием** поверх страницы.
  Кнопка **Save as PDF & send** собирает обе страницы в один PDF и открывает письмо
  учителю — файл нужно приложить вручную (`mailto:` не умеет вложения).
  Адрес учителя задаётся в начале `<script>`, константа `TEACHER_MAIL`.

## Как добавить новый урок

1. Создать папку `unitN-название/` с `index.html`, `pages/`, `audio/`
2. Добавить строку в таблицу выше и карточку в корневой `index.html`

## Материалы

Страницы и аудио принадлежат издателю учебника и включены исключительно для
использования на занятиях. Сайт закрыт от индексации поисковиками
(`robots.txt` + `<meta name="robots" content="noindex">`).
