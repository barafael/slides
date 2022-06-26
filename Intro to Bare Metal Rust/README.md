# Eine Einführung in Bare Metal Programmierung in Rust

ADC++ 2022, Regensburg

Mikrocontroller ohne Betriebssystem sind ein zentraler Bestandteil vieler eingebetteter Systeme. Weil diese Systeme direkt mit der Außenwelt interagieren können, sind sie oft hohen Leistungs- und Sicherheitsanforderungen unterworfen. Diese decken sich mit einigen Werten und Konzepten des Rust Projektes: hohe Performance bei niedrigem Speicher- und Energiebedarf, definiertes Verhalten und sichere Nebenläufigkeit, sowie Compiler und Tooling, welche uns Entwicklern zur Seite stehen.
Natürlich gibt es auch Herausforderungen für Bare Metal Rust - die großzügige Nutzung (auch transitiver) Abhängigkeiten scheint zunächst ungewöhnlich, man begegnet mehrzeiligen Typsignaturen, und für Asynchronizität (Interrupts, DMA, oder Multitasking) wird mit verschiedenen Ansätzen experimentiert.
Wir werden in dieser Session von den Grundlagen der Rust Bare Metal Programmierung ausgehen, um dann Bibliotheken kennenzulernen, welche die Entwicklung portabler Treiber und deren Tests ermöglichen. Dabei werden uns einige Design Patterns, Architekturen, und Tools über den Weg laufen. Zu guter Letzt halten wir einen Ausblick auf Asynchronizität in Embedded Rust.
