# Отчёт по итогам автоматизации

## Что было запланировано и что было сделано

- проведено исследовательское тестирование функционала веб-сервиса покупки тура "Путешествие дня".
- настроен удобный запуск SUT с быстрым подключением к необходимой БД.
- запущена и настроена CI, запускающая тесты на обеих заявленных БД: MySQL и PostgreSQL.
- составлен план автоматизации, предусматривающий 53 тестовых сценария (16 сценариев API тестирования и 37 на 
UI тестирование).
- написан необходимый для автоматизации тестовый фреймворк для взаимодествия с 
элементами веб-сервиса и для управления тестовыми данными. 
При этом тестовые данные независимы от текущей даты и генерируются случайно для избежания эффекта пестицида.
- автоматизированы все 53 заявленных в плане тестовых сценария. Помимо заявленных было добавлено ещё 7 дополнительных
сценария тестирования UI.
- составлен отчет по результату прогона тестов.
- созданы 16 issues по найденным дефектам.

## Сработавшие риски

- отсутствие технической документации не позволяло четко определить ожидаемый результат в тестах
- требование поддержки двух СУБД добавило сложности в настройках запуска SUT и CI.
- отсутствие у веб-элементов приложения атрибута test-id создало сложности с локаторами элеметов при составление page objects.

## Общий итог по времени

Было запланировано - затратить от 88 до 96 рабочих часов, график предполагаемых затрат времени приведен ниже:

Подготовка к проведению тестирования (запуск SUT, подготовка плана автоматизации) - 16 часов;
Написание и прогон авто-тестов - 40 часов;
Написание баг-репортов - 8 часов;
Оформление отчёта по итогам тестирования - 8 часов;
Оформление отчёта по итогам автоматизации - 16 часов.
Было затрачено - 84 рабочих часа, график затрат времени приведен ниже:

Подготовка к проведению тестирования (запуск SUT, подготовка плана автоматизации) - 24 часов;
Написание и прогон авто-тестов - 36 часов;
Написание баг-репортов - 8 часов;
Оформление отчёта по итогам тестирования - 8 часов;
Оформление отчёта по итогам автоматизации - 8 часов.
Расхождение во времени связано с тем что часть рисков не сработала, написание авто-тестов и отчета по итогам автоматизации заняло, меньше времени чем изначально предполагалось.
