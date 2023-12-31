# Техническое задание

## Цели разработки

Разрабатываемая CRM предназначена для учета клиентов, сделок и продаж клмпании с целью обеспечить структурированное хранение данных и дальнейший их анализ для выявления слабых и сильных сторон ведения бизнеса компании, оценки эффективности сотрудников, финансовых потоков от тех или иных клиентов компании.

Система должна поддерживать модульность, что позволяло бы в дальнейшем сторнонним разработчикам создавать свои компоненты, расширяющие возможность системы.


## Функциональные требования

### Ключевые сущности системы

#### Владелец - компания или группа компаний, ведущих учет сделок

#### Пользователь - сотрудники и клиенты

#### Сделка - заключение потенциального договора на оказание услуг или поставку товара между компанией владельца и клиента

### Какие действия могут совершаться в системе

Пользователи системы могут наделяться определенным набором прав, позволяющим осуществлять следующие действия:

* Аутентификация (вход в личный кабинет)
* Простмотр компаний и сделок
* Редактирование, создание и удаление компаний (компаний нутри одной группы или холдинга)
* Редактирование, создание и удаление клиентов
* Редактирование, создание и удаление сделок
* Редактирование, создание и удаление сотрудников
* Редактирование, создание и удаление статусов сделок
* Привязывать сотрудников компании к тем или иным компаниям и сделкам
* Настраивать систему (изменять отдельные настройки)

### Функциональные блоки

#### Аутентификация

К данному функциональному блоку относятся все процедуры и модули, отвечающие за вход пользователя в личный кабинет.

#### Авторизация

Модули системы, отвечающие за проверку и раздачу прав пользователя.

#### Редактирование пользователей (сотрудники и клиенты)

Модули системы, относящиеся к редактированию сотрудников компаний и клиентов. 

#### Сделки (сделки и статусы сделок)

Модули системы, относящиеся к редактированию сделок, статусов и механизмам проверки логикик статусов и их взаимных переходов.

#### Настройки системы

Общие настройки системы

#### Уведомления

Модуль системы, отвечающий за уведомление пользователей различными способами о событиях, происходящих в системе.

### Типы пользователей системы

#### Гость (анонимный пользователь)

Гость не имеет права входа в личный кабинет и пользование всеми вохможностями интерфейсами, отображаемыми в защищенном разделе сайта.

#### Системный администратор (пользователь с неограниченными правами)
* Может входить в личный кабинет при помощи своей учетной записи
* Имеет неограниченный наюор прав и может пользоваться всем доступным функционалом системы.

#### Сотрудник компании владельца
* Может входить в личный кабинет при помощи своей учетной записи
* Может наделяться определенным набором прав для управления (создания/редактирования/удаления) отдельными сущностями системы.

#### Сотрудник клиента

* Может входить в личный кабинет
* Имеет ограниченный набор прав на просмотр сделок, в которых он, непосредственно, задействован. 

### Доступные интерфейсы системы

#### Фронт часть - короткая презентационная страница

Общая информационная страница с описанием ключевых возможностей системы о способах приобретения, установке и разработчиках продукта.

#### Личный кабинет (защищенная часть сайта)
    1. Страница входа

    Страница ввода логина и пароля для входа в защищенную часть сайта (личный кабинет).

    2. Пользователи (клиенты и сотрудники)

    Данный интерфейс предназначен для просмотра всех учетных записей системы и карточек пользоввателей, их пренадлежности к тем или иным компаниям, а также к тем или иным сделкам.

    Данный интерфейс должен предоставлять возможность добавления/изменения/удаления пользователей (при наличии прав у текущего пользователя).
     
    3. Компании

    Данный интерфейс предоставляет следующие возможнотси:
        1. Добавление компании
        2. Редактирование компании
        3. Карточка компании (просмотр)
            1. Сотрудники компании
            2. Клиенты

    4. Сотрудники (пользователи и роли)
        1. Добавление сотрудника
        2. Редактирование сотрудника
        3. Карточка сотрудника (просмотр)
            1. _

    5. Клиенты
        1. Добавление клиента
        2. Редактирвание клиента
        3. Карточка клиента
            1. _

    6. Сделки
        1. Добавление
        2. Редактирование
        3. Карточка сделки (просмотр деталей)

    7. Настройки

## Требования к документации

Необходимо снабдить подробной документацией процесс создания сторонних дополнений к системе.

Необходимо предоставить подробное руководство пользователя (как обычного пользователя, так и администратора).


## Стадии и этапы разработки;
 
### Разработка технического задания

### Какие диаграммы интерфейсов

### Разработка прототипов интерфейсов

### Разработка дизайн-системы и сборка визуальных макетов интерфейса

### Верстка интерфейсов и фронтенд разработка

### Программирование серверной логики (бэкенд разработка)
 