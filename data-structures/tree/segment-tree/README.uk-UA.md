# Дерево сегментів

В інформатиці **дерево сегментів**, також відоме як дерево статистики
це деревоподібна структура даних, що використовується для зберігання інформації про інтервали,
або сегментах. Воно дозволяє запитувати, який із збережених сегментів містить
знаходиться задана точка. Це, в принципі, статична структура, тобто
це структура, яка не може бути змінена після створення. Схожою
структурою даних є дерево інтервалів.

Дерево сегментів - це бінарне дерево. Корінь дерева представляє собою
весь масив. Два нащадки кореня представляють
першу та другу половину масиву. Аналогічно, дочірні елементи
нащадки кожного вузла відповідають двом половинам
масиву, що відповідає вузлу.

Ми будуємо дерево знизу вгору, при цьому значення кожного вузла
є "мінімумом" (або будь-якою іншою функцією) значень його дочірніх елементів. Це займе `O(n log n)` часу. Кількість
виконаних операцій є висотою дерева, яка
дорівнює `O(log n)`. Для виконання діапазонних запитів кожен вузол розбиває
на дві частини, по одному підзапиту для кожного нащадка.
Якщо запит містить весь підмасив вузла, ми
можна використати попередньо обчислене значення у вузлі. Використовуючи цю
оптимізацію, ми можемо довести, що виконується лише `O(log n)` мінімум
операцій.

![Min Segment Tree](https://www.geeksforgeeks.org/wp-content/uploads/RangeMinimumQuery.png)

![Sum Segment Tree](https://www.geeksforgeeks.org/wp-content/uploads/segment-tree1.png)

## Застосування

Дерево сегментів - це структура даних, призначена для ефективного виконання
ефективного виконання певних операцій з масивами - особливо тих.
що передбачають запити до діапазону.

Дерево сегментів застосовується в обчислювальній геометрії,
та географічних інформаційних систем.

Поточна реалізація Segment Tree передбачає, що ви можете
передати йому будь-яку бінарну (з двома вхідними параметрами) функцію і
таким чином, ви можете робити діапазонні запити для різноманітних функцій.
У тестах ви можете знайти приклади виконання діапазонних запитів `min`, `max` і `сума` на SegmentTree.
запитів до SegmentTree.

## Посилання

- [Wikipedia](https://en.wikipedia.org/wiki/Segment_tree)
- [YouTube](https://www.youtube.com/watch?v=ZBHKZF5w4YU&index=65&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [GeeksForGeeks](https://www.geeksforgeeks.org/segment-tree-set-1-sum-of-given-range/)