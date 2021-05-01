#  Speaker [v. 1.1]

##  Пакеты
Нужные для работы пакеты:
1. Speech Recognizion(Получение и переобразование речи в текст)
2. gTTS(Отвечает за произношение)
3. pyttsx3(Вспомогашки для работы с Виндой)
4. pypiwin32(Вспомогашки для работы с Виндой ч. 2)
5. PyAudio(большинство функции(КАУШН! НЕ УСТАНАВЛИВАЕТСЯ ЧЕРЕЗ pip, СТАВИТСЯ ТОЛЬКО ШИНОЙ! (о том как установить читать [тут](https://github.com/ParTy-Play-go/speaker/tree/master#%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-pyaudio)))
6. (по вкусу) colorama (Изменяет цвет текста консоли)
7. (для собственных целей) Pyinstaller (Компилятор в exe(команда для билда Спикера [тут](https://github.com/ParTy-Play-go/speaker/tree/master#%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0-%D0%B4%D0%BB%D1%8F-pyinstaller)))
---
##  Информация
* Все остальное (принцип работы, что, куда, зачем) раписано в самом коде([main.py](https://github.com/ParTy-Play-go/speaker/blob/master/main.py "Тыкай)")).
* *В последующих коммитах напишу сюда, чтобы не засорять код.*
---
## Установка PyAudio
Добро пожаловать в самое не подробное руководство "Как поставить PyAudio"!
* Шаг 1: если у вас python 3.9 в архиве есть шина(ТОЛЬКО ДЛЯ ВИНДОВС!)
* Шаг 2: пишете команду pip install PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl и радуетесь жизни
* Шаг 3: если у вас не python 3.9, то идем сюда(https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) и скачиваем вил для нужной вам версии, затем прописываете 
pip install название вилла полностью и радуетесь жизни
---
## Команда для Pyinstaller
    pyinstaller -i"путь к иконке, если не нужна иконка удаляйте все" -F --hidden-import=pyttsx3.drivers --hidden-import=pyttsx3.drivers.sapi5 main.py
---
## Установщик
https://github.com/ParTy-Play-go/speaker/releases/tag/v.1.1-beta
---
## Цитата дня
> Кофе в рот - пиши код)
