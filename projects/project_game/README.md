# Проект. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)

### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений


### Краткая информация о данных
1) Функция random_predict(number: int = 1) - Рандомно угадывает число
2) Функция score_game(random_predict) - За какое количство попыток в среднем за 1000 подходов угадывает наш алгоритм
3) tpm=[1, 100] - Список, куда по умолчанию записан диапозон поиска чисел:
4) predict_number - Предполагаемое число
5) number - Загаданное число

### Алгоритм:
1) Если предполагаемое число больше загаданного числа, правую границу списка меняем на предполагаемое число. Если предполагаемое число меньше загаданного числа, левую границу списка меняем на предполагаемое число.
2) Следующее предполагаемое число будет находиться из среднего арифметического из границ списка

  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
1) Продумываем логику. Как достичь угадывания за наименьшее число попыток.
2) Реализация логики в VS Code.
3) Анализ полученных результатов.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Программа угададывает любое число от 1 до 100 в среднем за 5 попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Задача тривиальная. Сокращая ряд возможных чисел в двое, можно угадать любое число от 1 до 100 максимум за 7 попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️
