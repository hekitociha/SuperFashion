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
![TPkXSadEZ8Y](https://github.com/hekitociha/SuperFashion/assets/145964627/863d13bc-efd5-46d5-9e50-e70fa7620163)

### Диаграмма вариантов использования
![image](https://github.com/hekitociha/SuperFashion/assets/145964627/8a69661f-d1b2-4a61-911e-b0e927481089)

### Диаграмма классов
![SuperFashion-CD2](https://github.com/hekitociha/SuperFashion/assets/57916157/d06b3b9f-3359-409c-8243-dd2f36965252)

### ER-диаграмма (схема базы данных)
![SuperFashion-ER2](https://github.com/hekitociha/SuperFashion/assets/57916157/6cbb1f8a-6fc9-4fed-a0db-95ba9845ca4a)


### Взаимодествия пользователя с системой

Пользователь запускает Telegram бота. 
Под набором текста ему доступны всплывающие подсказки: 
«Каталог», «Корзина», «Заказы», «Новости», «Настройки», «Помощь». 
Выбирая вкладку «Каталог», в присланном сообщении для пользователя становятся доступны ячейки с одеждой:
«Верхняя одежда», «Костюмы», «Купальники», «Брюки/шорты/юбки», «Рубашки/топы», «Платья», «Комбинезоны». Выбирая нужную для пользователя ячейку, ему присылается новое сообщение с фирмами производителя, которые так же находятся в ячейках. Далее, при выборе нужной фирмы, пользователю присылается фотография выбранной одежды с указанием размера в соответствующих ячейках, которую должен выбрать пользователь. После окончательного выбора информация о заказе попадает в главную выкладку «Корзина».

Переходя во вкладку «Корзина», пользователю показывается в сообщении информация о заказе и появляется кнопка «Оплатить». Нажав на нее, пользователь указывает номер карты и адрес доставки. Нажав всплывающую кнопку «Закончить оплату», пользователь подтверждает номер карты и адрес доставки.

### Атрибуты качества:

- Производительность: время реакции на пользовательские действия 3 секунды
- Удобство и простота использования: интуитивна понятна, есть голосовые подсказки.
- Безопасность

### Ограничения:

- Интернет-платежи могут выполняться только банковскими картами
- Если оплата не произведена в течение 30 дней, то информация о заказе удаляется

### Бизнес-требования:

- Отправление заказа осуществляется только после 100% оплаты
- Доставка осуществляется средствами аутсорса
- Доставка заказа оплачивается дополнительно по тарифам компаний, осуществляющих доставку

![image](https://github.com/hekitociha/SuperFashion/assets/145964627/8ccd42ff-16fd-4e66-ab50-4cc861face43)
![image](https://github.com/hekitociha/SuperFashion/assets/145964627/29f4ef04-037f-49c6-9db7-27057cccd910)

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
    Время загрузки бота SuperFashion не должно превышать 3 секунды при скорости интернет-соединения 30 Мбит/с.

5. **Надежность**

    Вероятность работы магазина без сбоев в течение определенного периода времени.
    Вероятность сбоя системы SuperFashion не должна превышать 0.5% за месяц.

6. **Устойчивость**

    Способность системы восстанавливаться после сбоев и сохранять работоспособность.
    При возникновении ошибок при оформлении заказа, система SuperFashion должна сохранить все данные о заказе пользователя.

7. **Требования к защите**

    Системные меры, направленные на предотвращение вреда для пользователей и их данных.
    SuperFashion должен предоставлять возможность просмотра состава товаров, выделяя особо те компоненты, которые могут вызывать аллергические реакции.
    Все данные, передаваемые при обработке платежей, должны быть зашифрованы с использованием алгоритма шифрования SHA256 для предотвращения несанкционированного доступа.


### Внутренние

1. **Эффективность**

    Способность системы использовать ресурсы (процессор, диск, память, пропускная способность соединения) эффективно.
    SuperFashion должен минимизировать время обработки запросов покупателей до 500мс для оптимизации использования серверных ресурсов.

2. **Возможность модификации**

    Уровень простоты внесения изменений в дизайн и код магазина.
    100% используемых библиотек и интеграций должны быть поддерживаемыми и обновляемыми, чтобы обеспечить совместимость с последними версиями и 
    исправлениями безопасности.

3. **Возможность повторного использования**

    Способность программных компонентов магазина быть использованными повторно в других приложениях.
    Не менее 80% функциональности бота должны быть реализованы в виде модулей или библиотек, которые можно повторно использовать в других проектах.

4. **Масштабируемость**

    Способность магазина обслуживать большее количество пользователей и данных без ухудшения производительности.
    Бот должен поддерживать не менее 10,000 одновременных пользователей без снижения производительности. При увеличении числа пользователей до 100,000, бот 
    должен сохранять время отклика менее 1 секунды.

5. **Проверяемость**

    Легкость проверки программных компонентов на соответствие функциональным требованиям.
    Каждый модуль и основные функциональные блоки бота должны иметь 100% покрытие unit-тестами.
    Не менее 80% всех unit-тестов должны автоматически выполняться как часть процесса сборки и тестирования.


