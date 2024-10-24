[Explore - LeetCode](https://leetcode.com/explore/learn/card/sorting/694/comparison-based-sorts/4434/)


Алгоритм:
- Ставим bool переменную hasSwapped в true;
- Запускаем While(hasSwapped);
- Сразу скидываем hasSwapped в false;
- Запускаем for от начала до предпоследнего(!) элемента массива; (итератор i)
- Если массив[i] > массив[i+1], то меняем их местами и ставим hasSwapped = true;

Плюсы: не требует дополнительной памяти. очень простой в реализации.
Минусы: медленный, O(n^2) в худшем случае.