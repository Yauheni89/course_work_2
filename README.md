# Поиск вакансий с сайта HH.ru

## Установка
Копирование проекта к себе:
```commandline
git@github.com:Yauheni89/course_work_2.git
```
В проекте используется poetry, поэтому для установки используйте:
```commandline
poetry istall
```

# Работа поисковика
Для запуска программы наберите в консоли:
```commandline
python main.py
```
## Требования к реализации

- [✔] Создать абстрактный класс для работы с API сервиса с вакансиями. Реализовать класс, наследующийся от абстрактного класса, для работы с платформой hh.ru. Класс должен уметь подключаться к API и получать вакансии.
- [✔] Создать класс для работы с вакансиями. В этом классе самостоятельно определить атрибуты, такие как название вакансии, ссылка на вакансию, зарплата, краткое описание или требования и т. п. (всего не менее четырех атрибутов). Класс должен поддерживать методы сравнения вакансий между собой по зарплате и валидировать данные, которыми инициализируются его атрибуты.
- [✔] Определить абстрактный класс, который обязывает реализовать методы для добавления вакансий в файл, получения данных из файла по указанным критериям и удаления информации о вакансиях. Создать класс для сохранения информации о вакансиях в JSON-файл. Дополнительно, по желанию, можно реализовать классы для работы с другими форматами, например с CSV- или Excel-файлом, с TXT-файлом.
- [✔] Создать функцию для взаимодействия с пользователем. Функция должна взаимодействовать с пользователем через консоль.
- [✔] Объединить все классы и функции в единую программу.
- [✔] Покрыть описанный функционал тестами(Покрыто частично)

## Требования к реализации в парадигме ООП

- [✔] Абстрактный класс и классы для работы с API платформ с вакансиями должны быть реализованы в соответствии с принципом наследования.
- [✔] Класс для работы с вакансиями должен быть реализован в соответствии с принципом инкапсуляции и поддерживать методы сравнения вакансий между собой по зарплате.
- [✔] Классы и другие сущности в проекте должны удовлетворять минимум первым двум требованиям принципов SOLID.


