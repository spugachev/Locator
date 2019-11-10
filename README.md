# Locator
Система тестирования Локатор
Позволяет создать и наполнить базу вопросов, опубликовать тест и провести тестирование.

#Состав системы
Система состоит из трех компонет:
1. СУБД, используется Microsoft SQL Server в редакции Expres
2. Веб приложение, реализованное на ASP.NET Core
3. Административного интерейса/редактора тестов, дополнительное приложение позволяющее импортировать тесты, проверить и настроить их. Также позволяет работать со списками групп и отдельными тестирующимися.

#Проведение тестирования
Проведение тестирования происходит в несколько шагов:
1. Тестируемый регистрируется или заходит в систему под имеющимся (созданным ранее) пользователем.
2. Выбирается и запускается тест.
3. Тестируемый проходит тест
  в соответсвии с настройками:
  - Время может быть ограничено
  - Вопросы можно пропускать (возвращаясь к ним позднее) или нет
  - Правильность набранного балла может быть показана или скрыта
  - Результат теста по заверению тестирования может быть показан или скрыт
4. Система фиксирует показывает результат в административном интерфейсы "результаты тестирования"
Отдельно стоит отметить возможность аппелирования, возможность вывода результатов на печать.

* Система находится в стадии переноса в репозиторий, возможны ошибки.
