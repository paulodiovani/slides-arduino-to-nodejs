
# Arduino to Node.js
# <i class="br br-arduino-notext"></i> ⬌ <i class="br br-nodejs"></i> &nbsp;

_Sending messages from [Arduino][ino] board to a [Node.js][node] application._

<small>Version 0.1.0</small>

[ino]: http://arduino.cc/
[node]: https://nodejs.org/

====

<!-- .slide: class="half-slide" data-background="url(img/paulodiovani.jpg)" data-background-size="contain" data-background-repeat="no-repeat" data-background-position="right" -->

### <i class="fa fa-user"></i> Paulo Diovani Gonçalves

Technologist in Internet Systems by Feevale University.
Software Enginer at Codeminer 42.
GNU/Linux user since 2005.

[blog.diovani.com][blog]

[slides.diovani.com][slides]

[@paulodiovani][twitter]

[![codeminer42][code-logo]][code-site] <!-- .element: class="no-border no-background" -->

[avatar]: img/avatar.jpg
[blog]: http://blog.diovani.com
[slides]: http://slides.diovani.com
[twitter]: http://twitter.com/paulodiovani
[code-logo]: img/codeminer42.png
[code-site]: http://codeminer42.com/

====

# <i class="br br-codeminer" style="font-size: 3em;"></i>

**we're hiring**<br>
[become@codeminer42.com](mailto:become@codeminer42.com)

----
<!-- .slide: data-background="linear-gradient(rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), url(img/lazy-parking.jpg)" data-background-size="cover" -->

A proof of concept for...

# <i class="fa fa-map-marker"></i> <i class="fa fa-car"></i>
## Lazy Parking

_Internet Systems Technology &ndash;
[Feevale University](http://feevale.br)_<br>
_Interdisciplinary Project I &ndash; 2015_

====
<!-- .slide: data-background="linear-gradient(rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), url(img/johnny-five.jpg)" data-background-size="cover" -->

# <i class="br br-johnny-five"></i>

### We're not talking about Johnny-Five. Sorry.

But worth take a look at [johnny-five.io](http://johnny-five.io/).

Note:
Johnny-Five is a Node.js Library used for
prototyping with many different board.

----

## Writing Arduino code

The arduino _sketch_ structure.

```cc
void setup()
{
    // Called when a sketch starts
    // Use it to initialize variables, pin modes, etc.
    // Runs once
}

void loop()
{
    // Called just after setup()
    // Use it to actively control the Arduino board.
    // Loops consecutively.
}
```

Note:
Arduino code is based on C++ but with
it's own commands and librearies

====
<!-- .slide: data-background="linear-gradient(rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), url(img/arduino-ultrasonic.jpg)" data-background-size="cover" -->

# <i class="fa fa-question-circle-o"></i>

### How to send sensor data to a web server?

We're using a ultrasonic sensor for example,
but could be any sensor. <!-- .element: class="small" -->

- ~~Serial/USB port~~
- TCP Socket

http://blog.filipeflop.com/sensores/sensor-ultrassonico-hc-sr04-ao-arduino.html <!-- .element: class="credits" -->

Note:
For serial/USB port the Arduino must be
physicaly conected to the server.

====
<!-- .slide: data-background="linear-gradient(rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), url(img/arduino-ethernet.jpg)" data-background-size="cover" data-background-position="center" -->

## Arduino Ethernet Shield

https://www.arduino.cc/en/Main/ArduinoEthernetShield

- Allow TCP/IP connections
- Can get a DHCP address
- Read/Write to SD Card

http://www.arduino.cc <!-- .element: class="credits" -->

====

### Assembling Ethernet Shield

![ethernet-assembly](img/arduino-ethernet-assembly.jpg)

https://www.flickr.com/photos/bpunkt/3141966707 <!-- .element: class="credits" -->

====

### Assembling Ultrasonic Sensor

![ultrasonic-assembly](img/arduino-ultrasonic-assembly.png)

http://blog.filipeflop.com/sensores/sensor-ultrassonico-hc-sr04-ao-arduino.html <!-- .element: class="credits" -->

----

# Questions?

====

## Bibliografy


====

### Credits

by Paulo Diovani Gonçalves

<small>[paulo@diovani.com]((mailto:paulo@diovani.com)</small>

_powered by: [reveal.js](http://lab.hakim.se/reveal-js/)_

<small>[http://lab.hakim.se/reveal-js/](http://lab.hakim.se/reveal-js/)</small>

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" /></a>
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Docker for Lazy People</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://diovani.com" property="cc:attributionName" rel="cc:attributionURL">Paulo Diovani</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
