# Реализицая алгоритма RRT и RRT star

Алгоритм на вход принимает: 
- длину шагу (steer)
- радиус попадания в конечную цель(tolerance)
- кол-во эпох(не все они реализуются алгоритмом)

Алгоритм выдает длину пути(если он существует), также можно визуализирвовать получившийся граф и найденный путь.


-----------------------------------------------
На входе подаются: 

1.   Размеры поля
2. Кол-во препятсвий
3.   Препятсвия
4.   Начальная позиция
5. Конечная позиция


Пример входног файла: 


```
bordersize: [-10,10,-10,10]
num_obstacles: 2
obstacles:
  - ob: 1
    points: [[-1,1,1,-1,-1],[1,1,-1,-1,1]]
  - ob: 2
    points: [[-3,5,-1,-3],[2,8,1,2]]
start: [3,3]
finish: [5,5]
```
