Реализовать REST сервис по работе с накопительным счётом
В сервисы должны быть реализованы:
- аутентификация/авторизация пользователя;
- создание накопительного счета;
- выполнение базовых финансовых операций со счетом (пополнение, перевод, оплата);
- создание карты к счету + операции по ним(асинхронно,опционально);
- выгрузка истории операций;
- учет комиссий по операциям (опционально);
Данные должны храниться в БД (любая на выбор)
Реализация сервиса через Spring
Для демонстрации работы крайне желательно создать базовый UI, состоящий из страниц:
- авторизации/аутентфикации;
- основной страницы;
На основной странице необходимо отобразить текущие счета/карты пользователя и данные по ним.
Здесь же должен быть интерфейс для проведения операций, а также выгрузки истории.
Инструменты разработки ui - любые 
Для логики аутентификации/авторизации предлагается использовать Spring Security
Инструменты работы с базой - любые (Jdbc, Spring data и пр.)
Код бэка должен быть покрыт юнит тестами не менее чем на 50%
Инструменты юнит тестирования - любые
