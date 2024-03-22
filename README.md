# Rework Embody-Experiment
Based on: https://version.aalto.fi/gitlab/eglerean/embody

### 1. XAMPP installieren
  - https://www.apachefriends.org/de/index.html

### 2. XAMPP-Ordner finden + Initiale php-Einstellungen
  - unter `C:/xampp/php`
  - `php.ini` Datei finden und mit Text-Editor öffnen
  - `max_input_vars` finden, ";" löschen und die Zahl ändern (bsp. 1 000 000)
<a href="https://drive.google.com/uc?export=view&id=1AhVlzpFhCgHePfHVo8eTZyKCRSF2Amha"><img src="https://drive.google.com/uc?export=view&id=1AhVlzpFhCgHePfHVo8eTZyKCRSF2Amha" style="width: 500px; max-width: 100%; height: auto" title="Click here if nothing is shown." /></a>

### 3. Ordner kopieren
- `embody`-Ordner nach `C:/xampp/htdocs` kopieren
- check ob im v1-Ordner ein **subjects-Ordner** zu finden ist

### 4. Pfad für die Bilder ändern (optional - falls Ordnerstruktur anders benannt)
- `settings.php` im v1 ordner finden und öffnen
- `$path`-Variable ändern zum v1 Ordner

<a href="https://drive.google.com/uc?export=view&id=1dbUVvfKUYnsMIpbd5APCvvN_er3ze-Ww"><img src="https://drive.google.com/uc?export=view&id=1dbUVvfKUYnsMIpbd5APCvvN_er3ze-Ww" style="width: 500px; max-width: 100%; height: auto" title="Click here if nothing is shown." /></a>

### 5. Experiment starten
- Control Panel starten
- `Apache`-Server starten
- im Browser [localhost](http://localhost/embody/v1/)http://localhost/embody/v1/ eingeben (bzw. je nach Ordnerstruktur die Namen ändern)

### 6. Experiment-spezifisches
- Erste Seite auf `register` klicken für neuen Participant
- Demographischer Fragebogen ausfüllen
- Erklärtext
- Pro Emotion die Körper bemalen
- CSV-Dateien werden automatisch geschrieben, sobald auf "click here when done" geklickt wird
- CSV-Dateien haben pro Emotion immer die gleiche Nummerierung (bsp. Love = 8)
- Pro Participant gibt es je einen eigenen Ordner im Subjects-Ordner, dort sind auch alle CSV-Dateien
