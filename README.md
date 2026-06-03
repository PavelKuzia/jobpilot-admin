# DIGITALES JOB BERATER

### PROBLEMSTELLUNG

Immer wieder hört man in Deutschland, dass die Lage am Arbeitsmarkt angespannt ist. Außerdem weist der Arbeitsmarkt aufgrund von Entstehen neuen Technologien höhe Dynamik auf. Folglich steigt der Bedarf nach Spezialisten, die den Arbeitsmarks analyzieren und Beratung in Jobsuche anbieten.

Das Ziel des Projektes, ein digitales Partner der Arbeitsuchenden zu werden und die Jobsuche leicht zu machen, indem es:

- Stellenausschreibungen von mehreren Platformen analysiert
- Information über Arbeitgeber zur Verfügung stellt
- Die Jobanforderungen verarbeitet und eine Analyze darüber bietet
- Filtert alle Jobs, die nicht zum Bewerberprofil passen
- Lässt die Dynamik auf dem Arbeitsmarkt visuell verfolgen
<hr>

### ARCHITEKTUR

![My Project Screenshot](assets\architecture\DigitalJobAssistentArchitecture.jpg)

<hr>

### TECH-STACK

<b>INFRASTRUKTUR</b></br>
&emsp;**Docker Compose**: für Dev Entwicklungsumgebung</br>
&emsp;**Kubernetes**: für Prod Entwicklungsumgebung</br>

<b>BACKEND</b></br>
&emsp;**Java (Spring Boot)**: Verwalter, der alle Anfragen verarbeitet und Kommunikation mit Jobs, KI Systemen und Datenbanken ermöglicht</br>
&emsp;**Python (Selenium, TaskIQ, FastAPI)**: Jobs, die Daten von unterschiedlichen Diensten auf Anfrage sammeln und an die Spring Boot Application zurückgeben</br>
&emsp;**RabbitMQ**: Nachrichtenvermittler, der Systementkopplung ermöglicht</br>
&emsp;**PostgreSQL**: Datenbank</br>
&emsp;**Redis**: In-Memory-Datenbank</br>

<b>FRONTEND</b></br>
&emsp;**React (TypeScript)**: SPA (Single Page Application)

<hr>

#### LINK ZUM CODE

https://github.com/PavelKuzia/jobpilot</br>
<i>private repo - für Zugriff bitte um Anfrage</i>
