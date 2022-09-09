## Горячая перезагрузка

1. Качаем и устанавливем ласт версию питона https://www.python.org/downloads/
2. Открываем консоль и пишем `py -V`  должно показать какая версия питона установлена у меня например `Python 3.10.5`  если после  ввода `py -V` не показало версию пробуем написать `python -V`  если в этот раз версию не показало значит что python не установлен пробуем установить еще раз.
3. Далее в консоль пишем `python -m http.server` это запустит локальный http сервер на 8000 порту.
4. Переходим в браузере по `http://localhost:8000/` откроется древо файлов локальной машины, находим папку с вашим проектом и открываем нужный html
5. В том html файле который вы открыли в браузере в теге head нужно добавить `<script type="text/javascript" src="https://livejs.com/live.js"></script>`. Пример файла можно посмотерь в этом репозитории `index.html`
6. Готово! Теперь когда вы будете делать изменения в html файле браузер будет обновляться, так же обновления будут происходить если делать изменения в подключеном css файле 