# Облачные платформы как основа технологического предпринимательства

Отчёты по лабораторным работам Университета ИТМО за 2026/2027 учебный год.

| Поле | Значение |
| --- | --- |
| Автор | Agadilova Malika |
| Группа | U4225 |
| Университет | [ITMO University](https://itmo.ru/ru/) |
| Факультет | [FICT](https://fict.itmo.ru) |
| Курс | [Cloud platforms as the basis of technology entrepreneurship](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship) |
| Учебный год | 2026/2027 |

## Лабораторные работы

| № | Работа | Отчёт | Статус |
| --- | --- | --- | --- |
| 1 | Обзор Google Cloud и исследование основных сервисов | [lab1_report.md](lab1/lab1_report.md) | Защищена |
| 2 | Исследование Cloud Run | [lab2_report.md](lab2/lab2_report.md) | Отчёт подготовлен; сервис удалён |
| 3 | Исследование Cloud Storage | [lab3_report.md](lab3/lab3_report.md) | Не начата |
| 4 | Разработка инфраструктуры MVP AI приложения | [lab4_report.md](lab4/lab4_report.md) | Не начата |

Каталоги подготовлены для четырёх работ, перечисленных в [основном списке лабораторных курса](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship/blob/main/docs/education/labs.md). Файлы ЛР3–ЛР4 содержат заготовки шапок для последующего заполнения.

## Структура репозитория

```text
.
├── .gitignore
├── LICENSE
├── README.md
├── lab1/
│   ├── images/                 # Скриншоты выполнения ЛР1
│   └── lab1_report.md
├── lab2/
│   ├── images/                 # Скриншоты выполнения ЛР2
│   └── lab2_report.md
├── lab3/
│   └── lab3_report.md
└── lab4/
    └── lab4_report.md
```

## Замечания по выполнению

В ЛР1 после замены роли `Storage Admin` на `Compute Viewer` повторное скачивание файлов из `lab1-bucket-itmo` завершилось успешно. Анонимный запрос к `pic1.jpg` вернул HTTP `200`, а настройки бакета показали разрешения для публичных групп. Исследование этой особенности и результаты проверок приведены в отчёте.

В ЛР2 стандартный контейнер Hello продолжил работать после смены порта с `8080` на `8090`. Проверены переключение трафика между ревизиями с тегами `ver1` и `ver2` и распределение 50/50. При повторных сериях запросов обнаружены ответы `429`; их анализ и ограничения диагностики включены в отчёт. Сервис удалён после подготовки отчёта.

Отчёты оформляются в Markdown, изображения хранятся рядом с соответствующей работой. Поле `Date of create` обозначает дату начала работы, а `Date of finished` заполняется датой защиты перед преподавателем.

## Материалы курса

- [Репозиторий дисциплины](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship).
- [Правила оформления и защиты отчётов](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship/blob/main/docs/education/labs2023-2024/reportdesign.md).
- [Задание ЛР1](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship/blob/main/docs/education/labs2023-2024/lab1/lab1.md).
- [Задание ЛР2](https://github.com/ex-itmo-ict-faculty/cloud-platforms-as-the-basis-of-technology-entrepreneurship/blob/main/docs/education/labs2023-2024/lab2/lab2.md).

## Лицензия

Материалы этого репозитория распространяются по [лицензии MIT](LICENSE).
