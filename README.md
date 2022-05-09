## Классификация изображений с помощью сверточной нейронной сети
### Практическое задание №1 в рамках курса «Нейронные сети в обработке изображений»

В результате выполнения задания была реализована и обучена модель, основанная на свёрточных нейронных сетях, для классификации фрагментов полнокадровых гистологических изображений (патчей) на 9 классов. Каждый патч представляет собой цветное (8-bit) изображение 224 × 224 px. 

Достигнута точность `95.44%` на тестовом наборе данных.

### Список дополнений:
| Метка | Описание |
| ----- |--------|
| LBL1  | Валидация модели на части обучающей выборки |
| LBL2  | Остановка обучения при потере точности на валидационной выборке |
| LBL3  | Вывод функции потерь и точности в процессе обучения |
