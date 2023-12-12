# lab_SPO_sec_bash

#1

Суммирование

Напишите программу, которая находит суммирование каждого числа от 1 до num. Число всегда будет целым положительным числом, большим 0.

Например:

sum(2) -> 3

1 + 2

sum(8) -> 36

1 + 2 + 3 + 4 + 5 + 6 + 7 + 8

<img width="225" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/3409164c-9be3-4f91-be7a-14aaf5309892">
<img width="261" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/14906938-2dd7-45f9-927d-cceeb81087b8">

#2

Возьмите 2 строки s1 и s2, включающие только буквы от a до z.

Возвращает новую отсортированную строку, максимально длинную, содержащую различные буквы - каждая из которых берется только один раз - исходящие из s1 или s2.

a = "xyaabbbccccdefww"

b = "xxxxyyyyabklmopq"

longest(a, b) -> "abcdefklmopqwxy"

a = "abcdefghijklmnopqrstuvwxyz"

longest(a, a) -> "abcdefghijklmnopqrstuvwxyz"

<img width="470" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/f843e7aa-9db8-4337-9991-943cc24350b5">
<img width="471" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/45268191-2ab7-4bfd-a81e-54d1133c32a4">

#3

Джон пригласил друзей. Его список:

s = "Ann:Russel;John:Gates;Paul:Wahl;Alex:Tolkien;Ann:Bell;Lewis:Kern;Sarah:Rudd;Sydney:Korn;Madison:Meta";

Нужно написать программу, которая переводит эту строку в верхний регистр и сортирует ее в алфавитном порядке по фамилии.

Если фамилии совпадают, отсортируйте их по имени. Фамилия и имя гостя вводятся в результате в скобках через запятую.

Таким образом, результатом будет:

"(BELL, ANN)(GATES, JOHN)(KERN, LEWIS)(KORN, SYDNEY)(META, MADISON)(RUDD, SARAH)(RUSSEL, ANN)(TOLKIEN, ALEX)(WAHL, PAUL)"

Может случиться так, что в двух разных семьях с одинаковой фамилией два человека также имеют одинаковое имя.

<img width="401" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/755563f0-ac78-4c69-ba26-1f5016130014">

<img width="450" alt="image" src="https://github.com/Krutov12/lab_SPO_sec_bash/assets/77206997/a08b50e8-32ae-408c-8c0b-cec1ca006aab">
