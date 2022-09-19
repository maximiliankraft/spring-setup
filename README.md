### 1. Hausübung

Erstelle ein neues Spring-Basisprojekt auf [start.spring.io](http://start.spring.io). Verwende als Javaversion die Nummer 18.

Das Projekt soll folgende Metadaten enthalten:

 - Group `at.spengergasse`
 - Artifact `spengermed`
 - Name `Spengermed`
 - Package name `at.spengergasse.spengermed`

 Füge als Dependencies hinzu:
 - spring web
 - lombok
 - mysql driver
 - rest repositories
 
 Falls du welche vergessen hast kannst du sie auch nachträglich über die pom.xml nachbessern.


Entpacke das Basisprojekt in das bereits bestehende Repository `spengermed`. Commite und pushe die neuen Dateien und stelle sicher dass alle Tests erfolgreich waren. Die Tests kannst du entweder über `mvn test` ausführen. Oder über die Github-Actions. Füge dazu in dein `spengermed`-Repository den in diesem Repository vorhandenen `.github`-Ordner ein. Darin ist beschrieben wie auf den Servern von Github die Tests remote ausgeführt werden können.