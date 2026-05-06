# Лабораторная работа №3

Представьте, что вы стажер в компании "Formatter Inc.".

## Задание 1

Вам поручили перейти на систему автоматизированной сборки CMake. Исходные файлы находятся в директории `formatter_lib`. В этой директории находятся файлы для статической библиотеки `formatter`.

Создайте [`CMakeLists.txt`](formatter_lib/CMakeLists.txt) в директории `formatter_lib`, с помощью которого можно будет собирать статическую библиотеку `formatter`.

## Задание 2

У компании "Formatter Inc." есть перспективная библиотека, которая является расширением предыдущей библиотеки.

Создайте [`CMakeLists.txt`](formatter_ex/CMakeLists.txt) для библиотеки `formatter_ex`, которая использует библиотеку `formatter`.

## Задание 3

Создайте `CMakeLists.txt` для двух приложений:

- [`hello_world`](hello_world_application/CMakeLists.txt), которое использует библиотеку `formatter_ex`
- [`solver`](solver_application/CMakeLists.txt), приложение которое использует статические библиотеки `formatter_ex` и `solver_lib`

