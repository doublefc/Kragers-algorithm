# Kragers-algorithm

Этот алгоритм необходим для рассчета минимального разреза графа. Это эвристический алгоритм, однако в своей реализации я довел вероятность получения ответа до $1 - 1/n^2$ путем добавления $n^2*log(n)$ итераций поиска разреза. n - количество вершин в графе.

Реализовал телеграм бота, в основном используя библиотеку aiogram. На вход боту нужно подавать граф в виде списка ребер
