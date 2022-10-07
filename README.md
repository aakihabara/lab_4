<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Коньков Никита Алексеевич</p>
<br><br><br>
<p align = "center">Лабораторная работа №4<br>«Основы языка <strong>JavaScript</strong>»<br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2022 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p> <b>HTML</b> (или же HyperText Markup Language) - стандартизированный язык разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора. </p>
<p> <b>JavaScript</b> – мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией спецификации ECMAScript (стандарт ECMA-262).JavaScript обычно используется как встраиваемый язык для программного доступа к объектам приложений. Наиболее широкое применение находит в браузерах как язык сценариев для придания интерактивности веб-страницам.</p>

<h1 align = "center">Цели и задачи</h1>

1.  Рассчитать значение у при заданном значении х  
  <p align = "center"><image src="z1.jpg" alt="z1"></p>
2.  Дано натуральное число n (n<=9999). Выяснить, является ли оно палиндромом ("перевертышем") с учетом четырех цифр, как, например, числа 7777, 8338, 0330 и т.п.(Палиндромом называется число, десятичная запись которого читается одинаково слева направо и справа налево.)<br><br>
3.	Год является високосным, если его номер кратен 4, однако из кратных 100 високосными являются лишь кратные 400, например, 1700, 1800 и 1900 — невисокосные года, 2000 — високосный. Дано натуральное число n. Определить, является ли високосным год с таким номером.<br><br>
4.	Составить программу для вычисления значения функции y(x):
  <p align = "center"><image src="z3.jpg" alt="z4">  </p><br><br>
5.	Составить программу, которая в зависимости от порядкового номера дня месяца (1, 2, ..., 12) выводит на экран время года, к которому относится этот месяц.<br><br>
6.	Мастям игральных карт условно присвоены следующие порядковые номера: масти "пики" — 1, масти "трефы" — 2, масти "бубны" — 3, масти "червы" — 4, а достоинству карт: "валету" — 11, "даме" — 12, "королю" — 13, "тузу" — 14 (порядковые номера карт остальных достоинств соответствуют их названиям: "шестерка", "девятка" и т. п.). По заданным номеру масти m (1 m 4) и номеру достоинства карты k (6 k 14) определить полное название (масть и достоинство) соответствующей карты в виде "Дама пик", "Шестерка бубен" и т. п.<br><br>
7.	В некоторых странах Дальнего Востока (Китае, Японии и др.) использовался (и неофициально используется в настоящее время) календарь, отличающийся от применяемого нами. Этот календарь представляет собой 60-летнюю циклическую систему. Каждый 60-летний цикл состоит из пяти 12-летних подциклов. В каждом подцикле года носят названия животных: Крыса, Корова, Тигр, Заяц, Дракон, Змея, Лошадь, Овца, Обезьяна, Петух, Собака и Свинья. Кроме того, в названии года фигурируют цвета животных, которые связаны с пятью элементами природы — Деревом (зеленый), Огнем (красный), Землей (желтый), Металлом (белый) и Водой (черный). В результате каждое животное (и его год) имеет символический цвет, причем цвет этот часто совершенно не совпадает с его "естественной" окраской — Тигр может быть черным, Свинья — красной, а Лошадь — зеленой. Например, 1984 год — год начала очередного цикла — назывался годом Зеленой Крысы. Каждый цвет в цикле (начиная с зеленого) "действует" два года, поэтому через каждые 60 лет имя года (животное и его цвет) повторяется. Составить программу, которая по заданному номеру года нашей эры n печатает его название по описанному календарю в виде: "Крыса, Зеленый". Рассмотреть два случая: а) значение n 1984; б) значение n может быть любым натуральным числом.<br><br>
8.	Напечатать таблицу умножения на 9.<br><br>
9.	Напечатать "столбиком" значения sin 2 , sin 3 , ..., sin 20 .<br><br>
10.	Найти: а) сумму всех целых чисел от 100 до 500; б) сумму всех целых чисел от a до 500 (значение a вводится с клавиатуры; a<=500); в) сумму всех целых чисел от –10 до b (значение b вводится с клавиатуры; b=>–10); г) сумму всех целых чисел от a до b (значения a и b вводятся с клавиатуры; b=>a).<br><br>
11.	Вычислить сумму
      <p align = "center"><image src="z10.jpg" alt="z11">  </p><br><br>
