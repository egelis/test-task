## Build and run main program:
>`./build.sh`
> 
> `cd build/`
> 
> `./TestTask file.csv`

## Build and run test program:
> `cd Test/`
> 
> `./build.sh`
> 
> `cd build/`
> 
> `./Tests`

Тестовые примеры находятся в `Test/tests`. 
На них проводится тестирование программы, где проверяется:
- пустота ячеек
- корректность размерности таблцы (должна быть прямоугольной)
- наличие пустой ячейки в начале
- одинаковые название колонок, индексы строк
- положительное число в индексах строк
- деление на 0
- принадлежность выражение виду = ARG1 OP ARG2
- использование целых чисел
- ссылки только на существующие ячейки
