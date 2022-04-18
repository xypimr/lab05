[![Coverage Status](https://coveralls.io/repos/github/SodAcetate/Lab05a/badge.svg?branch=main)](https://coveralls.io/github/SodAcetate/Lab05a?branch=main)

Badge is embedded using:
```
[![Coverage Status](https://coveralls.io/repos/github/xypimr/lab05/badge.svg?branch=main)](https://coveralls.io/github/xypimr/lab05?branch=main)
```

## Laboratory work V fffffff

Данная лабораторная работа посвещена изучению фреймворков для тестирования на примере **GTest**

## Tasks

- [x] 1. Создать публичный репозиторий с названием **lab05** на сервисе **GitHub**
- [x] 2. Склонировать репозиторий с библиотекой *banking*
- [x] 3. Добавить сабмодуль **gtest**
- [x] 4. Написать тесты для библиотеки *banking*
- [x] 5. Написать `CMakeLists` для сборки библиотеки и тестов
- [x] 6. Увидеть, что в коде есть ошибка и исправить её
- [x] 7. Написать `CI.yml` для **Github Actions**
- [x] 8. Подключить **lcov** и **Coveralls** для измерения покрытия кода

## Homework

### Задание
1. Создайте `CMakeList.txt` для библиотеки *banking*.

2. Создайте модульные тесты на классы `Transaction` и `Account`.
    * Используйте mock-объекты.
    * Покрытие кода должно составлять 100%.
3. Настройте сборочную процедуру на **Github Actions**.
4. Настройте [Coveralls.io](https://coveralls.io/).

## Links

- [lcov](http://ltp.sourceforge.net/coverage/lcov.php)
- [lcov manual](http://ltp.sourceforge.net/coverage/lcov/lcov.1.php)
- [Coveralls.io](https://coveralls.io/).
- [Coveralls for Github Actions](https://github.com/marketplace/actions/coveralls-github-action)

```
Copyright (c) 2015-2021 The ISC Authors
```