12.	Даны натуральные числа х и у. Вычислить произведение x и y, используя лишь операцию сложения. Задачу решить двумя способами.<br><br>
13.	Составить программу возведения натурального числа в квадрат, учитывая следующую закономерность
      <p align = "center"><image src="z12.jpg" alt="z13">  </p><br><br>
14.	Вычислить сумму
      <p align = "center"><image src="z13.jpg" alt="z14">  </p><br><br>
15.	Дана непустая последовательность целых чисел, оканчивающаяся нулем. Найти: а) сумму всех чисел последовательности; б) количество всех чисел последовательности.<br><br>
16.	Дана непустая последовательность неотрицательных целых чисел, оканчивающаяся отрицательным числом. Найти среднее арифметическое всех чисел последовательности (без учета отрицательного числа).<br><br>
17.	Дано натуральное число. Определить: а) количество цифр 3 в нем; б) сколько раз в нем встречается последняя цифра; в) количество четных цифр в нем. Составное условие и более одного неполного условного оператора не использовать; г) сумму его цифр, больших пяти; д) произведение его цифр, больших семи; е) сколько раз в нем встречаются цифры 0 и 5 (всего).<br><br>
18.	Дано натуральное число, в котором все цифры различны. Определить: а) порядковый номер его максимальной цифры, считая номера: от конца числа; от начала числа; б) порядковый номер его минимальной цифры, считая номера: от конца числа; от начала числа.<br><br>
19.	Дано натуральное число. Выяснить, является ли оно простым (простым называется натуральное число, большее 1, не имеющее других делителей, кроме единицы и самого себя). Оператор цикла с параметром не использовать.<br><br>
20.	Дано натуральное число. Установить, является ли последовательность его цифр при просмотре их слева направо упорядоченной по возрастанию. Например, для числа 1478 ответ положительный, для чисел 1782 и 1668 — отрицательный и т. п.<br><br>
21.	Дана непустая и упорядоченная по возрастанию последовательность целых чисел, оканчивающаяся числом 10 000. Определить порядковый номер первого числа, большего заданного n. Если таких чисел в последовательности нет, то на экран должно быть выведено соответствующее сообщение.<br><br>
22.	Дано натуральное число. Верно ли, что цифра a встречается в нем реже, чем цифра b?<br><br>
23.	Имеется фрагмент программы в виде оператора цикла с параметром, обеспечивающий вывод на экран "столбиком" всех целых чисел от 10 до 30. Оформить этот фрагмент в виде: а) оператора цикла с предусловием; б) оператора цикла с постусловием.<br><br>
24.  https://www.codewars.com/kata/head-tail-init-and-last<br>
25.  https://www.codewars.com/kata/array-deep-count<br>
26.  https://www.codewars.com/kata/length-of-missing-array<br>
27.  https://www.codewars.com/kata/pair-of-gloves<br>
28.  https://www.codewars.com/kata/sorting-by-bits<br>
29.  https://www.codewars.com/kata/lets-recycle<br>
<h1 align = "center">Решение</h1>  

