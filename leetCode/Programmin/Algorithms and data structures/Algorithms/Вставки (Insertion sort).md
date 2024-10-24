[Explore - LeetCode](https://leetcode.com/explore/learn/card/sorting/694/comparison-based-sorts/4435/)

Алгоритм:
- Запускаем for от второго элемента до конца (итератор i);
- Заводим переменную currentIndex = i;
- Запускаем while с условием:  currentIndex > 0 && массив[currentIndex - 1] > массив[currentIndex]
- Меняем местами массив[currentIndex] и массив[currentIndex - 1], а currentIndex уменьшаем на 1;

Плюсы: не требует дополнительной памяти, хорош для маленьких массивов (примерно меньше 15,) и если нужно будет делать мало перестановок.
Минусы: медленный, O(n^2) в худшем случае.