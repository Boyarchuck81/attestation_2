# FindCellsSpecifiedLength

### Принимаемые и возвращаемые значения
Метод _**FindCellsSpecifiedLength**_ принимает в качестве входных данных следующие аргументы: 
- массив строк 
- переменную со значение типа int указывающую, ограничение длины ячейки.

Метод _**FindCellsSpecifiedLength**_ возвращает массив строк.

### Прицип работы метода
Метод _**FindCellsSpecifiedLength**_ перебирает принимаемый массив и присваивает в возвращаемый массив значения только тех ячеек которые не превышают указанную длину.

### Подробное описание работы метода

- Создаем и инициализируем переменную _count_, которая будет является счетчиком

- Перебираем принимаемый массив, если ячейка массива не превышает указанную длину, _count_ увеличиваем на единицу.

- Создаем массив строк _result_ с размером полученным из переменной count.

- Переменной _count_ присваиваем значение 0.

- Перебираем принимаемый массив, если ячейка массива не превышает указанную длину, в ячейку массива _result_ равную значению хранящемуся в переменной _count_ присваиваем значение из ячейки принимаемого массива. Увеличиваем _count_ на единицу.

- Возвращаем заполненный массив _result_.

- ВСЕ ВРЕМЯ ЗАБЫВАЛА ДЕЛАТЬ КОММИТЫ
