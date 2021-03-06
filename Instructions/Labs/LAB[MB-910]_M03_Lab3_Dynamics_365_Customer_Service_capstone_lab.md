---
lab:
    title: 'Лабораторная работа 3.3. Итоговая работа по Dynamics 365 Customer Service'
    module: 'Модуль 3. Изучение основ Dynamics 365 Customer Service'
---

Модуль 3. Изучение основ Dynamics 365 Customer Service
========================

## Практическая лабораторная работа 3.3. Итоговая работа по Dynamics 365 Customer Service

## Сценарий лабораторной работы

Компания ABC специализируется на производстве, продаже, установке и обслуживании охранного оборудования. В число ее продуктов входят как внутренние, так и наружные камеры видеонаблюдения, датчики влажности и огня, услуги мониторинга и многое другое. 

Компания ABC использует приложения Dynamics 365 для взаимодействия со всеми своими клиентами в различных областях своей деятельности — от продаж до обслуживания. 

**Продажи и маркетинг**

Компания ABC продает товары своим бытовым клиентам напрямую через целевые маркетинговые кампании. Клиенты выбираются с учетом их города и других факторов. Маркетинговые материалы направляются по электронной почте и соответствующим образом корректируются я в зависимости от результатов такой рассылки. 

Хотя некоторые из небольших продуктов продаются через розничных продавцов, основная часть продается напрямую потребителям внутренними менеджерами по продажам.

Усилия таких менеджеров по продажам сосредоточены на двух ключевых областях: 

- **Бытовые клиенты.** Бытовые клиенты обычно ищут либо отдельные компоненты, либо покупают решение для дома целиком. Эти циклы продаж обычно короче и проистекают из социальных сетей, веб-сайтов, от рекомендателей или прямого контакта с перспективным клиентом. Поскольку бытовых клиентов обычно больше интересуют конкретные продукты или небольшие установки, их циклы продаж обычно длятся несколько дней или недель. 

- **Корпоративные клиенты.** Продавцы корпоративного сектора ориентируются на клиентов, которым требуются более специализированные и индивидуальные бизнес-решения. Корпоративные продажи обычно охватывают несколько объектов, связанных системами коммуникации и часто требуют нескольких ресурсов для завершения проекта. Эти циклы продаж обычно длиннее и имеют гораздо больше составных частей. 

Важно, чтобы все продавцы компании ABC независимо от области их работы располагали необходимыми инструментами, ресурсами и указаниями для осуществления продаж клиентам. 

**Установка системы.**

Процесс установки проданного охранного оборудования зависит от типа клиента, который его приобрел. 

- **Бытовые клиенты.** Поскольку установка в жилых помещениях обычно занимает меньше дня, ей занимаются сотрудники компании. После совершения продажи создается заказ на работу, и определяется квалифицированный специалист, который должен выполнить установку. 

- **Корпоративные клиенты.** Развертывание на предприятии может занять несколько месяцев, и для этого требуется менеджер проекта, который будет контролировать повседневные операции. Это включает в себя составление планов проекта, определение проектных групп и планирование ресурсов. 

**Обслуживание и поддержка.**

После установки системы компания ABC предоставляет поддержку после продажи. Если у клиента возникает проблема, он может обратиться в службу поддержки. Агент попытается помочь клиенту удаленно, чтобы решить эту проблему. Если проблема не может быть решена удаленно, агент поддержки может эскалировать ее в виде заказа на работу, который будет запланирован и обработан квалифицированным выездным техником. 

## Цели

Часто клиенты могут столкнуться с проблемами со своим оборудованием. Когда возникают проблемы, о них сообщают в службу поддержки компании ABC. О проблемах можно сообщить разными способами. В некоторых случаях оборудование может проактивно сообщать о проблемах. При поступлении сообщений о проблемах операторы пытаются решить их удаленно. Если им это не удается, для решения проблемы направляется выездной техник. В последнее время вы чинили множество датчиков, вышедших из строя. Вы заметили, что это связано с ошибкой в программном обеспечении. Вы хотите создать статью знаний, на которую смогут ссылаться другие операторы, когда столкнутся с такой же проблемой. 

Как оператор службы поддержки, вы несете ответственность за работу над проблемами, о которых сообщают клиенты. Недавно вы приняли звонок от Пайпер Смит. Она сообщила, что один из датчиков в ее системе не работает. Вам нужно зарегистрировать звонок Пайпер и попытаться найти решение ее проблемы. 

По завершении этого задания вы выполните следующие задачи:

- Создание статьи базы знаний 

- Управление обращениями с помощью Центра обслуживания клиентов.

- Создание и регистрация обращения. 

- Управление обращением на протяжении его жизненного цикла. 

## Для выполнения работы вам понадобится следующее.

  - **Ориентировочное время выполнения работы**: 45 мин

## Инструкции

## Упражнение 1. Создание и публикация статьи базы знаний

### Задание 1. Создание статьи базы знаний

1. Откройте приложение **Dynamics 365 Customer Service Hub**, если оно еще не открыто. 

2. Используя навигацию в левой части экрана, выберите **Статьи базы знаний**. 

