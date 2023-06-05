# AVL Tree

В інформатиці **AVL-дерево** (назване на честь винахідників
Адельсона-Вельського та Лендіса) - це самобалансуюче бінарне пошукове
дерево двійкового пошуку. Це була перша така структура даних, яку було винайдено.
В AVL-дереві висоти двох дочірніх піддерев будь-якого
вузла відрізняються не більше ніж на одиницю; якщо в будь-який момент часу вони відрізняються на
більше, ніж на одиницю, то для відновлення цієї властивості виконується ребалансування.
Пошук, вставка та видалення займають `O(log n)` часу у
як у середньому, так і у найгіршому випадку, де n - кількість
вершин у дереві до виконання операції. Вставки та
видалення можуть вимагати перебалансування дерева за допомогою одного або
більше обертань дерева.

Анімація, що демонструє вставку декількох елементів у дерево AVL
дерево. Вона включає обертання вліво, вправо, вліво-вправо та вправо-вліво.

![AVL Tree](https://upload.wikimedia.org/wikipedia/commons/f/fd/AVL_Tree_Example.gif)

Дерево AVL з коефіцієнтами збалансованості (зелене)

![AVL Tree](https://upload.wikimedia.org/wikipedia/commons/a/ad/AVL-tree-wBalance_K.svg)

### Обертання дерева AVL

**Обертання вліво-вліво**

![Left-Left Rotation](http://btechsmartclass.com/data_structures/ds_images/LL%20Rotation.png)

**Обертання вправо-вправо**

![Right-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/RR%20Rotation.png)

**Обертання вліво-вправо**

![Left-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/LR%20Rotation.png)

**Обертання вправо-вліво**

![Right-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/RL%20Rotation.png)

## Посилання

* [Wikipedia](https://en.wikipedia.org/wiki/AVL_tree)
* [Tutorials Point](https://www.tutorialspoint.com/data_structures_algorithms/avl_tree_algorithm.htm)
* [BTech](http://btechsmartclass.com/data_structures/avl-trees.html)
* [AVL Tree Insertion on YouTube](https://www.youtube.com/watch?v=rbg7Qf8GkQ4&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8&index=12&)
* [AVL Tree Interactive Visualisations](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html)
