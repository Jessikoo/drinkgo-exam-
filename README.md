# drink2go-exam

## Набор инструментов для проверки проекта грейдирования

### Подготовка 
- установите зависимости `npm install`
- создайте скриншоты эталонного проекта `npm run reference` (процесс займет пару минут)
- скриншоты сохраняются в папке `backstop_data/bitmaps_reference`
- положите проект для проверки в папку `project` - проверки работают **только с этой папкой**
- соберите проект и запустите сервер командой `npm run preview`
- проверьте, что проект собран и открывается в браузере http://localhost:3000
- сервер со студенческим проектом должен быть запущен, откройте новый терминал 
- запускайте отдельные тесты командами `npm run test-03`
- отчет о проверке откроется в браузере
- файл отчета сохранен в `backstop_data/html_report/index.html`

### Этап тестирования
- `npm run test-pp` проверяем блоки по PP и создает конфиг для проверки стилей
- `npm run test-swiper` **JS1-Б1** покажет поведение слайдера (только если ПП)
- `npm run test-menu` **JS1-Б1** покажет поведение меню (только если ПП)
- `npm run test-05` **HTML2-Б11** показывает базовые текстовые стили для PixelPerfect блоков
- `npm run test-08` **HTML1-TEST-08** покажет элементы, которые изменяют размеры при взаимодействии
- `npm run test-07` **HTML1-TEST-07** показывает состояния интерактивных элементов

### Проверка кода
- `npm run linthtml` **HTML1-PROJ-01** покажет ошибки html
- `npm run stylelint` **HTML1-PROJ-01** покажет ошибки sass
- `npm run img-size` **HTML2-Д1**
- `npm run input-label` **HTML1-HTML-05**
- `npm run meta-viewport` **HTML2-Б15**
- `npm run no-important` **HTML1-CSS-05**
- `npm run no-id` **HTML1-CSS-04**
- `npm run no-extend` **HTML2-Д12**
- `npm run no-union-class-name` **HTML2-Д11**
- `npm run bemlinter` **HTML2-Б5** покажет ошибки BEM
- `npm run w3c` **HTML1-HTML-07** Валидация HTML
- `npm run lint-js` **JS1-Б11** покажет ошибки js

### Этап ревью
- `npm run html-04` **HTML1-HTML-04** проверит отправку форм
- `npm run test-03` **HTML1-TEST-03** показывает поведение на широком / узком экране
- `npm run test-ff` **HTML1-TEST-01** покажет отображение целой страницы в FireFox
- `npm run test-04` **HTML1-TEST-04** показывает переполнение / недополнение элементов
- `npm run img-01` **HTML1-IMG-01** покажет контентные / декоративные изображения
- `npm run html-03` **HTML1-HTML-03** покажет набор ссылок и кнопок
