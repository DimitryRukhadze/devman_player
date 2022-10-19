Видеоплеер для devman
===

Это простой видеоплеер, выполненный в рамках обучающего курса [devman](https://dvmn.org). Готовый вариант
можно увидеть на [GitHub Pages](https://dimitryrukhadze.github.io/devman_player/).

Подготовка к работе на локальной машине
---
Для начала необходимо в главной директории проекта создать виртуальное окружение командой в терминале:
```commandline
python -m venv env
```

Затем запустите его по инструкциям из документации. [Ссылка на документацию](https://docs.python.org/3/library/venv.html)

После этого следует установить необходимые библиотеки командой в терминале:
```commandline
pip install -r requirements.txt
```

Запуск
---
Плеер готов к работе! Запустите файл `server.py` командой:
```commandline
python server.py
```

Затем в браузере перейдите по адресу [http://127.0.0.1:5500/](http://127.0.0.1:5500/) и наслаждайтесь!))
