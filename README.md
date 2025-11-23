# Automatisierung-von-X.509--Zertifikaten-durch-Sectigo-Certificate-Manager

Dieses Repository enthält die technische Dokumentation und den Projektbericht zur Implementierung einer automatisierten Zertifikatsverwaltung in einer Enterprise-Umgebung.

Das Projekt wurde im Rahmen eines Praktikums beim Westdeutschen Rundfunk (WDR) durchgeführt und akademisch an der Universität Bonn ausgearbeitet.

## 📄 Projektbericht

👉 **[Hier klicken, um den vollständigen Bericht zu lesen (PDF)](Projektbericht_X509_Automatisierung.pdf)**

*(Hinweis: GitHub öffnet die PDF direkt im Browser)*

## 🔍 Projektübersicht

Ziel des Projekts war die Ablösung manueller Zertifikatsprozesse durch eine vollautomatisierte Lösung mittels **Sectigo Certificate Manager (SCM)**, um Sicherheitsrisiken durch abgelaufene Zertifikate zu minimieren.

### Technische Schwerpunkte
* **PKI-Automatisierung:** Konfiguration von "Auto-Installation" und "Auto-Renewal" für X.509-Zertifikate.
* **Network Agents:** Implementierung und Konfiguration von Sectigo Network Agents.
* **Plattformen:**
    * **Windows:** Integration mit Microsoft IIS (Port 443 Bindings).
    * **Linux:** Integration mit Apache Webserver (inkl. SSH-Verbindung und Bash-Scripting für automatische Neustarts).
* **Sicherheit:** Analyse von Berechtigungskonzepten (sudoers) im Kontext der Automatisierung.

## 🛠 Technologien & Tools
* Sectigo Certificate Manager (SCM)
* X.509 / PKI / SSL / TLS
* Linux (Ubuntu/WSL), Bash Scripting
* Windows Server, IIS
* OpenSSL
