<!-- Плеер будет создан с задержкой, после того как загрузятся все ресурсы на странице. Для этого используется событие `DOMContentLoaded`. Благодаря этой особенности можно вызывать функцию `createPlayer` раньше, чем загрузятся все необходимые библиотеки: jQuery и Playable.
 -->

# Видеоплеер

Учебный проект для курсов web-разработчиков [dvmn](https://dvmn.org).
Построен на базе библиотеки [Playable](https://wix.github.io/playable/).
Сайт с видеоплеером доступен [по этому адресу](https://ilyag96.github.io/video-player-jslib/player/index.html).

<img src="https://github.com/IlyaG96/video-player-jslib/blob/master/screenshots/player.png?raw=true" width="50%" height="50%">

## Установка

Клонируйте репозиторий или [скачайте архив с кодом](https://github.com/IlyaG96/video-player-jslib/archive/refs/heads/master.zip):
```bash
git@github.com:IlyaG96/video-player-jslib.git
```

## Запуск с использованием python3
<details>
<summary>Запуск с использованием python3</summary>

Если вы планируете изменять и дорабатывать плеер, то возможно использование python и библиотeки livereload.

Создайте виртуальное окружение:

```bash
cd video-player-jslib
python3 -m venv env
```

Активируйте виртуальное окружение и установите все необходимые пакеты.
```bash
source env/bin/activate
pip install -r requirements.txt
```
Запустите скрипт командой:
```shell
livereload player
```
Сайт будет доступен [по этому адресу](http://127.0.0.1:35729)
</details>

## Запуск без использования python3
<details>
<summary>Запуск без использования python3</summary>

Откройте index.html в папке player и подождите, пока плеер загрузится.
</details>



