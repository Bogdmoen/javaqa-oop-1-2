# Цикломатическая сложность кода

Цикломатическа сложность - это метрика для измерения сложности программы.  
Эта метрика зависит от от количества вложенных операторов ветвления и циклов в коде.


1. Jacoco вычисляет необходимое количество тестов исходя из формулы

v(G) = B - D + 1  
где 
B - количество ветвлений
D - количество точек принятия решений

Полученное значение - необходимое количество тестов для того, чтобы покрыть метод на 100%

2. Рекомендуемый порог цикломатической сложности - 10, с возможным повышением до 15 в некоторых случаях.