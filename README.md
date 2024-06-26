# Федор Плужников — "Manga Translate"

## Описание

### Группа: 10С2

### Элекронная почта: <pluzhnikovf@inbox.ru>

### Telegram: [@fedya_plu](https://t.me/fedya_plu)

**[ НАЗВАНИЕ ПРОЕКТА ]**

"Manga Translate"

**[ ПРОБЛЕМНОЕ ПОЛЕ ]**

В настоящее время в России на одном из популярных сайтов для чтения манги [MangaLib](https://mangalib.me/) заристрированно больше 8 миллионов пользователей. Ежедневно выходят около 150 глав манги, манхвы, маньхуа и т.&nbsp;п. Из них около трети приходится на черно-белую японскую мангу.

Практически всем переводом, а также его графическим оформлением (клинингом и тайпингом) занимаются любители на добровольной основе. Зачастую перевод забрасывается из-за нехватки времени или отсутствия желания. Таким образом, читатели лишаются возможности следить за дальнейшей историей, если не знают язык оригинала.

Мой проект поможет людям самостоятельно переводить главы интересных им произведений практически в один клик.

[ ПОТЕНЦИАЛЬНАЯ АУДИТОРИЯ ]

Азиатские комиксы очень популярны, в первую очередь среди подростков и студентов, поэтому данный проект будет ориентирован на людей в возрасте около 14-24 лет (Источники: [AnimeNewsNetwork, 2019](https://www.animenewsnetwork.com/news/2019-04-22/shueisha-reveals-new-circulation-numbers-demographics-for-its-manga-magazines/.145991#:~:text=27.4%25%20of%20readers%20are%2025,nine%20years%20old%20or%20younger.), [Дзен, 2024](https://dzen.ru/a/Zb1NvOQP62g2x_P_)).

[ АППАРАТНЫЕ / ПРОГРАММНЫЕ ТРЕБОВАНИЯ ]

Программные:

- Python 3
- Библиотеки Python, такие как:
  - OpenCV
  - PyQt6
  - PIL
  - другие, перечисленные в `requirements.txt`

Аппаратные: поддержка всего, что перечислено в программных требованиях.

[ ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ ]

Программный продукт будет предоставлять следующие возможности:

- выбор изображений для перевода через программу
- выбор языка оригинала и перевода
- автоматическое определение текста
- автоматическое определение областей баблов
- клининг исходного текста на изображениях
- перевод обнаруженного текста
- выбор шрифта для нового текста
- добавление текста на изображение
- сохранение одного изображения
- сохранение комикса/манги целиком

[ ПОХОЖИЕ / АНАЛОГИЧНЫЕ ПРОДУКТЫ ]

**[Scan Translator](https://scan-translator.com/ru)**

Часто неправильно распознает области с текстом. Вместо удаления старого и добавления нового текста поверх, оно накладывает белый прямоугольник с текстом, что выглядит неаккуратно и нарушает содержание страницы.

**[ogkalu2, comic-translate](https://github.com/ogkalu2/comic-translate)**

Сложный процесс установки и запуска приложения и конфлиты в зависимостях (например, как в [Issue #22](https://github.com/ogkalu2/comic-translate/issues/22)). Требуется получать сообественный ключ для API платных сервисов по переводу.

[ ИНСТРУМЕНТЫ РАЗРАБОТКИ ]

1. Язык програмирования Python и следующие библиотеки:

   - OpenCV
   - PyQt6
   - PIL
   - другие, перечисленные в `requirements.txt`

2. Редактор кода Visual Studio Code

[ ЭТАПЫ РАЗРАБОТКИ ]

1. Разработка пользовательских сценариев
2. Проектирование интерфейса
3. Написание кода для выбора файла изобржения
4. Написание кода для обнаружения текста и области баблов
5. Написание кода для автоперевода манги
6. Написание кода для клининга и добавления текста
7. Написание кода для сохранения полученных изображений
8. Создание графического приложения
9. Тестирование, отладка
10. Подготовка проекта к защите

[ ВОЗМОЖНЫЕ РИСКИ ]

- Сложности и низкая точность библиотеки для распознования текста, особенно при работе с японским языком
- Долгое выполнение программы
- Нехватка времени на изучение материала и написание кода
