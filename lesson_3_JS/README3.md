## Основи Web UI розробки 2023
Завдання №1
1.0/1 point (graded)
Опис завдання:

Створити функцію з назвою isEven, яка буде приймати число і повертати булевий результат (True/False). True – число парне, False – число не парне. Результат повернути за допомогою ключового слова "return".


```
function isEven (number) 
{  if (number % 2 == 0)
	{ return true; } else { return false; } 
} var valueIsEven = isEven();
```

Завдання №2
1.0/1 point (graded)
Опис завдання:

Створити глобальну змінну senseOfLife = 42. Створити функцію, яка буде приймати параметр otherSenseOfLife. Якщо параметр передати, то функція має повернути його. А якщо не передати, то фунція має повернути глобальну змінну senseOfLife.

```
var senseOfLife = 42;

function showVariable (otherSenseOfLife) 
{
	var otherSenseOfLife = otherSenseOfLife;
	if (otherSenseOfLife = otherSenseOfLife)
		return otherSenseOfLife;
	else
    	return senseOfLife;
}
```
ЗЗавдання №3
1/1 point (graded)
Опис завдання:

Виберіть 3 DOM елемента:
- зверніться до елемента <div id="test"></div> за id = "test" та присвойте вибраний елемент змінній id.

- зверніться до елемента <div class ="test"></div> за класом class = "test" та присвойте вибрані елементи змінній className

- зверніться до елемента <div></div> за тегом та присвойте вибрані елементи змінній tag

```
var id = document.getElementById('test');
var className = document.getElementsByClassName('test');
var tag = document.getElementsByTagName('div');
```
Завдання №4
1/1 point (graded)
Опис завдання:

У елемент <ul id="test"></ul> потрібно додати три <li></li> елементи. Вибрати <ul> елемент за допомогою id = “test”. Створити кожен новий <li></li> елемент за допомогою методу createElement() та додати до списоку за допомогою методу appendChild().

```
for (int i =0; i<3; i++) 
{
	var child = document.createElement("li");
	var text = document.createTextNode("Item");
	child.appendChild(text);

	var parent = document.getElementById("test");
	parent.appendChild(child);
}
```
Завдання №5
1.0/1 point (graded)
Опис завдання:

Створити функцію – калькулятор. Назва count. Функція приймає 3 параметра:

перший параметр типу Number,
другий парамерт типу Number,
третій параметр типу String,

в який передається значення операції. Значеннями операції можуть бути: «+», «-» , «*» і «/». Функція повинна повернути результат виконаної операції за допомогою return.
* Підказка: використайте конструкцію switch.

```
function count (num1, num2, mark) 
{
	switch (mark) 
	{
	case "+" :
		return num1 + num2;
	case "-" :
		return num1 - num2;
	case "*" :
		return num1 * num2;
	case "/" :
		return num1 / num2;
	}
	return mark; 
}
```


-------------------------------------------------------------------------------------------------------------------------------

