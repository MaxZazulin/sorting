[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Сортировки+на+языке+Kotlin!)](https://git.io/typing-svg)
<h4 align="left">Задание: Написать различные сортировки целочисленных массивов на языке kotlin</> 
<h2 align="center">1 - Пузырьковая сортировка</h2> 
<h5 align="left">Или сортировка простыми обменами. Бессмертная классика жанра. Принцип действий прост: обходим массив от начала до конца, попутно меняя местами неотсортированные соседние элементы. В результате первого прохода на последнее место «всплывёт» максимальный элемент. Теперь снова обходим неотсортированную часть массива (от первого элемента до предпоследнего) и меняем по пути неотсортированных соседей. Второй по величине элемент окажется на предпоследнем месте. Продолжая в том же духе, будем обходить всё уменьшающуюся неотсортированную часть массива, запихивая найденные максимумы в конец</h5>
<img src="https://github.com/MaxZazulin/Sorting/blob/main/Materials/Пузырьковая%20Сортировка.gif"> 
<h2 align="center">2 - Глупая сортировка</h2> 
<h5 align="left">Сортировка и впрямь глупейшая. Просматриваем массив слева-направо и по пути сравниваем соседей. Если мы встретим пару взаимно неотсортированных элементов, то меняем их местами и возвращаемся на круги своя, то бишь в самое начало. Снова проходим-проверяем массив, если встретили снова «неправильную» пару соседних элементов, то меняем местами и опять начинаем всё сызнова. Продолжаем до тех пор пока массив потихоньку-полегоньку не отсортируется.</h5>
<img src="https://github.com/MaxZazulin/Sorting/blob/main/Materials/Глупая%20Сортировка.gif"> 
<h2 align="center">2 - Шейкерная сортировка</h2> 
<h5 align="left">Она же сортировка перемешиванием, она же коктейльная сортировка. Начинается процесс как в «пузырьке»: выдавливаем максимум на самые задворки. После этого разворачиваемся на 1800 и идём в обратную сторону, при этом уже перекатывая в начало не максимум, а минимум. Отсортировав в массиве первый и последний элементы, снова делаем кульбит. Обойдя туда-обратно несколько раз, в итоге заканчиваем процесс, оказавшись в середине списка.</h5>
<img src="https://github.com/MaxZazulin/Sorting/blob/main/Materials/Шейкерная%20сортировка.gif"> 
