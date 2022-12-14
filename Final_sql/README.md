# SQL-запросы
## Задачи:
1. Посчитать, сколько книг вышло после 1 января 2000 года;
2. Для каждой книги посчитать количество обзоров и среднюю оценку;
3. Определить издательство, которое выпустило наибольшее число книг толще 50 страниц — так мы исключим из анализа брошюры;
4. Определить автора с самой высокой средней оценкой книг — учитывать только книги с 50 и более оценками;
5. Посчитать среднее количество обзоров от пользователей, которые поставили больше 50 оценок.

## Общие выводы:
#### Запрос 1
- количество книг, опубликованных после 1 января 2000 г.: 819
- с 2000 года в среднем (по базе данных) публиковалось 40 книг в год

#### Запрос 2
- наибольшее количество обзоров имеет книга Twilight (Сумерки.Сага.Часть 1)
- почти все книги из топ-10 были экранизированы, и имеют рекордные кассовые сборы в кинотеатрах
- 8 из них имеют несколько частей, являются франшизами, как в книгах, так и в экранизациях
- средний рейтинг топ-10 не ниже 3.5
- топ имеет сотни обзоров благодаря популярности, серийности сюжета и сравнению с экранизацией, в т.ч. "подогреваемые" огромными рекламными бюджетами.

#### Запрос 3
- наибольшее количество книг опубликовали Penguin Books - 42
- большая часть топа-10 являются основными издателями Amazon Books
- более 20 книг опубликовали лишь 4 издателя, это в среднем более 1 книги в год (по базе данных)

#### Запрос 4
- J.K. Rowling/Mary GrandPré - автор с максимальным средним рейтингом всех своих книг (4.28), имеющих более 50 оценок

#### Запрос 5
- среднее количество обзоров от пользователей, которые поставили больше 50 оценок - 24
- в среднем эти читатели оставляют 50% обзоров, на общее количество прочитанных книг.

## Стек технологий: 
#### Pandas, Python, SQL;

## Статус проекта: Завершен
