str()
Строка 'hello' и "hello" идентичны

Создание
    >>> a = 'Hello'

Многострочные строки
    >>> a = """ Это многострочная
                строка.
            """
    >>> a = ('Это тоже\n'
    >>>     'многострочная\n'
    >>>     'строка')

Строка это массив символов, можно получить доступ к символу по индексу
    >>> a = 'Hello'
    >>> print(a[2])
    >>> l

Перебор символов в строке
    >>> for s in a:
    >>>     print(s)
    >>> H
    >>> e
    >>> l
    >>> l
    >>> o

    >>> print(len(a))
    >>> 5

Проверка строк
    >>> a = 'Python course'
    >>> b = 'Python'
    >>> b in a
        True
    >>>

Срез строк
    >>> a[2:-2]
    'thon cour'
    >>> a[-5:-1]
    'ours'

Методы строк https://www.w3schools.com/python/python_ref_string.asp

    >>> a = 'Python'
    >>> b = 'course'
    >>> c = a + ' ' + b
    >>> print(c)
    Python course
    или
    >>> c = f'{a} {b}'
    >>> print(c)
    Python course

Форматирование строк
    >>> a = 12
    >>> s = f'Variable a = {a}'
    или тоже
    >>> s = f'Variable {a = }'

Точность значений с плавающей запятой
    >>> pi = 3.14159
    >>> f'Value {pi: {1}.{5}}
    'value  3.1416'
    >>> f'value {pi: .2f}'
    'value  3.14'
