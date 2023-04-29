# Control for a rover with a manipulator

This repository contains the source files for controlling the rover and its manipulator via the web interface.


## Files

<ul>
<li><b>`app.py`</b> - is the main script that controls the rover.</li>
<li><b>`index.html`</b> - is the HTML page on which the joystick for controlling the rover is placed.</li>
<li><b>`joy.js`</b> - is a JavaScript script that handles joystick movements.</li>
<li><b>`README-en.md`</b> - This file.</li>
</ul>

## Dependencies

This project uses the following libraries:
<ol>
<li>Flask</li>
<li>OpenCV</li>
<li>PySerial</li>
</ol>

## Usage

<ol>
<li>Upload files from this repository to your computer.</li>
<li>Install the necessary dependencies by running <b>`pip install -r requirements.txt `</b> in the terminal.</li>
<li>Connect the rover to your computer via the access point on the rover.
Run <b>`main.py `</b>.</li>
<li>Open the browser and enter the address http://localhost:8080 </li>
<li>You should see the joystick on the page. Move it to control the rover.</li>
</ol>
