# Домашнее задание по JS.

## 1 задание

Придумайте самый короткий код для проверки, пуст ли элемент elem.

«Пустой» — значит нет дочерних узлов, даже текстовых.

if (/*...ваш код проверки elem... */) { узел elem пуст }
Что написать в условии if ?

## 2 задание

Создайте таблицу с 10 стороками и столбцами!

Напишите код, который выделит все ячейки в таблице по диагонали.

Вам нужно будет получить из таблицы table все диагональные td и выделить их, используя код:

```

// в переменной td DOM-элемент для тега <td>
td.style.backgroundColor = 'red';

```

## 3 задание

Напишите функцию printNumbersInterval(), которая последовательно выводит в консоль числа от 1 до 20, с интервалом между числами 100мс. То есть, весь вывод должен занимать 2000мс, в течение которых каждые 100мс в консоли появляется очередное число.

## 4 задание

Напишите функцию createSpanInBlockByID(blockID) которая будет создавать элемент 'span' в блоке id=blockID

createSpanInBlockByID('myBlock') // создаст span в блоке с id='myBlock'

P.S. Эта функция должна проверять наличие элемента в этом блоке, если он уже там есть второй раз она его добавлять не будет!

## 5 задание

Создайте функцию createCloneNode(block) которая которая будет клонировать передаваемый ей элемент и добавять его в конец страницы! 

## 6 задание

Создайте функцию addChildrenTo(block, count, type) которая будет создавать внутри block count количество детей типа type ( type это будет тип блока например 'span, ul, li, div' и т.д.  )

## 7 задание

Напишите функцию replaceElBy(blockCurrent, blockToReplace) которая будет заменять blockCurrent на blockToReplace и выводить сообщение пользователю после успешного проведения операции!

## 8 задание

Создайте элемент #test. По клику на него выведите название его тега.

## 9 задание

Создайте элемент #test. По клику на него выведите название его тега в нижнем регистре.

## 10 задание

Создайте пару элементов с классом .www. Добавьте каждому элементу в конец название его тега в нижнем регистре.

## 11 task

Создайте ol. Вставьте ему в конец li с текстом 'пункт'.

## 12 task
 
Дан ul. Дан массив. Вставьте элементы этого массива в конец ul так, чтобы каждый элемент стоял в своем li.

## 13 task

Дан массив. Создайте div через createElement, затем вставьте каждый элемент этого массива в отдельный p 
внутри этого div, затем вставьте этот div в конец body.

## 14 task

Дан элемент #test. Вставьте перед ним абзац с текстом '!!!'.