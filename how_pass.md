# !!! ВСЕГДА ТЕСТИРУЙТЕ КОД ЛОКАЛЬНО ПЕРЕД ОТПРАВКОЙ !!!
Неработающий код может сильно снижать оценку. 

Необходимо в общий проект [OEMIB_PI01_19_TBOT](https://github.com/IHVH/OEMIB_PI01_19_TBOT) добавить новую функцию, которая используя какие либо из изученных технологий реализует взаимодействие с внешней системой. Необходимо использовать только общедоступные api которые ещё не использовались в других функциях. 
(Если хотите модифицировать и расширить существующую функцию, согласуйте это в чате [sstmintgrtn](https://t.me/sstmintgrtn))
Функция должна выполнять какое то осмысленное (желательно полезное) действие. 

# *Используйте только программные интерфейсы парсинг страниц не подходит!*

- В вашем аккаунте на github.com делаете fork репозитория.
- Добавляете вашу функцию отдельным фалом в папку `/src/functions/`. Весь код функции должен быть внутри класса унаследованного от абстрактного класса `BotFunctionABC`. В репозитории есть пример [example_bot_function.py](https://github.com/IHVH/OEMIB_PI01_19_TBOT/blob/main/src/functions/example_bot_function.py) как организовать наследование и код внутри класса. 
- Затем необходимо добавить информацию о вашей функции в словарь `BOT_FUNCTIONS_2` в файле [bot_func_dictionary.py](https://github.com/IHVH/OEMIB_PI01_19_TBOT/blob/main/src/bot_func_dictionary.py). 
- Если необходимы токены или другие аутентификационные данные, добавляйте информацию о них в файл [README.md](https://github.com/IHVH/OEMIB_PI01_19_TBOT/blob/main/README.md). 
- Новые зависимости добавляйте в [requirements.txt](https://github.com/IHVH/OEMIB_PI01_19_TBOT/blob/main/requirements.txt)
- Протестировав всё локально отправляете Pull request в основной репозиторий.

Вопросы можно задавать, обсуждать в общем телеграм чате [sstmintgrtn](https://t.me/sstmintgrtn).
Список общедоступных api можно посмотреть в [project](https://github.com/users/IHVH/projects/1) 
либо найти подходящий в репозитории [public-apis](https://github.com/IHVH/public-apis) 