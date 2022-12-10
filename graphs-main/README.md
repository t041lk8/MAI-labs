# Лабораторная работа "Графы. Поиск кратчайших путей. Построение остовного дерева"
## Описание программы
Для взвешенного ориентированного графа, состоящего из 10 вершин, реализован алгоритм поиска кратчайшего пути. Для этого использовался алгоритм Флойда-Уоршелла.
Для каждой итерации алгоритма представлены промежуточные результаты (таблица кратчайших расстояний и таблица предков).

Для того же самого неориентированного графа построено его остовное дерево минимальной стоимости по алгоритму Прима.
Матрица смежности определена в начале программы.

## Входные данные
Два числа u и v - вершины, между которыми нужно найти кратчайший путь.
## Выходные данные
Таблица кратчайших расстояний, таблица предков, остовное дерево.
Кратчайший путь между вершинами u и v с указанием промежуточных вершин. В случае отсутствия кратчайшего пути, выводится сообщение об этом.