```js
module.exports.getZad1 = function(x)
{
    if(x < 0)
        return Math.sin(x)**2;
    else
        return 1-(2*(Math.sin(x)**2));
    
}

module.exports.getZad2 = function(x)
{
    let a = String(x);
    while(a.length < 4)
    {
        a = "0" + a;
    }

    let b = a;
    let res = (a.split('').reverse().join('') == b) ? true : false;
    return res;
}

module.exports.getZad3 = function(n)
{
    if(n % 4 == 0)
    {
        if(n % 100 == 0)
        {
            if(n % 400 == 0)
            {
                return "Год является високосным";
            }
            else
                return "Год не является високосным";
        }
        else
            return "Год является високосным";
    }
    else
        return "Год не является високосным";
}

module.exports.getZad4 = function(x)
{
    if(x < -1)
        return -1;
    else if (x > -1)
        return x;
    else 
        return 1;
}

module.exports.getZad5 = function(x)
{
    switch(x)
    {
        case 1:
        case 2:
        case 12:
            return "Зима";
        case 3:
        case 4:
        case 5:
            return "Весна";
        case 6:
        case 7:
        case 8:
            return "Лето";
        case 9:
        case 10:
        case 11:
            return "Осень";
        default:
            return "Номер месяца введён неверно";
    }
}

module.exports.getZad6 = function(m,n)
{
    let res = "";

    switch(n)
    {
        case 6:
            res += "Шестёрка ";
            break;
        case 7:
            res += "Семёрка ";
            break;
        case 8:
            res += "Восьмёрка ";
            break;
        case 9:
            res += "Девятка ";
            break;
        case 10:
            res += "Десятка ";
            break;
        case 11:
            res += "Валет ";
            break;
        case 12:
            res += "Дама ";
            break;
        case 13:
            res += "Король ";
            break;
        case 14:
            res += "Туз "
            break;
        default:
            "Неверно указан номер достоинства";
            break;
    }

    switch(m)
    {
        case 1:
            res += "Пик";
            break;
        case 2:
            res += "Треф";
            break;
        case 3:
            res += "Бубен";
            break;
        case 4:
            res += "Червей";
            break;
        default:
            return "Номер масти введён неверно";
    }
    return res;
}

module.exports.getZad7 = function(n)
{
    let res = "";
    let forAn = n % 12 - 4;
    let forCol = Math.abs(n % 10 - 4);
    switch(forAn)
    {
        case 0:
            res += "Крыса, ";
            break;
        case 1:
            res += "Корова, ";
            break;
        case 2:
            res += "Тигр, ";
            break;
        case 3:
            res += "Заяц, ";
            break;
        case 4:
            res += "Дракон, ";
            break;
        case 5:
            res += "Змея, ";
            break;
        case 6:
            res += "Лошадь, ";
            break;
        case 7:
            res += "Овца, ";
            break;
        case 8:
            res += "Обезьяна, ";
            break;
        case 9:
            res += "Петух, ";
            break;
        case 10:
            res += "Собака, ";
            break;
        case 11:
            res += "Свинья, ";
            break;
    }
    switch(forCol)
    {
        case 0:
        case 1:
            res += "Зелёный";
            break;
        case 2:
        case 3:
            res += "Красный";
            break;
        case 4:
        case 5:
            res += "Желтый";
            break;
        case 6:
        case 7:
            res += "Белый";
            break;
        case 8:
        case 9:
            res += "Чёрный";
            break;
    }
    return res;
}

module.exports.getZad8 = function()
{
    for(let i = 2; i < 10; i++)
    {
        console.log(9 * i);
    }
}

module.exports.getZad9 = function()
{
    for(let i = 2; i < 21; i++)
    {
        console.log(Math.sin(i));
    }
}

module.exports.getZad10 = function(a, b)
{
    //a
    let res = 0;
    for(let i = 100; i < 501; i++)
    {
        res += i;
    }
    console.log(res);
    //b
    res = 0;
    let k = a;
    for(; k < 501; k++)
    {
        res += k;
    }
    console.log(res);
    //c
    res = 0;
    for(let i = -10; i <= b; i++)
    {
        res += i;
    }
    console.log(res);
    //d
    res = 0;
    let h = a;
    while(h <= b)
    {
        res += h;
        h++;
    }
    console.log(res);
}

module.exports.getZad11 = function(n)
{
    let res = 0;
    for(let i = 1; i <= n; i++)
    {
        res += 1/i;
    }
    return res;
}

module.exports.getZad12 = function(x, y)
{
    let res = 0;
    for(let i = 1; i <= y; i++)
    {
        res += x;
    }
    console.log(res);
    res = 0;
    let i = 1;
    while(i <= y)
    {
        res += x;
        i++;
    }
    console.log(res);
}

module.exports.getZad13 = function(n)
{
    let res = 0;
    let plus = 1;
    for(let i = 1; i <= n; i++)
    {
        res += plus;
        plus += 2;
    }
    return res;
}

module.exports.getZad14 = function()
{
    let res = 0;
    let sqr = 2;
    for(let i = 1; i <= 50; i++, sqr += 2)
    {
        res += Math.pow(i, sqr);
    }
    console.log(res);
}

module.exports.getZad15 = function(a)
{
    //a
    let res = 0;
    for(let i = 0; i < a.length; i++)
        res += a[i];
    console.log(res);
    //b
    console.log(a.length);

}

module.exports.getZad16 = function(a)
{
    let res = 0;
    let reslength = a.length;
    for(let i = 0; i < a.length; i++)
    {
        if(a[i] >= 0)
            res += a[i];
        else
            reslength--;
    }
    return res / reslength;
}

module.exports.getZad17 = function(a)
{
    let lastnumeric;
    let three = 0;
    let lastnum = a % 10;
    let lastc = 0;
    let even = 0;
    let moreThanFive = 0;
    let mulMoreSeven = 1;
    let zeroOrFive = 0;
    while(a != 0)
    {
        lastnumeric = a % 10;
        //a
        if(lastnumeric == 3)
            three++;
        //b
        if(lastnumeric == lastnum)
            lastc++;
        //c
        if((lastnumeric % 2) == 0)
            even++;
        //d
        if(lastnumeric > 5)
            moreThanFive += lastnumeric;
        //e
        if(lastnumeric > 7)
            mulMoreSeven *= lastnumeric;
        //f
        if(lastnumeric == 5)
            zeroOrFive++;
        if(lastnumeric == 0)
            zeroOrFive++;
        a = Math.floor(a / 10);
    }
    console.log("а) " + three);
    console.log("б) " + lastc);
    console.log("в) " + even);
    console.log("г) " + moreThanFive);
    console.log("д) " + mulMoreSeven);
    console.log("е) " + zeroOrFive);
}

module.exports.getZad18 = function(a)
{
    let str = a.toString();
    let num = a;
    let lastnumeric;
    let a1 = a % 10;
    let a2 = a % 10;
    let b1 = a % 10;
    let b2 = a % 10;
    let a1i = str.indexOf(a1);
    let a2i = str.indexOf(a2);
    let b1i = str.indexOf(b1);
    let b2i = str.indexOf(b1);
    //a.1
    do
    {
        lastnumeric = num % 10;
        if(lastnumeric > a1)
            a1 = lastnumeric;
            a1i = str.indexOf(a1) + 1;
        num = Math.floor(num / 10);
    }while(num != 0);
    num = a;
    //a.2
    let digits = 0;
    do
    {
        digits++;
        num = Math.floor(num / 10);
    }while(num != 0);
    num = a;
    while(digits > 1)
    {
        digits--;
        let number = Math.floor(num / Math.pow(10, digits));
        num -= number * Math.pow(10,digits);
        if(number > a2)
            a2 = number;
            a2i = str.indexOf(a2) + 1;
    }
    num = a;
    //b.1
    do
    {
        lastnumeric = num % 10;
        if(lastnumeric < b1)
            b1 = lastnumeric;
            b1i = str.indexOf(b1) + 1;
        num = Math.floor(num / 10);
    }while(num != 0);
    num = a;
    //b.2
    digits = 0;
    do
    {
        digits++;
        num = Math.floor(num / 10);
    }while(num != 0);
    num = a;
    while(digits > 1)
    {
        digits--;
        let number = Math.floor(num / Math.pow(10, digits));
        num -= number * Math.pow(10,digits);
        if(number < b2)
            b2 = number;
            b2i = str.indexOf(b2) + 1;
    }
    console.log("а.1)" + a1i);
    console.log("а.2)" + a2i);
    console.log("б.1)" + b1i);
    console.log("б.2)" + b2i);
}

module.exports.getZad19 = function(a)
{
    let i = 2;
    while(i < a)
    {
        if(a % i == 0)
            return "Число не является простым";
        i++;
    }
    return "Число является простым";
}

module.exports.getZad20 = function(a)
{
    let lastnum = a % 10;
    while(a != 0)
    {
        Math.floor(a /= 10);
        let num = a % 10;
        if(num > lastnum)
            return "Число не является при просмотре слева направо упорядоченным по возрастанию";
        lastnum = num;
    }
    return "Число является при просмотре слева направо упорядоченным по возрастанию";
}

module.exports.getZad21 = function(a, n)
{
    for(let i = 0; i < a.length; i++)
    {
        if(a[i] > n)
            return "Порядковый номер первого числа больше n = " + (i+1);
    }
    return "Таких чисел в последовательности нет";
}

module.exports.getZad22 = function(n,a,b)
{
    let countA = 0;
    let countB = 0;
    do
    {
        let digit = n % 10;
        if(digit == a)
            countA++;
        else if(digit == b)
            countB++;
        n = Math.floor(n / 10);
    }while(n != 0);

    if(countA < countB)
        return true;
    else
        return false;
}

module.exports.getZad23 = function()
{
    //a
    let i = 9;
    while(i < 30)
    {
        i++;
        console.log(i);
    }
    //b
    i = 9;
    do
    {
        i++;
        console.log(i);
    }while(i < 30)
}
```

