# Разработка базы данных и приложения для управления данными посетителей санатория
## Стек:
* Microsoft Visual FoxPro 9.0
* Erwin Data Modeler
## Основные цели:
Целью проекта является разработка прикладного программного обеспечения для санаториев, позволяющего посетителям отслеживать и изменять свои личные данные и медицинскую информацию. Программа предоставляет функционал для регистрации, авторизации, просмотра и редактирования информации, а также подсчета количества людей с одинаковыми диагнозами.

## Данные:
Используется база данных, созданная с помощью Microsoft Visual FoxPro 9.0. Основные таблицы:

* Visitors: Личные данные посетителей.
* Med_info: Медицинская информация, включая диагнозы и аллергии.
* Diagnosis: Справочник диагнозов.
* Diet: Справочник диет с калорийностью.
* Vitamins: Справочник витаминов.
* Food: Справочник продуктов с питательными веществами.
* Diet_vitamins, Diets_food: Связующие таблицы для диет и продуктов, витаминов.
## Этапы работы:
### Проектирование базы данных:
Использована логическая и физическая модели ERWIN. Были разработаны таблицы для хранения информации о посетителях, их медицинских данных, диагнозах, диетах и витаминах.

### Интерфейс:
Приложение включает несколько форм:

* Авторизация: Пользователь может войти в систему или зарегистрироваться.
* Меню: Основное меню, с кнопками для изменения данных, получения отчетов, подсчета людей с одинаковым диагнозом.
* Изменение данных: Форма для редактирования личных данных и медицинской карты.
* Отчеты: Генерация отчетов по личным данным и медицинской информации.
### Логика работы:
При авторизации проверяется наличие пользователя в базе данных. Если данные корректны, происходит вход в систему.
Пользователь может зарегистрироваться, добавив свои данные в таблицы посетителей и медицинской информации.
Для изменения данных предусмотрены формы с возможностью редактирования информации о посетителе и его диагнозах.
В разделе отчетов можно выводить данные о личных данных посетителя и его медицинской карте.
## Результаты:
Проект показал, как с помощью баз данных можно эффективно управлять информацией о посетителях санатория. Благодаря разработке приложения были получены знания в области проектирования баз данных, а также практические навыки в работе с СУБД и создании прикладных программ.