#  Пакет для проверки является ли ввод пятью

## Требования

- **PHP** ^8.0

## Установка

composer require dkeruntu/composer-package-if-five

## Использование

Проверка на 5

```
<?php

$obClass = new IfFive();

// Проверка различных вариантов
$arResult = $obClass->checkFive(5); // true
$arResult = $obClass->checkFive("пять"); // true
$arResult = $obClass->checkFive("five"); // true

// С подробной информацией
$arResult = $obClass->checkFive("V", true);

```


Получение всех возможных пятерок которые поддерживает данный модуль

```
<?php

$obClass = new IfFive;
var_dump($obClass ->getAllFiveVariants());

```
