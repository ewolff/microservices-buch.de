---
layout: default
title: "Microservices-Buch - Errata"
description: Errata für das Microservices-Buch
---

Errata
---

### Kapitel 1 - Vorwort

p. 5, Marginalie "Unabhängige Skalierung": Jeder Microservice kann
      unabhängig von den anderen Services skaliert werden kann. Der
      Satz enthält ein "kann" zu viel am Ende.

Danke an [Etlam Nahkcip](https://twitter.com/Coderebelll)

### Kapitel 4 - Was sind Microservices?

p.52 "CONFORMIST oder CUSTOMER/SUPPLIER hingegen binden die
      Domänenmodelle sehr eng aneinander und die Teams müssen sich
      dann eng absprechen, wenn ihre Microservices eine solche
      Kollaboration nutzen (siehe Abb. 4–5)." Die Aussage findet sich
      in der Abbildung nicht wieder. Dort hat CONFORMIST wenig
      Koordinierungsaufwand, aber CUSTOMER/SUPPLIER viel.

Der Text ist falsch, die Abbildung ist richtig. Beide Modelle binden
      tatsächlich die Modelle sehr eng, aber bei CUSTOMER/SUPPLIER
      bedeutet, dass sich die Teams abstimmen, währen bei CONFORMIST
      das gerade nicht der Fall ist. Das eine Team nutzt einfach das
      Modell des anderen - ohne weitere Abstimmung.

Danke für den Hinweis an Rubén Elías Lara Tello!

      
### Kapitel 8 - Architektur von Microservice-Systemen

p. 150 In Abbildung 8-16 soll der Kasten "Standard Service Security"
      eigentlich mit "Standard Security" beschriftet sein.

Die Literaturangaben [7]-[11] für Abschnitt 8.10 sind in
      Abschnitt 10.8 zu finden - nicht Abschnitt 8.14 wie für den Rest
      des Kapitels.

p. 150 In Abbildung 8-16 soll der senkrechte Strich mit "vertikaler
      Skalierung" beschriftet sein.

### Kapitel 9 - Integration und Kommunikation

p.183 (Abschnitt 9.3): Der Satz "Jede Station kann als ein Teil der
      Nachricht verarbeitet oder an andere Empfänger verschickt
      werden." ist falsch. Richtig: "Jede Station kann ein Teil der
      Nachricht verarbeiten oder an andere Empfänger verschicken."

p. 186 (Abschnitt 9.4): AMQP steht für "Advanced Message
      Queuing Protocol".

p. 192 (Abschnitt 9.6): Der Verweis auf Literaturangabe [6]
      ist falsch. Richtig ist [26].

### Kapitel 10 - Architektur eines Microservices

p. 271 (Abschitt 12.8): Der Link bei Literaturangabe [19] ist
      falsch. Richtig ist <https://www.elastic.co/products/elasticsearch>. 

 Ebenso ist die Literaturangabe [20] für Kibana falsch - sie gilt
      für Redis. Richtig ist <https://www.elastic.co/products/kibana>.
      

### Kapitel 12 - Betrieb und Continuous Delivery von Microservices

p. 214 (Abschitt 10.6): Der Verweis auf Literaturangabe [14] für
      Play ist falsch. Richtig ist [15].

### Kapitel 13 - Organisatorische Auswirkungen der Architektur

p. 288 (Abschitt 13.4): Der Verweis auf Literaturangabe [2]
      für Developer Anarchy ist falsch. Richtig ist [1].


### Kapitel 14 - Ein Beispiel für eine Microservices-Architektur

In Abschnitt 14.1 wird Spring Cloud vorgestellt. Die Technologie hat
      mittlerweile Unterstützung für viel mehr Frameworks u.a. auch
      Consul für Service Discovery.

Abschnitt 14.7 zeigt das Listing für Docker Compose 1.0. Im git
      Repository ist mittlerweile die Datei für Docker Compose 2.0.

In 14.15 (Links und Literatur) ist Link 9 falsch. Richtig
      wäre <https://github.com/netflix/eureka>.

### Kapitel 15 - Technologien für Nanoservices

p. 349, 15.3 Neben Java und JavaScript unterstützt Amazon Lambda nun
      auch Python als Programmiersprache.

p. 350, 15.3 Es ist mittlerweile möglich, mit dem API-Gateway auch
      REST-Services mit Lambda zu entwickeln.

Danke für den Hinweis an Niko Köbler!

p. 368, 15.10 Link 14 sollte auf
      <http://senecajs.org/getting-started/> verweisen. Link 22 sollte
      auf <https://github.com/ewolff/war-demo> verweisen. Link 24
      sollte auf
      <https://github.com/vert-x3/vertx-examples/tree/master/maven-simplest>
      verweisen.

