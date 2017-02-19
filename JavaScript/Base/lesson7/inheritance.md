# Домашнее задание по JS.

### Задача:

    HTML:
    Создаем страницу на которой будет 1 кнопка, и 3 чекбокса.
    На кнопке написано: "Показать модальное окно", чекбоксы будут добавлять стиль для модального окна, их будет 3 это:             "Ошибка" - красный цвет окна,
    "Информация" - синий цвет окна,
    "Предупреждение" - желтый цвет окна!

    Пользовать будет выбирать одну из галочек и нажимать на кнопку "Показать модальное окно" (его еще называют попапом) как только он нажимает на кнопку => появляется модальное окно определенного цвета, заданого галочкой.
    По умолчанию у вас должна быть выбрана галочка со стилем: "Информация"

### Модальное окно:

    Модальное окно состоит из 3 частей:
    1. Крестик сверху справа которая тоже будет закрывать окно
    2. Текст в окне, какой-то статитческий текст
    3. кнопка: "Ок" которая тоже будет закрывать окно


## Как это все нужно сделать:

Для этой задачи будем использовать функции конструкторы:

Создаем класс Modal который будет базовым класом для модального окна, у него будет 3 свойства:


```
function Modal (options) {
  // тут будут свойства которые нужны для нашего модального окна
}
```

этот класс должен создавать функционал для добавления и показывания модального окна на страницу + добавлять действия на кнопки внутри попапа

### Методы класса:

#### create
он будет показывать создавать динамически модальное окно через document.createElement и т.д. а потом добавлять его на страницу, если уже такое модельное окно на странице
есть оно его уже создавать не будет а будет возвращать существующее!

#### show
он будет показывать наше окно меняя this.visibility

#### hide
он будет скрывать наше окно меняя this.visibility

После этого, создаем 3 экземпляра этого класса:

```
var info =
var error =
var warning =
```

Это будут наши 3 попапа с разными стилями соотвественно, для этого вам нужно будет для каждого экземпляра правильно передать параметры в конструктор Modal!

Теперь в зависимости от того какая галочка отмечена мы будем будем показывать тот или инной попап!

Все теперь вам осталось создать кнопочку и 3 галочки и слепить все это в 1 целое!))