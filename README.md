Тесты к курсу «Технологии Java»
====

[Условия домашних заданий](http://www.kgeorgiy.info/courses/java-advanced/homeworks.html)

Домашнее задание 2. ArraySortedSet
----
* Протестировать сложную версию задания:

        info.kgeorgiy.java.advanced.arrayset.Tester NavigableSet <полное имя класса>

* Протестировать простую версию задания:

        info.kgeorgiy.java.advanced.arrayset.Tester SortedSet <полное имя класса>

Исходный код тестов:

* [Простой вариант](java/info/kgeorgiy/java/advanced/arrayset/SortedSetTest.java)
* [Сложный вариант](java/info/kgeorgiy/java/advanced/arrayset/NavigableSetTest.java)


Домашнее задание 1. Обход файлов
----
Для того, чтобы протестировать программу:

 1. Скачайте тесты ([WalkTest.jar](artifacts/WalkTest.jar)) и библиотеки к ним:
    [junit-4.11.jar](lib/junit-4.11.jar) [hamcrest-core-1.3.jar](lib/hamcrest-core-1.3.jar)
 * Откомпилируйте решение домашнего задания
 * Запустите

        info.kgeorgiy.java.advanced.walk.Tester Walk <полное имя класса>

   для простого варианта, и

        info.kgeorgiy.java.advanced.walk.Tester RecursiveWalk <полное имя класса>

   для сложного. Обратите внимание, что все скачанные `.jar` файлы должны
   быть указаны в `CLASSPATH`.

Исходный код тестов:

* [Простой вариант](java/info/kgeorgiy/java/advanced/walk/WalkTest.java)
* [Сложный вариант](java/info/kgeorgiy/java/advanced/walk/RecursiveWalkTest.java)
