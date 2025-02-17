# ConsoleApp

[Задание 1](section#1)
[Задание 2](section#2)
[Задание 3](section#3)



<a id="section1"></a>
## Задание №1
В ходе выполнения задания была проведена отладка программы на C#, вычисляющей элемент последовательности Фибоначчи. Изначально программа возвращала неверное значение для пятого элемента последовательности (3 вместо 5). С использованием отладчика Visual Studio были выполнены следующие шаги:

 - **Создание** проекта: Создан консольный проект.

 - **Анализ кода:** Изучен код, вычисляющий последовательность Фибоначчи, и выявлена ошибка в логике цикла.

 - **Установка точек останова:** Точки останова были установлены на ключевых строках кода для пошагового выполнения и проверки значений переменных.

 - **Пошаговая отладка:** Проверены значения переменных n1, n2, sum и i на каждой итерации цикла.

 - **Обнаружение ошибки:** Выявлено, что цикл завершался на одну итерацию раньше, чем нужно, из-за условия i < n в цикле for.

 - **Исправление ошибки:** Условие цикла изменено на i <= n, что позволило выполнить все необходимые итерации.

 - **Проверка результата:** После исправления программа вернула правильное значение для пятого элемента последовательности Фибоначчи — 5.

***Итог:*** Ошибка успешно исправлена, программа теперь корректно вычисляет элементы последовательности Фибоначчи.



<a id="section2"></a>
## Задание №2
В ходе выполнения задания было создано консольное приложение на C# для отображения информации о галактиках (название, расстояние, тип). В процессе разработки были выявлены и исправлены ошибки:

 - **Создание проекта:** Создан консольный проект.

 - **Анализ кода:** Изучен код, который выводит информацию о галактиках, и выявлены проблемы:

   - Свойство GalaxyType в классе Galaxy было объявлено как object, что приводило к неправильному выводу типа галактики.

   - Опечатка в операторе switch (case 'l' вместо case 'I') для типа галактики "Irregular".

 - **Отладка:**

   - Установлены точки останова для анализа значений переменных.

   - Исправлено свойство GalaxyType на тип GType, чтобы корректно отображать тип галактики.

   - Исправлена опечатка в операторе switch для правильного определения типа "Irregular".

 - **Проверка результата:** После исправлений приложение выводит корректные данные о галактиках, включая правильные типы.

***Итог:*** Ошибки успешно исправлены, приложение теперь корректно отображает информацию о галактиках.


<a id="section3"></a>
## Задание №3
