# Управление для ровера с манипулятором

Этот репозитории содержит исходные файлы для управление ровером и его манипулятором посредством web-интерфеса.


## Файлы 

<ul>
    <li><b>`app.py`</b> -  главный скрипт, который управляет ровером.</li>
    <li><b>`index.html`</b> - HTML-страница, на которой размещен джойстик для управления ровером.</li>
    <li><b>`joy.js`</b> - JavaScript-скрипт, который обрабатывает движения джойстика.</li>
    <li><b>`README.md`</b> - Этот файл.</li>
</ul>

## Зависимости

Этот проект использует следующие библиотеки:
<ol>
  <li>Flask</li>
  <li>OpenCV</li>
  <li>PySerial</li>
</ol>

## Использование

<ol>
<li>Загрузите файлы из этого репозитория на ваш компьютер.</li>
<li>Установите необходимые зависимости, выполнив <b>`pip install -r requirements.txt`</b> в терминале.</li>
<li>Подключите ровер к вашему компьютеру посредством точки доступа на ровере.
Запустите <b>`main.py`</b>.</li>
<li>Откройте браузер и введите адрес http://localhost:8080</li>
<li>Вы должны увидеть джойстик на странице. Двигайте его, чтобы управлять ровером.</li>
</ol>
