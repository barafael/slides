# Programmierung in Rust für C- und C++-Entwickler

Die Entwicklung robuster und leistungsfähiger Systeme ist herausfordernd und birgt viele Überraschungen. Das Rust Projekt versucht, die Entwicklung und Gestaltung solcher Systeme zugänglicher, sicherer und produktiver zu machen. Während Rust in den letzten Jahren rapide an Beliebtheit gewinnt, wollen immer mehr Entwickler diese Sprache lernen und treffen dabei auf die berüchtigte steile Lernkurve. Doch so steil ist sie gar nicht! Ziel dieses Workshops ist es, fundamentales Verständnis zu vermitteln, um erfolgreich tiefer in die Sprache eintauchen zu können. Außerdem zeigen wir mit ein paar komplexeren Beispielen die Möglichkeiten von Rust im täglichen Gebrauch.
Zunächst werden wir mit einfachen Beispielprogrammen Syntax und Philosophie der Sprache erkunden und die Grundlagen in Aktion sehen. In interaktiven Übungen wird es dabei Gelegenheit für Praxis geben.
Anschließend werden wir Projekte im Mob-Programming-Stil bearbeiten. Dabei werden wir auch Tools zum Testen von Code, zum Linten, sowie zur Erzeugung von Metriken wie Testabdeckung, Binary Bloat, und Abhängigkeitsgrafen kennen lernen. Unser Ziel wird sein, in den fast vollständig implementierten Projekten ausgesuchte (und ausgeschilderte) Stellen zu reparieren oder zu erweitern. Jeder wird die Gelegenheit haben, als Navigator, Driver oder Member des Mobs an den Projekten teilzuhaben.
Folgende Projekte stehen uns zur Auswahl und werden auch kurz vorgestellt:

* Multithreaded Renderer für Julia-Fraktal [rayon, clap, klask]
* Interpreter für minimales LISP: Parser Library in C, Applikation in Rust in friedlicher Koexistenz [C-FFI]
* Async IO chat server/client [tokio, anyhow, clap, serde]
* Raspberry Pi LoRa transmitter/receiver mit CLI/GUI [thiserror, clap, klask, embedded-hal]
* Email parser in WebAssembly [WASM, cross compilation, serde, mail-parser]
* Treiber für SDP8xx Differential Pressure Sensor [embedded-hal, i2c, mocking]
* Minimale Quadkopter-Firmware [stm32f1, mpu6050, nrf24, embedded-hal]
