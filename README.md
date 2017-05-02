# Seminar 8
Testing mit Karma und Jasmine

# Cloud 9 Clone
Neues Projekt mit Blank Ubuntu und diesem Github https://github.com/juergen-hollfelder/seminar8.git

Nachträglich kann mit 
```bash
git clone https://github.com/juergen-hollfelder/seminar8.git
```
der Sourcecode geholt werden

# Setup
Installieren der neuesten Node Version mit
```bash
nvm install stable
```
Folgendes ist nicht notwendig, wenn man das Repo runtergeladen hat ...
```bash
# Installieren der Karma Module mit --save-dev werden sie in package.json abgespeichert
npm install karma karma-phantojs-launcher karma-jasmine jasmine-core --save-dev
```
... dann sollte man aber `node_modules` füllen mit
```bash
npm install
```
# Starten von Karma
Karma kann dann ständig laufen und führt Tests aus, sobald man an irgendeinem File etwas verändert hat
```bash
npm test
```

