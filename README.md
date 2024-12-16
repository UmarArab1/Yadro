# Справка по использованию Yadro

## Описание

Yadro — это простой язык программирования, предназначенный для создания программ с использованием различных конструкций, таких как переменные, функции, условия и циклы. Язык поддерживает работу с графикой, сетевыми операциями и базами данных.

## Установка

1. **Клонируйте репозиторий:**
   git clone https://github.com/ваш_репозиторий/Yadro.git

2. **Перейдите в директорию проекта:**
   cd Yadro

3. **Убедитесь, что у вас установлен Python 3.6 или выше.**

## Использование

### Запуск интерпретатора

Чтобы запустить интерпретатор и обработать файл с кодом на Yadro, используйте следующую команду:

python src/main.py <имя_файла>

**Пример:**

python src/main.py examples/example1.y

### Примеры кода

#### Пример 1: Создание переменной и логирование

создать переменная.py = "Hello, Yadro"  
логировать переменная.py

#### Пример 2: Условная конструкция

создать число = 10  
ЕСЛИ число > 5 ТО  
    логировать "Число больше 5"  
КОНЕЦ

#### Пример 3: Функция

ФУНКЦИЯ приветствие(имя)  
    логировать "Привет, " + имя  
КОНЕЦ  

приветствие("Мир")

### Поддерживаемые конструкции

- **Создание переменной**: создать имя.расширение = "значение"
- **Условные конструкции**: ЕСЛИ условие ТО ... КОНЕЦ
- **Циклы**: ПОКА условие ТО ... КОНЕЦ
- **Функции**: ФУНКЦИЯ имя(аргументы) ... КОНЕЦ
- **Логирование**: логировать "Сообщение"

## Тестирование

Для запуска тестов используйте следующие команды:

python -m unittest tests/test_lexer.py  
python -m unittest tests/test_parser.py  
python -m unittest tests/test_interpreter.py  

## Заключение

Yadro — это мощный инструмент для создания программ, который поддерживает множество конструкций и возможностей. Вы можете расширять язык, добавляя новые функции и улучшая существующие. Если у вас есть вопросы или предложения, не стесняйтесь обращаться!
