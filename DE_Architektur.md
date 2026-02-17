# Technische Anforderungen

Dieses Dokument beschreibt die technischen Voraussetzungen und Integrationsoptionen für die Nutzung der Oneboard-Plattform auf Kundenseite.

## 1. Systemvoraussetzungen

**Endgeräte**

- Betriebssystem: Windows, Linux, MacOS, Docker
- Freier Speicherplatz: mindestens 10 GB
- Internetverbindung: stabil, Router muss ggf. Ports für Proxy freigeben

**Modell**

- Einfachstes Modell: Lokale Instanz - keine Einrichtungskosten
- Windows Hosted Modell: VDI Instanz mit freigeschalteten Ports (4869, und für email: 993, 465) - geringe Einrichtungskosten
- Linux Hosted Modell: Terraform and Docker for organization wide unified installation or as a Service - SaaS

**Browser**

- Google Chrome – neueste Version

- erforderlich für das webbasierte Dashboard und administrative Funktionen

## 2. KYC Flow (Endkunden-Onboarding)

**Integration**

- Einfache Einbettung über einen kundenspezifischen Link
- Der Link kann direkt auf der Website des Kunden (z. B. Button oder Weiterleitung) hinterlegt werden (siehe Screenshot)
- Keine zusätzliche Softwareinstallation auf Endkundenseite erforderlich

![Onboardinglink](https://github.com/OneBoardGroup/Get-Started/blob/main/Onboardinglink.png?raw=true)

## 3. Compliance Cockpit (Interne Nutzung)

**Installation**

- Download der Oneboard Node-Applikation als lokale Anwendung auf dem Computer des Kunden
- Installation auf Windows-Systemen

**Sicherheitsarchitektur**

- Zugriff auf das Compliance Cockpit erfolgt lokal auf dem Computer
- End-to-End-verschlüsselte Verarbeitung der Daten
- Keine direkte Cloud-Abhängigkeit für den operativen Zugriff
- Speicherung gem. individueller Architektur (lokal / eigene Datenbank / Cloud)

**Netzwerk & Zugriff**

- Die Node kann einen Proxy bereitstellen
- Über diesen Proxy kann das Cockpit für alle Personen im selben Netzwerk freigeschaltet werden
- Voraussetzung:

- Die internen Internet- und Sicherheitseinstellungen müssen erlauben, dass die Node einen Proxy erstellt

**Benutzerverwaltung**

- Jede Person erstellt einen eigenen Login
- Anmeldung erfolgt mit:

- Klarnamen & biometrischem Abgleich

- Jeder Zugriff ist eindeutig einer Person zuordenbar

## 4. Datenweitergabe & Schnittstellen

**Integrationsmöglichkeiten**

- Anbindung an interne Systeme je nach Bedarf, z. B.:

- CRM, Core-Banking-Systeme, Interne Compliance- oder Archivsysteme

- Einrichtung von:

- Backup-Prozessen
- Datenexporten (strukturierte Formate)

**Vorgehen**

- Umfang und Art der Schnittstellen werden gemeinsam in einem technischen Abstimmungsmeeting definiert
- Ein Terms & Conditions Template wird zur Verfügung gestellt
- Anschließend erfolgt die gezielte Umsetzung und Konfiguration
