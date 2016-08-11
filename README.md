# PHY9C

E&M with a Synaptics TouchPad.

1st Place Best Use of Touch Hardware at HackDavis 2016.

<img src="http://i.imgur.com/OanbfjK.gif">

## Install

PHY9C requires 
<ul>
  <li>A Synaptics TouchPad + the appropriate <a href="http://www.synaptics.com/resources">TouchPad drivers</a></li>
  <li>Python 2.7 or 3.X</li>
  <li>The <a href="http://www.ftdichip.com/Drivers/D2XX.htm">FTDI D2XX USB Chip driver</a> for your OS</li>
  <li>The <a href="https://sourceforge.net/projects/pywin32/">PyWin32 module</a> if using Windows</li>
</ul>

```bash
$ git clone https://github.com/leegabriel/PHY9C.git 
```

## Usage
1. Open up your terminal/command prompt
2. ```cd``` to the cloned directory (it should be called "em-simulator")
3. Type ``` $ python server.py ```, or ``` $ C:\Path\To\Python\Python\python.exe server.py ``` if you're on Windows and you haven't added Python to your path
4. Go to <a href="http://localhost:8080/">http://localhost:8080/</a>

## Disclaimer

The Python HTTP server, TouchPad, and related drivers were provided to us by Synaptics. No copyright infringement intended.
