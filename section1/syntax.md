    python язык регистрозависимый
        >>> A = 2
    и
        >>> a = 2
    разные переменные.
    
    Python язык со строгой динамической типизацией.
    Есть языки со строгой типизацией (Pascal, Java, C++ и т.п.), у которых тип переменной
определяется заранее и не может быть изменен, и есть языки с динамической типизацией
(python, ruby, vb), в которых тип переменной трактуется в зависимости от присвоенного значения. 
Динамические языки можно разделить еще на два типа: Строгие, которые не допускают неявное 
преобразование (python) и нестрогие, которые выполняют неявные преобразования типа 
сложения переменной строкового типа и число '123' + 456 (VisualBasic)

    В python для индикации блока кода используются отступы, тогда в других языках
программирования отступы используются для читабельности кода. Пример:
    Правильный синтаксис:

        >>> if 5 > 2:
        >>>     print('Five is greater than two)
    
    Вызовет ошибку интепретатора:
    
        >>> if 5 > 2:
        >>> print('Five is greater than two)

    Количество отступов зависит от программиста, но должно быть одинаковым во всем
блоке кода. Такой код вызовет ошибку интерпритатора
        >>> if 5 > 2:
        >>>     print('Five is greater than two)
        >>>         print('Five is greater than two)

    Однострочные комментарии начинаются со знака #
        >>> # This is a comment
    Многострочный комментарий заключен между ''' '''
        >>> '''
        >>>     This is a multiline comment
        >>>     All this is a comment
        >>> '''
