## Интерфейс для создания бита
#### Описание:
Интерфейс включает в себя камеру для записи трека взгляда и приложение. Пользователь
запускает приложение и на экране появляется панель с настройками.
С помощью взгляда осуществляется ввод данных, после чего сигнал преобразуется в
аудиофайл(возможно, с помощью machine learning). Пользователь может скачать полученный файл,
а также посмотреть файлы, которые похожи на этот и созданы другими пользователями.(опционально).
#### Технологии:
* ROS
* Python
* OpenCV

#### Цель проекта:
Реализация интерфейса

#### Задачи проекта:
* Настройка камеры для трека взгляда
* Дизайн приложение
* Разработка алгоритма генерации бита, на основе полученных данных
* Разработка приложения
#### Запуск:
* Открыть терминал
* Выполнить команду `git clone https://github.com/x-sanchez/ROS`
* Для начала работы необходимо установить все модули,
указанные в requirements.txt Для этого можно выполнить следующую команду
`pip install -r requirements.txt`
* Запустить Interface.py
* Получать удовольствие
