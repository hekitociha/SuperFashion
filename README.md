# SuperFashion
Интернет-магазин одежды в Telegram.

### Команда
1. [Ярослав Голубев](https://github.com/Rubix327)
2. [Павел Чувикин](https://github.com/pavell85598)
3. [Даниил Климов](https://github.com/Dudergov365)
4. [Арсений Бутенко](https://github.com/arsenybut) Лидер, капитан, наш проводник в мир моды!!
5. [Полина Голубева](https://github.com/golubinkaa)
6. [Мочалова Юлия](https://github.com/MochalovaYulia)
7. [Никита Чернов](https://github.com/hekitociha) Русский хакер, живущий в Майами. Лицо проекта)

### Назначение системы
Продажа предметов одежды через мессенджер Telegram.

### Цели
**Цель проекта**: обеспечить создание бота для магазина одежды внутри мессенджера Telegram.

**Бизнес-цели:**
 - _Краткосрочная_: разработать основной функционал бота и открыть доступ к боту на широкую аудиторию до 31.06.2024;
 - _Долгосрочная_: привлечь первых 500 уникальных пользователей в бота и достичь первых 50 покупок до 31.07.2024.

### Список заинтересованных сторон

**Демографический:**

- _Пол_: сервис будет нацелен как на мужчин, так и на женщин, предоставляя им возможность выбора одежды в соответствии с их предпочтениями и потребностями.
- _Возраст_: основной акцент будет сделан на молодежь (18-30 лет), так как они чаще проявляют интерес к модным трендам и онлайн-покупкам. Однако, предложения также будут доступны для взрослых (31-50 лет) и пожилых (51+ лет) пользователей.

**Географический:**

- _Городское население и регион_: поскольку бот будет работать через платформу Telegram, для использования необходимо интернет-подключение и доступ к этой платформе. На данном этапе реализация функций бота будет работать только если пользователь укажет город Иваново.

**Социально-экономический:**

- _Уровень дохода_: бот будет предлагать различные ценовые категории, чтобы удовлетворить потребности пользователей с разным уровнем дохода.
- _Образование и род деятельности_: разнообразие предложений поможет удовлетворить запросы студентов, офисных работников, фрилансеров и других категорий пользователей с разным образованием и видами деятельности.

**Поведенческий:**

- _Метод покупки_: пользователи смогут оформить онлайн-покупку прямо через бота.
- _Брендовая преданность_: бот будет предоставлять информацию о различных брендах и помогать пользователям найти товары именно тех марок, которым они предпочитают.

**Психографический:**

- _Лайфстайл_: бот будет предлагать одежду и аксессуары, соответствующие разным стилям жизни, включая активный отдых, офисные занятия и культурные мероприятия.
- _Ценности и интересы_: пользователи смогут выбирать товары, отвечающие их ценностям, таким как качество, а также учитывать их интересы, такие как спорт, искусство или путешествия.
- ![image](https://github.com/hekitociha/SuperFashion/assets/145964627/948f3677-0bdf-4804-bd4d-05142dca1e58)


### Бизнес-процессы
![EPHEklZ5D1A](https://github.com/hekitociha/SuperFashion/assets/145964627/ff07d482-0895-4560-b935-2235b867c4d4)

### Контекстная диаграмма
![нпгнарпсртмор](https://github.com/hekitociha/SuperFashion/assets/165883704/901f232a-d179-416a-9e1b-9ebbd2780af0)

### Диаграмма вариантов использования
![image](https://github.com/user-attachments/assets/9e0b8de7-af90-47dd-b5cd-1d85ca09a591)

### Диаграмма классов
![SuperFashion-CD drawio](https://github.com/hekitociha/SuperFashion/assets/57916157/03d7a50c-c8ce-4926-915c-23a93acb72b4)

### ER-диаграмма №1
![SuperFashion ER (1)](https://github.com/hekitociha/SuperFashion/assets/57916157/24a81aa9-ec4a-473a-ac08-4a4b656df80d)

### ER-диаграмма №2
![SuperFashion-ER2](https://github.com/hekitociha/SuperFashion/assets/57916157/6e4d2279-a1b1-4bd5-a95c-a245b212d9ce)

### Диаграмма переходов состояний
![image](https://github.com/hekitociha/SuperFashion/assets/165883704/ff44d6d7-eb4b-4b82-a0d9-488620b0c137)

### Ограничения полей базы данных
![Ограничения полей бд](https://github.com/hekitociha/SuperFashion/assets/57916157/7c122252-def4-4aa0-b22b-36f76f03f318)

### Диаграмма последовательности
![Диаграмма последовательности](https://github.com/hekitociha/SuperFashion/assets/57916157/3091967d-aefc-4280-a292-b21734eda57f)

### Диаграмма деятельности
![image](https://github.com/hekitociha/SuperFashion/assets/165883704/a7308845-e249-4996-83db-e6e1962112ee)

### Взаимодествия пользователя с системой

Пользователь запускает Telegram бота. 
Под набором текста ему доступны всплывающие подсказки: 
«Каталог», «Корзина», «Заказы», «Новости», «Настройки», «Помощь». 
Выбирая вкладку «Каталог», в присланном сообщении для пользователя становятся доступны ячейки с одеждой:
«Верхняя одежда», «Костюмы», «Купальники», «Брюки/шорты/юбки», «Рубашки/топы», «Платья», «Комбинезоны». Выбирая нужную для пользователя ячейку, ему присылается новое сообщение с фирмами производителя, которые так же находятся в ячейках. Далее, при выборе нужной фирмы, пользователю присылается фотография выбранной одежды с указанием размера в соответствующих ячейках, которую должен выбрать пользователь. После окончательного выбора информация о заказе попадает в главную выкладку «Корзина».

Переходя во вкладку «Корзина», пользователю показывается в сообщении информация о заказе и появляется кнопка «Оплатить». Нажав на нее, пользователь указывает номер карты и адрес доставки. Нажав всплывающую кнопку «Закончить оплату», пользователь подтверждает номер карты и адрес доставки.

## Атрибуты качества

### Внешние

1. **Доступность**

    Процент времени, когда магазин SuperFashion доступен для использования и работоспособен.
    Система должна быть доступна для использования не менее чем на 95% времени в течение рабочих дней.

2. **Целостность**

    Уровень защиты от потери информации и сохранение корректности данных в системе.
    истема должна на 95% защищать от неточности и потери данных. После резервного копирования данных система должна проверить их целостность и 
    засвидетельствовать об отличиях, если они есть.

3. **Совместимость**

    Готовность системы к обмену данными с другими программными системами и интеграции с внешними устройствами.
    Бот должен корректно работать с платежной системой через Telegram.

4. **Производительность**

    Скорость реакции системы на запросы и действия пользователей.
    Время загрузки бота и обработки каждого запроса не должно превышать 3 секунды при скорости интернет-соединения 30 Мбит/с.

5. **Устойчивость**

    Способность системы восстанавливаться после сбоев и сохранять работоспособность.
    При возникновении ошибок при оформлении заказа, система SuperFashion должна сохранить все данные о заказе пользователя.

6. **Требования к защите**

    Системные меры, направленные на предотвращение вреда для пользователей и их данных.
    Все данные, передаваемые при обработке платежей, должны быть зашифрованы с использованием алгоритма шифрования SHA256 для предотвращения несанкционированного доступа.


### Внутренние

1. **Эффективность**

    Способность системы использовать ресурсы (процессор, диск, память, пропускная способность соединения) эффективно.
    Время обработки одного запроса покупателя на стороне сервера не должно превышать 500мс.

2. **Возможность модификации**

    Уровень простоты внесения изменений в дизайн и код магазина.
    100% используемых библиотек и интеграций должны быть поддерживаемыми и обновляемыми, чтобы обеспечить совместимость с последними версиями и 
    исправлениями безопасности.

3. **Масштабируемость**

    Способность магазина обслуживать большее количество пользователей и данных без ухудшения производительности.
    Бот должен поддерживать не менее 100 одновременных пользователей без снижения производительности. При увеличении числа пользователей до 1000, бот 
    должен сохранять время отклика менее 3 секунд.

4. **Проверяемость**

    Легкость проверки программных компонентов на соответствие функциональным требованиям.
    Каждый модуль и основные функциональные блоки бота должны иметь не менее 85% покрытие unit-тестами.