3. Чтобы легко увидеть, какие статьи находятся на разных этапах, щелкните стрелку раскрывающегося списка рядом с **Мои активные статьи**. 

4. Выберите **Черновики статей**. 

5. Используйте выбор представления, чтобы выбрать **Утвержденные статьи**.  

6. С помощью выбора представления вернитесь в раздел **Мои активные статьи**

7. На **панели команд** нажмите кнопку **Создать**. После открытия новой записи щелкните стрелку раскрывающегося списка рядом с полем **Причина состояния** в заголовке записи вверху. Задайте для параметра **Язык** значение **Английский - США**.

8. Заполните статью следующим образом:

	- **Заголовок:** Датчик не работает — Ваши инициалы

	- **Ключевые слова:** Датчик, поврежден, не работает

	- **Описание:** Помогает проработать сценарии, в которых датчик не работает. 

9. Введите следующий текст в **конструкторе содержимого**.   

	Датчик в данный момент не работает

	Если датчик не работает должным образом, сделайте следующее:

	1. Найдите и замените батарейки в устройстве. 

	2. Нажмите и удерживайте кнопку питания в течение 3 секунд. 

	3. Устройство откроется в режиме администратора. 

	4. Нажмите и удерживайте кнопку сопряжения, пока индикатор не изменит цвет с красного на синий. 

	5. Нажмите кнопку перезагрузки. 

	После перезагрузки устройство снова будет работать. 

10. В редакторе содержимого выберите текст «Датчик в данный момент не работает».

11. Измените размер шрифта на **22** и нажмите кнопку **Полужирный**. 

12. На **панели команд** нажмите кнопку **Сохранить**, чтобы сохранить статью базы знаний и оставить ее открытой. 

13. В разделе **Новый процесс**, выберите этап **Автор** и в поле **Тема статьи** установите значение **Обслуживание**. 

14. Установите для поля **Пометить для рецензирования** значение **Завершено**.

15. Нажмите кнопку **Следующий этап**, чтобы перейти к этапу **Рецензирование**.

16. На **панели команд** нажмите кнопку **Сохранить и закрыть**, чтобы сохранить изменения и закрыть статью.

 

### Задание 2. Управление статьей в процессе утверждения

В большинстве организаций после того, как автор статьи создает запись, она проходит процесс утверждения, прежде чем будет опубликована. Как правило, это делает другой человек. В данном случае в роли утверждающего выступим мы. 

1. В разделе «Статьи базы знаний» переключитесь на представление **Предлагаемые статьи**, чтобы увидеть, какие статьи требуют вашего утверждения. 

2. Откройте статью **Датчик не работает — Ваши инициалы**, которую вы только что создали.

3. В разделе **Новый процесс**, выберите этап **Рецензирование**. Установите для поля **Рецензирование** значение **Отклонено**.

4. На экране «Отклонение статьи базы знаний» введите текст **Эти меры не работают, когда я пытаюсь воспроизвести их**.

5. Нажмите кнопку **Отклонить**

6. Нажмите кнопку **Сохранить и закрыть**, чтобы вернуться к записи статьи.

7. С помощью **выбора представления** измените представление на **Мои активные статьи**. 

8. Откройте запись статьи **Датчик не работает — Ваши инициалы**.

9. Когда запись будет открыта, выберите вкладку **Сводка**. 

10. На **временной шкале** записи обратите внимание на примечание, в котором указано, что статья была отклонена и почему она была отклонена. 

11. Перейдите на вкладку **Содержимое**.

12. В поле **Содержимое** установите курсор перед словом **Нажать** на шаге 5. 

13. Нажмите клавишу **ВВОД**. 

14. Введите текст «Нажмите кнопку подтверждения». 

15. На **панели команд** нажмите кнопку **Сохранить и закрыть**.

16. С помощью **выбора представления** измените представление на **Предлагаемые статьи**.

17. Откройте статью **Датчик не работает — Ваши инициалы**. 

18. В разделе **Новый процесс** потока бизнес-процесса выберите этап **Рецензирование**.

19. Измените Статус на **Утверждено**. 

20. Вам будет предложено подтвердить утверждение статьи, нажмите **OK**. 


### Задание 3. Утверждение статьи базы знаний

Теперь, когда статья утверждена, мы опубликуем ее, чтобы она была доступна людям, работающим с обращениями. 

1. Нажмите кнопку **Следующий этап**, чтобы перейти к этапу **Публикация**. 

2. Пометьте параметр **Задать связи с продуктами** как **Завершено**. 

3. Установите **дату окончания срока действия** на **один год от сегодняшнего дня в 00:00**. 

4. Нажмите кнопку **Разрешить**, чтобы завершить процесс. 

5. На **панели команд** статьи нажмите кнопку **Опубликовать**. 

6. Убедитесь, что выбрано следующее:

	- **Опубликовать:** Сейчас

	- **Статус публикации:** Опубликовано

	- **Дата окончания срока действия:** Один год от сегодняшнего дня в 00:00

	- **Состояние истечения срока действия:** Просрочено

	- **Состояние истечения срока действия:** Просрочено

