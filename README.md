# Kekish Newsreel Reporter

Kooperatives Reporter-Horrorspiel für 1–4 Spieler. Gemeinsam verborgene Orte entdecken, Beweise fotografieren und die nächste Sendung zusammenstellen.

## Spielen

[Windows-Client herunterladen](https://github.com/GG2EZBoOm/reporter/releases/download/v2026.10.21.5/Kekish-Newsreel-Reporter-2026.10.21.5-Windows.zip)

Die Datei **Kekish-Newsreel-Reporter-2026.10.21.5-Windows.zip** vollständig entpacken und **Spielen.cmd** starten. Unity und Unity Hub werden zum Spielen nicht benötigt. Download rund 212 MB, entpackt rund 275 MB.

Der Host legt Schwierigkeit und Einsatzzeit fest. Andere Reporter können über eine Host-IP, einen KNR1-Einladecode oder die Discord-Anbindung beitreten. Für Internet-Multiplayer muss der Host auf **UDP 7777** erreichbar sein oder ein gemeinsames virtuelles Netzwerk genutzt werden. Ein Relay-Server ist nicht enthalten.

Steuerung, weitere Hinweise sowie Quellen- und Lizenzangaben liegen im Client-Paket.

## Automatische Updates

Dieses Repository dient als Download- und Updatekanal für den Windows-Client. Vor dem Hauptmenü prüft das Spiel das neueste Release. Währenddessen zeigt der Fernseher Rauschen und den Fortschritt. Geänderte Dateien werden einzeln heruntergeladen und per SHA-256 geprüft; anschließend startet der Client neu.

**knr-update.json** und die **file-*.zip**-Dateien in den Releases sind für den Auto-Updater bestimmt. Für die erste Installation genügt das große Windows-ZIP.

Der Unity-Projektquellcode ist in diesem Repository derzeit nicht enthalten.