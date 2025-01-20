# Инструкция по установке Label Studio на Windows
## Установка Python
- Перейти на официальный [сайт Python](https://www.python.org/downloads/windows/). 
- ![https://iimg.su/i/FR5YW] Выбрать актуальную версию Python. На данный момент 3.13.1.
- После скачивания файла, открываем его. 
- ![https://iimg.su/i/OxUdg] Обязательно нажимаем выделенную галочку и делаем ее активной.
- ![https://iimg.su/i/9bffm] Нажимаем Disable path lenght limit после чего закрываем окно установщика.
## Установка Label Studio
- Создаем папку, к примеру `label_studio` у удобном месте.  !!!Желательно, чтобы полный путь к папке не имел символов кириллицы (русских символов).
- Открываем командную строку и пишем `cd C:\Users\Rustam\Desktop\ваш полный путь`
![https://habrastorage.org/r/w1560/getpro/habr/upload_files/2a8/c63/d53/2a8c63d53ddd9f1b416a453edb4967a5.png]
- В следующем шаге мы создаем виртуальное окружение с помощью команды `python -m venv venv`. Если команда `python -m venv venv` не сработала попробуйте ввести `python3 -m venv venv`.
![https://habrastorage.org/getpro/habr/upload_files/a16/0ac/169/a160ac169124ba3784b900e5f9a96aa8.png]
-  В этом шаге мы активируем виртуальное окружение командой `venv\Scripts\activate.bat`. Если слева от юзера появилось (venv), то окружение активировано.
![https://habrastorage.org/getpro/habr/upload_files/dc9/1ab/800/dc91ab80086e85b97ae42100bbb55133.png]
- В следующем шаге мы скачиваем Label Studio командой `pip install -U label-studio`.
![https://habrastorage.org/r/w1560/getpro/habr/upload_files/b00/a7f/0a2/b00a7f0a22fbd46e978746a8bbb31144.png]
- Последний шаг - запуск Label Studio командой `label-studio`
![https://habrastorage.org/r/w1560/getpro/habr/upload_files/7f7/129/c13/7f7129c13233c16552b108334ab94049.png]
- Если вы всё сделали без ошибок, то откроется страница Label Studio на вашем локальном сервере. Ниже видео этого процесса для большей наглядности:
[![](https://wdfiles.ru/3vDed)]
