# Задача обедающих философах
Философы постоянно заняты размышлениями с перерывами на еду и сон.  
Они сидят за круглым столом. 
По центру стола стоит большая тарелка пасты.
Пасту есть одной вилкой неудобно, поэтому каждому 
философу нужны две вилки. 
Вилок столько же сколько философов.  
Если философ проголодается, и для него не найдётся двух свободных 
вилок, он умирает.  
Сытый философ сразу же засыпает. 
Выспавшись вновь приступает думать.  
Каждому философу необходимо есть и спать. 

## philo_one
В первой задаче вилки лежат слева и справа философа.   
Философ являются потоками, вилки - мьютексами.

## philo_two
Вилки лежат по центру стола.  
Философы являются потоками, вилки - семафорами.

## philo_three
Вилки лежат по центру стола.  
Философы являются процессами, вилки - семафорами.

## Программа принимает 4 аргумента:  
Количество философов   
Время до смерти в мс  
Время необходимое чтобы поесть в мс  
Время необходимое для сна в мс  
