# Project_1
Проект включает три задания:

- Задание 1. A/B–тестирование
- Задание 2. SQL
- Задание 3. Python
## Задание 1. A/B–тестирование

### - Условие

Одной из основных задач аналитика в нашей команде является корректное проведение экспериментов. Для этого мы применяем метод A/B–тестирования. В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. Необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на всех пользователей.

### - Входные данные

В качестве входных данных 4 csv-файла:

- **groups.csv** - файл с информацией о принадлежности пользователя к контрольной или экспериментальной группе (А – контроль, B – целевая группа) 
- **groups_add.csv** - дополнительный файл с пользователями, который вам прислали спустя 2 дня после передачи данных
- **active_studs.csv** - файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента. 
- **checks.csv** - файл с информацией об оплатах пользователей в дни проведения эксперимента. 

### - Вопросы

Найти ответ на следующие вопросы:

- На какие метрики смотрим в ходе анализа и почему?
- Имеются ли различия в показателях и с чем они могут быть связаны?
- Являются ли эти различия статистически значимыми?
- Стоит ли запускать новую механику на всех пользователей?
## Общий план исследования

### 1.1. **Препроцессинг данных:**
    - Посмотрим на данные
    - Построим графики
    
### 1.2. **Формулировка гипотез:**
    - Выберем метрику
    - Построим графики
    - Сформулируем предположения

    
### 1.3. **Проверка гипотез:**
     - Выбираем подходящий тест
     - Тестируем
     
     
### 1.4. **Подведение итогов:**
    - Сформулировать выводы
    - Какие действия нужно предпринять разработчикам / бизнесу.
