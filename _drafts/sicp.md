*Нормальный порядок  вычислений* - реализация подстановочной  модели применения
процедуры,  при которой  интерпретатор сперва  производит замену  (подстановку)
"дырок"  процедур  на их  тела,  а  затем  производит вычисления  (редукцию)  с
конкретными значениями аргументов. (Пример, почему хуже аппликативного?)

При *аппликативном  порядке вычислений* сперва вычисляются  значения аргументов
процедур,  а  затем  их  подстановка,  и так  рекурсивно  вплоть  до  получения
результата.