# DLE Billing

![Version](https://img.shields.io/badge/Version-0.9.2-blue.svg?style=flat-square "Version")
![DLE](https://img.shields.io/badge/DLE-13.0+-green.svg?style=flat-square "DLE")
![PHP](https://img.shields.io/badge/PHP-8+-blue.svg?style=flat-square "PHP")
![Charset](https://img.shields.io/badge/Charset-utf--8-red.svg?style=flat-square "Charset")
![jQuery](https://img.shields.io/badge/jQuery-3.0+-yellow.svg?style=flat-square "jQuery")

Платежный модуль и биллинг платформа для cms dle - автоматизирует продажи и работу с пользователями сайта.

![](https://dle-billing.ru/assets/images/NW4MjIMUQ5.gif)

## Разработка и поддержка
- mr_Evgen (evgeny.tc@gmail.com)
- Japing (https://github.com/Japing/DLE-Billing)

[[dle-billing.ru](https://dle-billing.ru/ "dle-billing.ru")] [[техподдержка](https://dle-billing.ru/support/index.php?a=add)] [[документация](https://dle-billing.ru/doc/)]

[![](https://dle-billing.ru/img/donate3.png)](https://yoomoney.ru/fundraise/RKcDogSR19k.230521)

## Принять участие

[[contributing](https://github.com/evgeny-tc/dle-billing-module/blob/main/CONTRIBUTING.md)]
[[issues](https://github.com/evgeny-tc/dle-billing-module/issues)]

## Установить
1. [Загрузить](https://github.com/evgeny-tc/dle-billing-module/releases/download/beta-10-06/archive.zip "Скачать архив")  архив с модулем / [другие версии](https://github.com/evgeny-tc/dle-billing-module/releases)
2. **Панель управления** -> **Утилиты** -> **Управление плагинами** - загрузить скачанный архив
3. Открыть страницу ваш_сайт.ру/admin.php?mod=billing и запустить установщик

## Обновить
1. Обновите модуль через систему плагинов
2. Войдите в админ.панель модуля для автоматического обновления бд и конфигурации модуля.

## Плагины
- Перевод средств между пользователями
- Запросы вывода средств с баланса
- Платный переход в группу
- Пожертвования
- Фиксация новостей
- Оплата контента
- Бонусы
- Промокоды
- Реферальная программа
- Формы

## Платежные агрегаторы
- Payok.io
- ЮMoney
- PayAnyWay
- Робокасса
- LiqPay
- Free-Kassa
- Tegro.money
- Интеркасса
- enot.io

## API
Для разработчиков - [документация](https://dle-billing.ru/doc/api "документация").

## Журнал изменений
### v.0.9.2 (30.08.2023)
- Добавлены купоны, дающие скидку на оплату услуг
- Плагин Возврат средств - добавлен статус заявки "Отменен"
- Исправлена ошибка в плагине оплаты скрытого текста при использовании параметра "Описание платежа"
- Другие исправления и улучшения
### v.0.9 (09.08.2023)
- Новая панель управления плагинами
- Добавлены настройки: Главная страница ПУ и Время жизни квитанции
- Добавлен плагин - Формы
- Исправлена ошибка в платежной системе Free-kassa
- Другие исправления и улучшения

### v0.8.7.beta (21.06.2023)
- Оплата скрытого текста - добавлен вывод описания платежа в список оплаченных доступов (теги [pay_desc] {pay_desc} [/pay_desc], [not_pay_desc] ... [/not_pay_desc])
- Оплата скрытого текста: добавлена возможность динамически указывать описание платежа для каждого тега; код закрытого тега может быть указан непосредственно в шаблоне с контентом, т.е. в нем можно использовать штатные теги dle.
- Робокасса - добавлена передача фискальных данных
- добавлена интеграция с платежным агрегатором AnyPay
- обновлен раздел статистики
- исправление багов

### v0.8.beta (20.05.2023)
- Модуль полностью переведен на PHP 8 и выше
- Обновлены и добавлены в модуль некоторые плагины
- Добавлена возможность прямой оплаты услуг, в обход баланса
- Добавлена возможность оплаты некоторых услуг неавторизованным пользователям

### v0.7.6 (24.02.2023)
- Исправление багов

### v0.7.5 (20.02.2023)
- Адаптирован для DLE 16.0
- Поддерживает PHP 8.*

### v0.7.4 (25.08.2019)
- Модуль полностью адаптирован к системе плагинов.
- В личный кабинет пользователя добавлен раздел **«Квитанции»**, в котором отображается список всех квитанций.
- В настройках модуля добавлен новый пункт, указывающий максимальное количество неоплаченных квитанций которые может создать пользователь.
- В личный кабинет пользователя добавлена возможность удалять неоплаченные квитанции.
- Исправлена ошибка при отображении статистики в админ панель модуля.
- Изменён принцип создание новых квитанций: теперь создается квитанция и её можна оплачивать любой платежной системой.

### v0.7.3 (06.06.2019)
- Модуль адаптирован под DLE 13.0 и выше .
- Изменены иконки в админ панель модуля.
