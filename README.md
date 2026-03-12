# CSmon Add-on

**CSmon® Add-on** ist ein hochentwickeltes technisches Add-on (TA) mit integrierten Visualisierungen für das SAP-Monitoring. Es dient als Brücke zwischen dem **CSmon Monitoring Server** und **Splunk**.

## Features

* **Echtzeit-Monitoring**: Überwachung von SAP-Hana-Datenbanken und SAP-Applikationsservern.
* **Modernes UI & UX**: Hochperformante Splunk UI Dashboards mit voller **Dark & Light Mode** Unterstützung.
* **Responsive Design**: Optimale Darstellung auf verschiedenen Bildschirmgrößen und Endgeräten.
* **Optimierte Performance**: Minimale Bundle-Größen für schnelle Ladezeiten im Browser.

## Installation

1. Download and install the **CSmon Add-on** from Splunkbase or via the "Install app from file" menu.
2. Navigate to the App's configuration page in Splunk.
3. Set up the connection to your **CSmon® Monitoring Server**.
4. Specify the `index` where CSmon data is stored (Information -> Configuration -> Global Settings).
5. Define the system scope (Information -> Configuration -> System Scope) [default: prefilled].
6. Ensure your data inputs are using the sourcetype `csmon:hostperf` or `csmon:serviceperf`.

## Demo Mode

Die App verfügt über einen integrierten **Demo-Mode**. Falls Sie noch keine Verbindung zu einem aktiven CSmon-Server haben, können Sie diesen in den Einstellungen aktivieren, um die Dashboards mit Mock-Daten (Beispieldaten) zu testen.

## Dokumentation

Detaillierte Informationen zur Einrichtung finden Sie in der integrierten Hilfe des Add-ons.
