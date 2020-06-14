# Класс CPowerLayer

<!-- TOC -->

- [Класс CPowerLayer](#класс-cpowerlayer)
    - [Настройки](#настройки)
        - [Степень](#степень)
    - [Обучаемые параметры](#обучаемые-параметры)
    - [Входы](#входы)
    - [Выходы](#выходы)

<!-- /TOC -->

Класс реализует слой, возводящий каждый элемент входа в некоторую степень.

Имеет формулу:

```c++
f(x) = pow(x, GetExponent())
```

## Настройки

### Степень

```c++
void SetExponent( float exponent );
```

Установка степени, в которую возводятся элементы входа.

## Обучаемые параметры

Слой не имеет обучаемых параметров.

## Входы

На единственный вход подается блоб с данными произвольного размера.

## Выходы

Единственный выход содержит блоб тех же размеров, что и вход, с результатами функции над его элементами.