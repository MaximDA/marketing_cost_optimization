# Приоритизация гипотез, анализ АВ-теста

#### Описание
Для крупного интернет-магазина была проведена оценка 9ти гипотез, подговленных маркетологами магазина.
Также проведен анализ результата АВ-теста.
<br>
<br>

#### Используемые инструменты
Анализ проводился на Python с использованием библиотек scipy, pandas, numpy, matplotlib
<br>
<br>

#### Выводы

- Среди предоставленных 9ти гипотез методом RICE выбрали гипотезу "Добавить форму подписки на все основные страницы, чтобы собрать базу клиентов для email-рассылок"
- Относительный график конверсии группы "В" к "А" показывает, что результаты стабилизировались и на данный момент составляют 17.4%. То есть конверсия группы "В" выше
- Статистической значимости в средних чеках нет как на "сырых" данных, так и на очищенных

Решение: Остановить тест, зафиксировать отсутствие различий между группами в среднем чеке. Но группа "В" показывает более высокие результаты по конверсии, поэтому признаем тест успешным.