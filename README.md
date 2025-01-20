# Инструкция по установке Label Studio на Windows

## Установка Python

- Перейти на официальный [сайт Python](https://www.python.org/downloads/windows/).
- Выбрать актуальную версию Python. На данный момент 3.13.1.
![](https://i.postimg.cc/3RPJPyXp/photo-2025-01-20-10-24-40.jpg)
- После скачивания файла, открываем его.
- Обязательно нажимаем выделенную галочку и делаем ее активной и нажимаем **Install Now**
![](https://i.postimg.cc/Y06kZdqK/photo-2025-01-20-10-24-35.jpg)
- После загрузки пакетов нажимаем **Disable path lenght limit** после чего закрываем окно установщика.

## Установка Label Studio
- Создаем папку, к примеру `label_studio` у удобном месте. !!!Желательно, чтобы полный путь к папке не имел символов кириллицы (русских символов).
- Открываем командную строку и пишем `cd C:\Users\Rustam\Desktop\ваш полный путь`
![](https://habrastorage.org/r/w1560/getpro/habr/upload_files/2a8/c63/d53/2a8c63d53ddd9f1b416a453edb4967a5.png)

- В следующем шаге мы создаем виртуальное окружение с помощью команды `python -m venv env`. Если команда `python -m venv env` не сработала попробуйте ввести `python3 -m venv env`.
![](https://habrastorage.org/getpro/habr/upload_files/a16/0ac/169/a160ac169124ba3784b900e5f9a96aa8.png)

-  В этом шаге мы активируем виртуальное окружение командой `env\Scripts\activate.bat`. Если слева от юзера появилось (env), то окружение активировано.
![](https://habrastorage.org/getpro/habr/upload_files/dc9/1ab/800/dc91ab80086e85b97ae42100bbb55133.png)

- В следующем шаге мы скачиваем Label Studio командой `pip install -U label-studio`.
![](https://habrastorage.org/r/w1560/getpro/habr/upload_files/b00/a7f/0a2/b00a7f0a22fbd46e978746a8bbb31144.png)

- Последний шаг - запуск Label Studio командой `label-studio`
![](https://habrastorage.org/r/w1560/getpro/habr/upload_files/7f7/129/c13/7f7129c13233c16552b108334ab94049.png)

- Если вы всё сделали без ошибок, то откроется страница Label Studio на вашем локальном сервере. Ниже видео этого процесса для большей наглядности:
[Видео](https://disk.yandex.ru/i/9k3JsdqGVVCuXQ)

## Работа в Label Studio
- Регистрируемся в Label Studio
![](https://i.postimg.cc/WpdvQ61J/2025-01-20-11-22-22.png)
- Создаем новый проект
![](https://i.postimg.cc/L5L0msWG/2025-01-20-11-25-16.png)
- Указываем любое название проекта 
![](https://i.postimg.cc/rsXQZkpj/2025-01-20-11-27-06.png)
- Загружаем изображения для разметки. Можно импортировать сразу большими пачками изображения. После чего заходим в настройки проекта.
![](https://i.postimg.cc/Gh9HgsZM/2025-01-20-11-31-12.png)
- Заходим в выбранные вкладки и нажимаем `Browse Templates`
![](https://i.postimg.cc/ZRV5VTjt/2025-01-20-11-33-26.png)
- Для нашей задачи по детекции нам лучше всего подходит шаблон «Object Detection with Bounding Boxes» или, проще говоря, разметка прямоугольниками.
![](https://i.postimg.cc/7PRx6tWV/2025-01-20-11-34-46.png)
- Удаляем стандартные лейблы и добавляем указанные. **Очень важно, чтобы они были в таком же порядке и назывались точно также как на следующем скриншоте.**
![](https://i.postimg.cc/L5P6Rz2R/2025-01-20-11-36-56.png)
- Переходим к разметке изображений. 
