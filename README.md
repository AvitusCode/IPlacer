# IPlacer

## Постановка задачи.
1. В данном репозитории в папке pictures даны 11 фотографий (10 с предметами на белом листе бумаги и 1 с фоном).
2. Входные данные лежат в папке data и представляют из себя набор изображений с предметами.
3. Требуется определить: смогут ли предметы из набора данных поместиться в заданный многоугольник.
4. Многоугольник будет задаваться массивом с координатами вершин на естественной плоскости. Координаты будут предварительно записаны в файл формата CSV. Каждая строка соответствует координате, сначала ВСЕГДА задается координата по x, а потом по y. Допускаются следующие координаты [[x,y],[x,y+h],[x+h,y+h],[x+h,y]].

### Результат работы
Выводим True, если объект(ы) поместился в заданный многоугольник. Выводим False в другом случае (в том числе при ошибке работы алгоритма)

### Требования к входным и выходным данным:
1. На одной фотографии не может быть расположено несколько предметов одного типа.
2. Все предметы должны полностью вместе со своими границами лежать в пределах белого листа бумаги.
3. Все предметы должны быть отделены друг от друга. Минимальное расстояние 1 мм.

### Изображения предметов:
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p1.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p2.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p3.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p4.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p5.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p6.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p7.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p8.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p9.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p10.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/pictures/p11.jpg)

### Данные:
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/data/d1.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/data/d2.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/data/d3.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/data/d4.jpg)
![alt text](https://github.com/AvitusCode/IPlacer/tree/develop/data/d5.jpg)
