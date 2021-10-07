# Лабораторна робота №1. Вступ до програмування. Освоєння Linux
1.1 Розробник
Горбань Кирило Володимирович;
Студент группи КІТ-121д
7 жовтня 2021
1.2 Загальне завдання
Розробити функцію, яка генерує структуру із залученням механізму випадкової генерації даних (прикладна галузь вказана в індивідуальному завданні). Розробити функцію, яка буде виводити вміст масиву структур на екран.
1.3 Індивідуальне завдання
Прикладна галузь «Тварина». Типи об’єктів та їх поля: тип (напр. Корова, Свиня), ріст, вага.
    **2 ОПИС ПРОГРАМИ**
    2.1 Функціональне призначення
Програма призначена для генерації тварин та видача їх на екран за допомогою функцій, що декларовані в файлі stdio.h. 
При генерації тварини діють наступні обмеження:
    • тип тварини - один з переліку: кіт, собака, корова, свиня;
    • ріст: від 0 до 255 (см);
    • вага: від 0 до 255 (кг). 
Результат зберігається у змінній animals.
Демонстрація знайдених результатів передбачає як покрокове виконання програми в режимі налагодження, так і видача даних у вікні консолі.
Таким чином вивід на єкран початкове

![Снимок экрана от 2021-10-07 13-52-40](https://user-images.githubusercontent.com/92089246/136368392-73cca951-0c75-4903-b5a3-f1172a408b19.png)
змінився на 
![Снимок экрана от 2021-10-07 13-57-33](https://user-images.githubusercontent.com/92089246/136368733-cabcd5a0-a3ca-4c7c-973b-15bfc6c183ab.png)
2.2 Внесення змінних до Makefile
для додання all, яка буде виконувати цілі clean prep compile check.
Відкриваемо Makefile та вносимо: 
all: clean prep compile cheak
виконуемо команду make all.
Структура проекту після команди make all:
          └── lab00
            ├── dist
            ├──  └──main.bin
            ├── Doxyfile
            ├── Makefile
            ├── README.md
            ├── doc
            │   ├── assets
            │   ├── lab00.docx
            │   └── lab00.md
            ├── src
            │   ├── lib.c
            │   ├── lib.h
            │   └── main.c
            └── test
                └── test.c
3.ВИСНОВКИ
При виконанні даної л.б. було здобуто практичного досвіду роботи з ОС Linux, утилита tree,git, clone та іншими.