7. Нажмите кнопку **Опубликовать**, чтобы опубликовать статью.


## Упражнение 2. Управление обращением в службу поддержки на протяжении его жизненного цикла


### Задание 1. Создание обращения и управление им

1. Откройте приложение **Dynamics 365 Customer Service Hub**, если оно еще не открыто. 

2. Используя навигацию в левой части экрана, выберите **Панели мониторинга**. Откроется панель мониторинга **уровня 1**. 

3. На **панели команд** нажмите кнопку **Показать визуальный фильтр**.


4. Дополнительные панели мониторинга предоставляют более подробную информацию о текущей загрузке обращений. Вы можете работать с другими панелями мониторинга, используя выбор панели мониторинга. Измените панель мониторинга с **панели мониторинга уровня 1** на **панели мониторинга уровня 2**. 

 

Теперь, когда вы знакомы с некоторыми из различных представлений и панелей мониторинга, мы создадим новую запись обращения, чтобы помочь Пайпер с ее проблемой.

 

10. Используя навигацию в левой части экрана, выберите **Обращения**. 

11. На **панели команд** нажмите кнопку **Создать**, чтобы создать новую запись обращения.

12. Заполните новую запись обращения следующим образом:

	- **Заголовок обращения:** Датчик не работает — Ваши инициалы

	- **Клиент:** Пайпер Смит

	- **Происхождение:** Телефон

	- **Описание:** Пайпер сообщила, что один из датчиков в ее системе не работает. 

13. Нажмите кнопку **Сохранить**, чтобы сохранить запись и оставить ее открытой. 

14. На **временной шкале записи**, нажмите **значок плюса**, чтобы создать новое действие. 

15. В появившемся меню выберите пункт **Телефонный звонок**.

16. Заполните форму **Быстрое создание: Телефонный звонок** следующим образом:

	- **Тема:** Обратный звонок Пайпер

	- **Направление:** Исходящий

	- **Номер телефона:**  888 555-1762

	- **Продолжительность:** 15 мин

17. Нажмите кнопку **Сохранить и закрыть**. 

18. В разделе **Преобразование звонка в обращение**, выберите этап **Определение**.

19. Нажмите кнопку **Следующий этап**, чтобы перейти к этапу **Исследование**. 

20. Выберите **X** в раскрывающемся окне этапа **Исследование**, чтобы удалить окно и продолжить работу. 

21. На **временной шкале записи**, нажмите **значок плюса**, чтобы создать новое действие. 

22. В появившемся меню выберите пункт **Задание**.

23. Заполните форму **Быстрое создание: Телефонный звонок** следующим образом:

	- **Тема:** Исследование проблемы Пайпер

	- **Описание:** Использование базы знаний для исследования проблемы Пайпер. 

	- **Продолжительность:** 30 мин

24. Нажмите кнопку **Сохранить и закрыть**. 

25. В правой части экрана обращения найдите и выберите значок книги **знаний**. (Он будет прямо под значком гаечного ключа).

26. Обратите внимание, что название обращения автоматически используется в качестве текста для поиска. Найдите и откройте статью **Датчик не работает — Ваши инициалы**, которую ранее создали. 

27. Отобразится полное содержание статьи. Выберите значок **Нравится**, чтобы отметить, что статья была полезной. 

28. Выберите значок **Связать эту статью с текущей записью**. Убедитесь, что отображается текст **Связано с обращением**. 

 

### Задание 2. Закрытие обращения

Теперь, когда мы определили решение проблемы клиентов, мы будем готовы разрешить обращение. Первый шаг в закрытии обращения — закрыть все связанные с ним открытые действия. 

1. На **временной шкале** записи обращения наведите курсор на задачу **Исследование проблемы Пайпер**, которую создали ранее**.** Выберите **значок закрытия действия**, чтобы завершить действие. 

2. На экране **Закрыть задачу** убедитесь, что для состояния установлено значение «Завершено» и нажмите кнопку **Закрыть**. В статусе задачи должно быть написано **Закрыто**. 

3. Наведите курсор на созданный ранее телефонный звонок **Обратный звонок Пайпер****.** Выберите **значок закрытия действия**, чтобы завершить действие. 

4. На экране **Закрыть звонок** убедитесь, что для **состояния** установлено значение **Завершено**, а для **статуса** — **Выполнено**. Нажмите кнопку **Закрыть**. Убедитесь, что на временной шкале действие отображается как закрытое. 

5. В разделе **Преобразование звонка в обращение** выберите этап **Исследование** и выберите **Следующий этап**, чтобы перейти к этапу **Разрешение**. 

6. На этапе **Разрешение** нажмите кнопку **Готово**, чтобы завершить процесс. 

7. На **панели команд** обращения нажмите кнопку **Разрешить обращение**.

8. В окне **Разрешить обращение** установите в поле **Разрешение** значение **Статья базы знаний**. 

9. Убедитесь, что в полях **Общее время** и **Оплачиваемое время** установлено значение **45 минут** (это общее время, затраченное на действия по осуществлению телефонного звонка и задачи, добавленные в запись). 

10. Нажмите кнопку **Разрешить**, чтобы завершить процесс. 

