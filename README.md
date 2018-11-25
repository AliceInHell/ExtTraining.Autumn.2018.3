# ExtTraining.Summer.2018.4

1. Дана система типов (проект No1) для верификации пароля согласно некоторым фиксированным правилам и его сохранения, в случае валидности, в хранилище. Какие  проблемы возникнут при использовании данного кода, если множество клиентов класса PasswordCheckerService захотят его использовать для различных комбинаций условий валидации (существующих и новых), используя при этом различные хранилища? Выполнить рефакторинг данного кода, устранив обнаруженную проблему (решение поместить в проект No1.Solution), проверить работу новой системы типов с помощью тесты (unit & mock). Тесты поместить в проект No1.Tests.
2. Разработана система типов (проект No2), моделирующая работу метеостанции на базе запатентовнного объекта WeatherData, отслеживающего текущие погодные условия (температура, влажность, атмосферное давление), а также классов для создания текущей сводки, статистики и простого прогноза. Все данные должны обновляться в режиме реального времени, по мере того, как объект WeatherData получает данные последних изменений. Изменить код, используя механизм событий (решение поместить в проект No2.Solution), проверить работу новой системы типов в консоли (проект No2.Solution.Console) или с использованием мок-фреймворка (добавить проект No2.Tests в решение). 