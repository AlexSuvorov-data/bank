## Сегментация клиентов банка "Метанпром" по потреблению.

Описание проекта:**

Последние месяцы в банке вырос отток клиентов. Они обратились к нам для поиска и анализа групп пользователей, на которые можно воздействовать, чтобы снизить отток. Необходимо проанализировать метрику по клиентам банка и сегментировать их по признакам, информация о которых была предоставлена.

Заказчик:

Отдел маркетинга.

Цель исследования:

Проанализировать отток клиентов из регионального банка, выделить наиболее подверженные уходу сегменты пользователей, дать рекомендации для улучшения ситуации.

Имеющиеся данные:

В нашем распоряжении датасет /datasets/bank_scrooge.csv, содержащий данные о клиентах банка «Метанпром». Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск:

    USERID — идентификатор пользователя;
    score — баллы кредитного скоринга;
    city — город;
    gender — пол;
    age — возраст;
    equity — количество баллов собственности;
    balance — баланс на счёте;
    products — количество продуктов, которыми пользуется клиент;
    credit_card — есть ли кредитная карта;
    last_activity — активный клиент;
    EST_SALARY — оценочный доход клиента;
    сhurn — признак оттока.

Декомпозиция:

    1)Обзор и предобработка данных:
        Загрузка библиотек и датасета;
        Приведение названий столбцов к "змеиному регистру";
        Преобразование столбцов;
        Работа с пропусками;
        Работа с дубликатами;
        Оценка выбросов;
    2)Исследовательский анализ:
        Рассмотрим распределение данных;
        Рассмотрим корреляцию оттока по признакам;
        Исследование оттока по значениям признаков;
        Выявим критерии для сегментации клиентов;
    3)Проверка статистических гипотез:
        Формулировка гипотез;
        Обоснование применения метода оценивания;
        Проверка и интерпретация результата;
    4)Промежуточные выводы.
    5)Сегментация на основе выделенных показателей:
        Анализ ключевых показателей;
        Приоритизация;
    6)Итоговые выводы и рекомендации:
        Фиксация конечного результата работы для заказчика.


