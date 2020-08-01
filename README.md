# Видеоплеер

Проект предназначен для создания видеоплеера киностудии.

### Пример работы:

![Player gif](example.gif)

[Сайт плеера](https://faholo.github.io/Video_player/index.html) 

### Установка

1. Python3 должен быть уже установлен.  

3. Рекомендуется использовать [virtualenv/venv](https://docs.python.org/3/library/venv.html) для изоляции проекта.

2. Используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
   ```
   pip install -r requirements.txt
   ```

4. Для автообновления сайта введите:
   ```
   livereload <путь к index.html>
   ```
   и откройте в браузере ссылку: 
   ```
   [I 200801 21:17:22 server:296] Serving on <место ссылки>
   ```
   Библиотека [livereload](https://github.com/lepture/python-livereload).

Инфо по настройке плеера [здесь](https://github.com/devmanorg/video-player-jslib)

### Цели проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