24. Head, Tail, Init and Last
```js
function head(a) {
  return a[0]
}

function tail(a) {
  return a.slice(1)
}

function init(a) {
  return a.slice(0, a.length-1)
}

function last(a) {
  return a[a.length-1] 
}
```

25. Array Deep Count

```js
let count = 0;
function countin(a)
{
  if(a.length == 0)
    return 0;
  for(let x of a)
    {
      if(Array.isArray(x))
        {
          count++;
          countin(x);
        }
      else
        count++;
    }
  return count;
}
function deepCount(a){
  //...
  let res = countin(a);
  count = 0;
  return res;
}
```

26. Length of missing array
```js
function getLengthOfMissingArray(arrayOfArrays) {
  if(arrayOfArrays != null)
    {
      arrayOfArrays = arrayOfArrays.sort(function(a,b){
      if((a == null) || (b == null))
        return ;
      else
        return a.length - b.length;
      });
    }
  else
    return 0;
  
  
  
  if((arrayOfArrays[0] == null) || (arrayOfArrays.length == 0) || (arrayOfArrays[0].length == 0))
    return 0;
  
  let arrlen = arrayOfArrays.map(x => x ? x.length : 0);
  
  if(arrlen.includes(0))
    return 0;
  
  for(let i = arrlen[0], j = 0; j < arrlen.length; j++, i++)
    {
      if(arrlen[j] != i)
        return i;
    }
}
```
27. Pair of gloves
```js
function numberOfPairs(gloves)
{
  let pairscount = 0;
  let gls = gloves.slice("").sort();
  //My hands are freezing
  for(let i = 0; i < gls.length - 1; i++)
    {
      if(gls[i] == gls[i+1])
        {
          pairscount++;
          i++;
        }
    }
  return pairscount;
}
```
28. Sorting by bits
```js
function sortByBit(arr) {
  arr.sort((a, b) => a.toString(2).replace(/0/g, '') - b.toString(2).replace(/0/g, '') || a - b)
  
  return (arr)
}
```
29. Let's Recycle!
```js
function recycle(array) {
  const all = [[], [], [], []];
  let index = {'paper' : 0, 'glass': 1, 'organic' : 2, 'plastic' : 3}
  
  for(let x of array)
    {
      all[index[x.material]].push(x.type);
      
      if(x.secondMaterial != undefined)
        all[index[x.secondMaterial]].push(x.type);
    }
  return all;
}
```

<h1 align = "center">Вывод</h1>
Опираясь на материал с сайта w3school, лекции, я немного поработал с базовыми функциями node.js, а также решил поставленные задачи в codewars.
