    Виртуальная среда - окружающая среда Python, в которой
    интерпритатор Python, библиотеки и сценарии, установленные в нее,
    изолированны от установленных в других вирутальных средах,
    а также установленных в "системном" Python.
    Виртуальная среда — это дерево каталогов, содержащее исполняемые 
    файлы и другие файлы Python, указывающие, что это виртуальная среда.
    
    Создание виртульной среды в командной строке
        >python -m venv <venv>
    Ключ -m означает, Python запускает встроенный модуль venv как скрипт.
    <venv> - каталог куда установлена виртуальная среда

    Активация виртуальной среды:
        Windows "cmd.exe"
            <venv>\Script\activate.bat
        Windows "PowerShell"
            <venv>\Script\Activate.ps1
        POSIX "bash/zsh"
            source <venv>/bin/activate
    Деактивация виртуальной среды просто введите в терминале
        deactivate
