# rogueGame
Выполнение тестового задания

Исходные данные

- Карта - это двухмерный массив, в котором хранится признак - стена это или пол
- Отрисовка производится очисткой <div class=”field”></div> и добавлением в него <div class=”tile”></div>
- Отрисовка здоровья производится добавлением <div class=”health” style=”width: нужное-количество%;”></div> внутрь <div class=”tile”></div>
 
Задачи

- Сгенерировать карту 40x24
- Залить всю карту стеной
- Разместить случайное количество (5 - 10) прямоугольных “комнат” со случайными размерами (3 - 8 клеток в длину и ширину)
- Разместить случайное количество (3 - 5 по каждому направлению) вертикальных и горизонтальных проходов шириной в 1 клетку
- Разместить мечи (2 шт) и зелья здоровья (10 шт) в пустых местах
- Поместить героя в случайное пустое место
- Поместить 10 противников с случайные пустые места
- Сделать возможность передвижения героя клавишами WASD (влево-вверх-вниз-вправо)
- Сделать возможность атаки клавишей пробел ВСЕХ противников находящихся на соседних клетках
- Сделать атаку героя противником, если герой находится на соседней клетке с противником
- Сделать случайное передвижение противников (на выбор, либо передвижение по одной случайной оси, либо случайное направление каждый ход, либо поиск и атака героя)
- Сделать восстановление здоровья при наступлении героя на зелье здоровья (и удаление зелья)
- Сделать увеличение силы удара героя при наступлении героя на меч (и удаление меча)

Условия

- Должно запускаться открытием файла index.html в браузере (без сервера)
- Не должно быть недостижимых зон


Требования к коду

- Отсутствие повторяющихся кусков, переиспользование кода там, где это возможно
- Хранение состояния внутри Javascript, а не в DOM

