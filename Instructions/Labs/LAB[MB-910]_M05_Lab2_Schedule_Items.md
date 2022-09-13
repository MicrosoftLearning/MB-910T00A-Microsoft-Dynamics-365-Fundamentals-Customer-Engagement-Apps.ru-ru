---
lab:
  title: Лабораторная работа 4.2. Планирование элементов в Dynamics 365 Field Service
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: ca0728e865cf16478ab84f160cf34538e521c91e
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/29/2022
ms.locfileid: "144405068"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Модуль 4. Изучение основ Dynamics 365 Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>Практическая лабораторная работа 4.2. Планирование элементов в Dynamics 365 Field Service

## <a name="lab-setup"></a>Исходные условия выполнения лабораторной работы

  - **Примерное время**: 20 минут

  **Примечание**. Панель «Требования к резервированию» не может быть открыта в браузере Internet Explorer. Используйте Microsoft Edge или Google Chrome для выполнения этого упражнения.
  
## <a name="instructions"></a>Инструкции

1.  Откройте приложение **Dynamics 365 Field Service**, если оно еще не открыто.  

2.  Используя навигацию в левой части экрана, выберите **Заказы на работу**.

3.  На **панели команд** нажмите кнопку **Создать**, чтобы создать новый заказ на работу.

4.  Заполните детали заказа на работу следующим образом:
    - Организация сервиса: ADatum Corporation
    - Тип основного инцидента: Не работает магнитно-резонансный томограф
    - Облагается налогом: Нет
    
5.  Нажмите **Сохранить и закрыть**, чтобы сохранить изменения и выйти из нового заказа на работу.

6.  На **панели команд** **заказа на работу** нажмите кнопку **Зарезервировать**.  Откроется **помощник по расписанию**.  

7.  Вам должны быть представлены варианты планирования элемента.  Выберите запись **Райана Брима**.

8.  В окне **Создать резервирование ресурса** установите **Время начала** на **начало следующего часа**.

9.  Установите **Время окончания** на 2,5 часа позже.  

10. Нажмите кнопку **Зарезервировать и выйти**, чтобы зарезервировать элемент и покинуть окно планирования.  

11. Вернувшись к заказу на работу, нажмите кнопку **Сохранить и закрыть** на **панели команд**.  

12. Используя навигацию в левой части экрана, выберите **Таблица расписаний**.

13. В нижней части экрана на панели требований выберите **Незапланированные заказы на работу**.

14. Выберите созданный ранее заказ на работу **Adventure Works**, используя записанный номер заказа на работу. В появившемся меню выберите пункт **Найти доступность**.  

15. Откроется **помощник по расписанию**.  

16. Вам должны быть представлены варианты планирования элемента.  Выберите запись Боба Козака.

17. В окне **Создать резервирование ресурса** установите **Время начала** на **начало следующего часа**.

18. Установите **Время окончания** на 2,5 часа позже.
  
19. Нажмите кнопку **Зарезервировать и выйти**, чтобы зарезервировать элемент и покинуть окно планирования. 

20. Иногда может потребоваться изменить график выполнения работ из-за конфликтов между техническими специалистами или по другим причинам.  Это легко может быть сделано диспетчерами с помощью таблицы расписаний.  

21. Щелкните поле поиска ресурсов в таблице расписаний (находится прямо над столбцом имени ресурса), введите «Райан» и найдите заказ на работу, который запланирован для Райана на сегодня.  

22. Щелкните правой кнопкой мыши заказ на работу и в появившемся меню выберите **Заменить ресурс**, затем нажмите кнопку **Найти замену**.

