# Sociability Test

### Описание

Тест на определение уровня общительности. Реализация на Ruby.
Необходимо ответить на 16 простых вопросов, выбирая из предложенных вариантов ответа.

Создан на основе: http://psylist.net/praktikum/00003.htm


### Запуск

Для запуска программы необходимо установить Ruby и запустить в коммандной строке:

`ruby main.rb`

### Назначение файлов

**main.rb** - основной файл программы

**lib/test.rb** - класс, предназначенный для контроля за состоянием теста - текущий вопрос, подсчет результатов

**lib/test_reader.rb** - класс, предназначенный для считывания теста из файла

**lib/user_io.rb** - класс ввода-вывода для взаимодействия с пользователем

**data/test1.json** - файл с входными данными - вопросами, вариантами ответов, результатами