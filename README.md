# HW01

## Дедлайн 23:59 13.02

1. (2 балла) Поддержать в обоих парсерах операции вычитания (`'-'`) и деления (`'/'`). Обе операции левоассоциативны. Вычитание обладает тем же приоритетом, что и сложение; деление обладаем тем же приоритетом, что и умножение.
1. (2 балла) Поддержать в обоих парсерах операцию возведения в степень (`'^'`). Операция является правоассоциативной и обладает бОльшим приоритетом, нежели умножение.
2. (2 балла) Порефакторить, чтобы избавиться от дублирования в коде.

## Процедура сдачи

1. Сделать форк этого репозитория.
2. Выполнить домашку в своем форке в соответствующей ветке.
3. Отправить PR со сделанной домашкой в этот репозиторий.
4. Код должен собираться, тесты должны проходить.

## Сборка и запуск

1. `stack build` для сборки.
2. `stack test` для запуска тестов.
3. `stack exec exe -- <args>` для запуска консольного приложения.
   1. `stack exec exe -- "+*123" -p -d` для запуска парсера для арифметики в префиксной записи на строке с отображением результата в консоли.
   2. `stack exec exe -- -i test.txt -o test.out` для запуска парсера для арифметики в инфиксной записи на содержимом файла `test.txt`; результат будет записан в файл `test.out`.
4. `stack run exe -- <args>` для запуска консольного приложения с предварительной сборкой проекта.

[Запись лекции](https://drive.google.com/file/d/1sKYYPl24H4Rd3uKJZHb7axkHPEOgEMbs/view?usp=sharing)
