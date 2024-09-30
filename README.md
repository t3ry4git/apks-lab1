# Лабораторна робота №1 з дисципліни «Автоматизоване проектування комп'ютерних систем» «Побудова комбінаційної схеми (перетворювача коду)»
## Загальне завдання
1) Описати логічні елементи на мові Active-HDL згідно з варіанту в
таблиці.
2) Побудувати логічну схему, використовуючи логічні елементи, описані
мовою A-HDL, описати поведінку КС, побудувати часові діаграми
роботи КС.
3) Описати поведінку перетворювача коду мовою А-HDL та побудувати
часові діаграми роботи перетворювача коду.
## Варіант 22 - 00010110
### Таблиця істиності
|x1|x2|x3|y1|y2|
|:-:|:-:|:-:|:-:|:-:|
|0|0|0|0|1|
|0|0|1|1|1|
|0|1|0|0|0|
|0|1|1|1|1|
|1|0|0|0|0|
|1|0|1|0|0|
|1|1|0|1|1|
|1|1|1|0|1|
### Час затримки 
10 ps
### Логічні елементи 
3NAND, 3NOR
### Логічні вирази
Y1 = ~X1 * X3 U X1 * X2 * ~X3

Y2 = X1 * X2 U ~X1 * ~X2 U X2 * X3
### Схема:
<img src="https://github.com/t3ry4git/apks-lab1/blob/b359c4bd11de1599e003c7a014820edb89e439d2/scheme.png" alt="scheme" />
