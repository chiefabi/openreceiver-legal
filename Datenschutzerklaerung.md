# Datenschutzerklärung

## Verantwortlicher

Abdulkerim Sari
Königsteiner Str. 8
45145 Essen
E-Mail: a.saridevelop@gmail.com

## Was OpenReceiver tut – und was nicht

OpenReceiver ist eine Windows-Anwendung, die das Bildschirmbild eines iPhones per AirPlay-kompatiblem
Protokoll über das lokale Netzwerk empfängt und anzeigt.

- **Keine Cloud, kein Server des Anbieters.** Die Übertragung läuft ausschließlich direkt zwischen dem
  iPhone und diesem PC im selben lokalen Netzwerk. Es gibt keinen Server, über den Bild- oder Tondaten
  laufen, und der Anbieter hat zu keinem Zeitpunkt Zugriff auf diese Daten.
- **Keine Telemetrie.** Die App sendet keine Nutzungsdaten, Absturzberichte oder sonstige Daten an den
  Anbieter.
- **Lokal gespeicherte Daten.** Folgende Daten werden ausschließlich auf diesem PC gespeichert
  (`%APPDATA%\OpenReceiver\`), nie übertragen:
  - Einstellungen (z. B. gewählter Gerätename, Bildqualität) – `settings.json`
  - Liste der bereits gekoppelten iPhones (damit nicht bei jeder Verbindung erneut ein PIN-Code
    eingegeben werden muss) – `paired-devices.register`
  - ein für die Kopplung verwendeter, lokal erzeugter kryptografischer Schlüssel – `server-key.pem`
  - ein Protokoll zur Fehlersuche (`log.txt`), das nur auf ausdrücklichen Wunsch (Einstellung
    „Ausführliches Protokoll“) mehr als die üblichen Verbindungsereignisse enthält
- Diese Daten können jederzeit selbst gelöscht werden: über „Gekoppelte Geräte zurücksetzen“ in der App,
  oder durch Löschen des genannten Ordners, oder durch Deinstallation der App.

## Kauf über den Microsoft Store

Der Kauf der Vollversion (einmaliger Kauf) wird vollständig vom Microsoft Store abgewickelt. Der Anbieter
erhält dabei keine Zahlungs- oder Kontodaten – diese verarbeitet Microsoft als eigener Verantwortlicher.
Es gilt die Datenschutzerklärung von Microsoft:
https://privacy.microsoft.com/de-de/privacystatement

## Rechtsgrundlage

Soweit personenbezogene Daten überhaupt betroffen sind (siehe oben: ausschließlich lokal auf dem eigenen
Gerät), erfolgt die Verarbeitung zur Erfüllung der Funktion der Software (Art. 6 Abs. 1 lit. b DSGVO)
bzw. aufgrund eines berechtigten Interesses an der Fehlersuche (Art. 6 Abs. 1 lit. f DSGVO) bei
freiwillig aktiviertem ausführlichem Protokoll.

## Diese Website / dieses GitHub-Repository

Falls dieses Repository oder eine daraus erzeugte Website (z. B. GitHub Pages) genutzt wird, gelten
zusätzlich die Datenschutzhinweise von GitHub: https://docs.github.com/de/site-policy/privacy-policies/github-privacy-statement

## Ihre Rechte

Da die oben genannten Daten ausschließlich lokal auf Ihrem eigenen Gerät liegen und nie an den Anbieter
übertragen werden, lassen sich Auskunft, Berichtigung und Löschung direkt selbst vornehmen (siehe oben).
Für Fragen steht die oben genannte Kontaktadresse zur Verfügung.
