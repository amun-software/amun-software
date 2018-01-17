
## SPHINX

*SHINX* ist eine, auf der Microservice Architektur basierende, Anwendung, mit welcher Sentinel 2 - Aufnahmen im Browser gesucht und analysiert werden können.

Dieses Dokument beschreibt die Architektur des Gesamtsystems, sowie die unterstützten Funktionalitäten. 
### Architektur
SPHINX ist eine Komposition aus 4 Servern. 3 Server (Discovery, Processing und SPHINX-Frontend) sind Eigenentwicklungen. OpenCPU ist ein Dienst Dritter. 
![Architekturt](./Architektur.png)

#### Die Komponenten
Im Folgenden werden die selber entwicklenten Komponenten kurz vorgestellt. 
Eine aussührliche Beschreibung, sowie die jeweiligen Installationsanleitungen der Dienste, können den Service-spezifischen Dokumentationen zu entnehmen.
##### Discovery
Dieser Dienst dient der Bereitstellung von Metadaten und Tiles zuSentinel 2 - Aufnahmen.
Eine detaillierte Dokumentation des Servers kann unter der folgenden URL eingesehen werden:
[https://amun-software.github.io/Geosoft2DiscoveryService/](https://amun-software.github.io/Geosoft2DiscoveryService/)

#### Processing


#### SHINX-Frontend
