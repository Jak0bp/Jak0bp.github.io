# Wolkenhüpfer – Entwicklerwebsite

Website, Support, Impressum und Datenschutzerklärung für das iPhone-Spiel **Wolkenhüpfer** von **Jakob Peters Netzwerk- und Mediendesign**.

## Schnellstart auf GitHub

1. Unter dem GitHub-Konto **Jak0bp** ein öffentliches Repository mit dem Namen **jak0bp.github.io** erstellen. „Add README“ kann aktiviert sein.
2. Diese `README.md` als Inhalt der GitHub-README verwenden oder die dort automatisch erstellte Datei durch diese ersetzen. **Die README allein ist noch nicht die vollständige Website.**
3. Das ZIP-Paket auf dem Computer **entpacken**. Im Repository über **Add file → Upload files** die Dateien und den Ordner `assets` hochladen. Liegen diese Funktionen an anderer Stelle, im Repository zunächst die Ansicht „Code“ öffnen.
4. Alle unten genannten Dateien gehören direkt ins **Hauptverzeichnis**. Keinen zusätzlichen Ordner `Website` hochladen und nicht nur die ZIP-Datei ablegen. Die bestehende README kann unverändert bleiben, wenn ihr Inhalt schon übernommen wurde.
5. Den Upload mit **Commit changes** speichern.
6. Unter **Settings → Pages → Build and deployment** die Quelle **Deploy from a branch**, den Branch **main** und **/ (root)** wählen und speichern.
7. Warten, bis GitHub Pages die erfolgreiche Bereitstellung meldet. Danach die unten genannten Adressen im Browser testen. Wenn angeboten, **Enforce HTTPS** aktivieren.

Ein Build, Node.js oder ein kostenpflichtiger Hostingtarif ist für diese Website nicht erforderlich. Die Website startet über `index.html`; die README dient der Beschreibung des Repositorys und der Einrichtung.

## Dateien im Hauptverzeichnis

```text
jak0bp.github.io/
├── README.md
├── index.html
├── support.html
├── datenschutz.html
├── impressum.html
├── app-ads.txt
├── .nojekyll
└── assets/
    ├── style.css
    ├── favicon.svg
    └── spiel.png
```

`.nojekyll` ist eine versteckte, leere Datei. Sie ist im ZIP enthalten. Im Finder können versteckte Dateien mit Cmd + Shift + Punkt eingeblendet werden. Falls sie beim Browser-Upload fehlt, kann sie auf GitHub über „Add file → Create new file“ mit dem Namen `.nojekyll` und einer leeren Zeile als Inhalt angelegt werden.

## Adressen für App Store Connect

Diese Zieladressen funktionieren **nach erfolgreicher Veröffentlichung**:

| Feld | URL |
| --- | --- |
| Marketing URL / Entwicklerwebsite | https://jak0bp.github.io/ |
| Support URL | https://jak0bp.github.io/support.html |
| Privacy Policy URL / Datenschutz | https://jak0bp.github.io/datenschutz.html |
| Impressum | https://jak0bp.github.io/impressum.html |
| AdMob app-ads.txt | https://jak0bp.github.io/app-ads.txt |

Die Datei `app-ads.txt` muss an der Domainwurzel erreichbar sein. Deshalb wird das Repository `jak0bp.github.io` verwendet. Als Entwicklerwebsite im App-Store-Eintrag die Startseite hinterlegen. Die Dateiendung und Schreibweise **app-ads.txt** sind beabsichtigt.

## Google AdMob

Die `app-ads.txt` enthält den vom Betreiber mitgeteilten Eintrag:

```text
google.com, pub-5847887208197243, DIRECT, f08c47fec0942fa0
```

Nach dem Hochladen prüfen, dass die Datei unter der oben genannten URL als Text angezeigt wird, und die Verifizierung in AdMob abwarten. Die Datei autorisiert den Werbeverkäufer; sie fügt selbst keine Werbung in die Website oder App ein.

## Spiel und Datenverarbeitung

- iPhone-Spiel ab iOS 17 mit Einfinger-Steuerung, Erfahrungspunkten, Sternen und freischaltbaren Welten und Looks.
- Spielstand und Rekorde werden lokal gespeichert. Die Bestenlisten enthalten fiktive Gegner.
- Acht Saisonkollektionen mit insgesamt 16 dauerhaft freischaltbaren Welten und Looks sind über Apple StoreKit angebunden.
- Google AdMob ist für freiwillige Werbevideos mit einer zweiten Chance eingebunden; Google UMP verwaltet verfügbare Datenschutzoptionen.
- Aktueller App-Stand: nicht personalisierte Anzeigen, keine ATT-Abfrage, deaktivierte Publisher-First-Party-ID; maximale Werbe-Inhaltsbewertung **T / Teen**, keine Altersabfrage und konservative UMP-Unteralterskennzeichnung.
- Kein zusätzliches Firebase Analytics oder Google Analytics und keine zusätzlichen Mediation-SDKs.
- Die Website selbst lädt keine Werbe- oder Analyse-Skripte, externen Schriftarten oder Drittanbieter-Einbettungen. GitHub verarbeitet als Hoster technische Zugriffsdaten.

Die Zielgruppe „0–99 Jahre“ ist keine App-Store-Alterseinstufung. Die Teen-Inhaltsgrenze für Werbung ist keine Altersprüfung und keine Zusicherung, dass Werbeinhalte für Kleinkinder geeignet sind. Zielgruppen- und Werbekonfiguration müssen vor der App-Veröffentlichung dazu passend geprüft werden. Eine veröffentlichte Website bestätigt weder die App-Store-Zulassung noch die AdMob-Freigabe.

## Betreiber und Kontakt

**Jakob Peters**  
Jakob Peters Netzwerk- und Mediendesign  
Otto-Thiele-Str. 2  
21279 Hollenstedt, Deutschland

E-Mail: [mediennetzwerkdesign@gmail.com](mailto:mediennetzwerkdesign@gmail.com)

Registerangaben, Rechtsform oder Umsatzsteuer-/Wirtschafts-Identifikationsnummer müssen im Impressum ergänzt werden, soweit sie für den Betreiber vorhanden und vorgeschrieben sind. Private Steuernummern gehören nicht auf die Website. Der Datenschutztext ist bei Änderungen der App oder verwendeten Dienste mit anzupassen.

## Quellen zur Einrichtung

- [GitHub Pages einrichten](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Google app-ads.txt](https://support.google.com/admob/answer/9363762?hl=de)
- [Google Mobile Ads: Datenverarbeitung](https://developers.google.com/admob/ios/privacy/data-disclosure)
- [Google UMP](https://developers.google.com/admob/ios/privacy)

Stand: 31. Oktober 2026. Ein App-Store-Downloadlink wird ergänzt, sobald die App veröffentlicht ist.
