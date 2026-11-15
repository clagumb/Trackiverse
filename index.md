# Datenschutzerklärung & Impressum / Privacy Policy & Legal Notice

**Stand / Last Updated:** 15. November 2026

---

## Deutsch

### 1. Impressum (Angaben gemäß § 5 TMG / § 18 Abs. 2 MStV)

**Verantwortlicher im Sinne der DSGVO:**
Claus Gumbmann
Heinrich-Böll-Str. 29
90587 Veitsbronn
Deutschland

**Kontakt:**
E-Mail: spalier-02talg@icloud.com

---

### 2. Grundsatz: Maximale Privatsphäre & Lokale Datenhaltung

Diese Datenschutzerklärung gilt zentral für alle Anwendungen im **Trackiverse**. Sämtliche Apps können grundsätzlich ohne Registrierung genutzt werden. Ihre Daten verbleiben weitestgehend auf Ihrem eigenen Gerät:

- **Kein Tracking & Keine Werbung:** Es werden keine Werbenetzwerke, keine Analytics-Tools und keine Tracking-Dienste eingesetzt.
- **Kein Benutzerkonto:** Es ist keine Registrierung, keine Anmeldung und keine Eingabe persönlicher Identifikatoren (wie Name oder E-Mail-Adresse) erforderlich.
- **Lokale Speicherung:** Alle Zeiten, Beträge, Standorte, Fotos usw. verbleiben ausschließlich auf Ihrem eigenen Gerät. Es existiert grundsätzlich kein Server-Backend – mit Ausnahme der optionalen, freiwilligen Community-Ranglisten im *Kennzeichen-Tracker* und *Klimmzug-Tracker* sowie externer Abrufe (Open-Meteo, Open Library), sofern Sie diese Funktionen nutzen.

---

### 3. Modulübersicht & Spezifische Datenerfassung

Jedes Modul arbeitet eigenständig und verarbeitet personenbezogene Daten nur, soweit dies für die jeweilige Funktionsweise erforderlich ist:

- 🏔️ **Bergschein-Tracker:** Erfassung des persönlichen Bergkirchweih-Status (z. B. Mythos-Stufe, Geschlecht, Fortschritt) sowie Datum und Uhrzeit der Aktivität. *(100 % lokal)*
- 🍺 **Biermass-Tracker:** Erfassung und Verwaltung des Bierkonsums (Anzahl der Mass, Datum, optionaler Standort nur bei ausdrücklicher Einwilligung). *(100 % lokal)*
- 🧊 **Eisbad-Tracker:**
  - **Lokal gespeicherte Daten:** Dauer des Bads (Plan vs. Ist bei vorzeitigem Abbruch), optional manuell eingegebene Wassertemperatur, optional Standort (nach Einwilligung in den Geräte-Standort ungefähr/genau oder nach manueller Ortsangabe) sowie – nur falls ein Standort vorliegt – die von Open-Meteo abgerufene Außentemperatur. *(lokal)*
  - **Abruf von Wetterdaten (Open-Meteo):** Sobald für einen Eintrag ein Standort vorliegt, wird die Außentemperatur (Lufttemperatur) immer bei Open-Meteo (OpenMeteo GmbH, Schweiz) abgefragt. Ein Standort liegt vor, wenn Sie den Geräte-Standort (ungefähr oder genau) freigegeben haben **oder** den Ort manuell gesetzt haben. Dabei werden technisch bedingt die IP-Adresse Ihres Geräts sowie die Koordinaten des Eintrags übertragen. Open-Meteo kann Verbindungsdaten (z. B. IP-Adresse, aufgerufene URL, Koordinaten) für Betrieb und Missbrauchsschutz in Server-Logs speichern und löscht diese nach eigenen Angaben nach 90 Tagen. Es wird kein Benutzerkonto bei Open-Meteo angelegt. Die zurückgelieferte Außentemperatur wird anschließend nur lokal auf Ihrem Gerät gespeichert. Eine manuelle Eingabe der Außentemperatur ist nicht möglich. Ohne Standort findet kein Abruf statt und es wird keine Außentemperatur gespeichert.
- 🍦 **Eiskugeln-Tracker:** Erfassung und Verwaltung des Eis-Konsums (Kugeln, Datum, optionaler Standort nur bei ausdrücklicher Einwilligung). *(100 % lokal)*
- ☕ **Espresso-Tracker:** Erfassung und Auswertung getrunkener Espressos (Datum und Uhrzeit, Anzahl der Espressos, optionaler Standort nur bei ausdrücklicher Einwilligung). *(100 % lokal)*
- 🍷 **Glühwein-Tracker:** Erfassung und Verwaltung des Glühweinkonsums (Anzahl der Tassen/Becher, Datum, optionaler Standort nur bei ausdrücklicher Einwilligung). *(100 % lokal)*
- 🚗 **Kennzeichen-Tracker:**
  - **Lokal gespeicherte Daten:** Erfassung von Kfz-Kennzeichen (Kürzel, Ort, Zusatzinfos), Status (gesehen/ungesehen) sowie optional Datum, Standort oder persönliche Notizen. *(ohne Rangliste 100 % lokal)*
  - **Optionale Community-Ranglisten:** Nur wenn Sie aktiv einen Nickname registrieren und Ihre Stände teilen, werden Ihr frei gewählter Nickname, eine lokal erzeugte anonyme Geräte-/Benutzer-ID (UUID), die jeweilige Anzahl gesichteter Kennzeichen/Bezirke (je Land: DE, AT, CH, FR sowie gesamt), Ihre beste Platzierung und der Zeitstempel der Aktualisierung an das Ranglisten-Backend übertragen und dort gespeichert. Konkrete Kennzeichen, Orte, Standorte oder persönliche Notizen werden **nicht** übertragen.
- 🏋️ **Klimmzug-Tracker:**
  - **Lokal gespeicherte Daten:** Erfassung und Verwaltung von Klimmzug-Fortschritten (Anzahl der Klimmzüge, ggf. Zusatzgewicht, Datum). Das Modul nutzt zudem lokale Benachrichtigungen, um Sie an das Ende einer Satzpause zu erinnern. *(ohne Rangliste 100 % lokal)*
  - **Optionale Community-Ranglisten:** Nur wenn Sie aktiv einen Nickname registrieren und Ihre Werte teilen (Teilnahme ab mindestens 3 verschiedenen Trainingstagen), werden Ihr frei gewählter Nickname, eine lokal erzeugte anonyme Geräte-/Benutzer-ID (UUID), Ihre Gesamtzahl an Klimmzügen, ggf. das gesamte bewegte Zusatzgewicht, Ihre beste Platzierung und der Zeitstempel der Aktualisierung an das Ranglisten-Backend übertragen und dort gespeichert. (Die Anzahl der Trainingstage wird nur bei der Übermittlung zur Teilnahmeprüfung geprüft und nicht im Ranglisteneintrag gespeichert.)
- 🍪 **Lebkuchen-Tracker:** Erfassung von Datum und Uhrzeit des Lebkuchen-Konsums. *(100 % lokal)*
- 📖 **Lesen-Tracker:**
  - **Lokal gespeicherte Daten:** Buchdetails (Titel, Autor, ISBN, Seitenanzahl, Genre), lokale Pfade zu heruntergeladenen Buchcovern, Lese-Sitzungen (Start-/Endzeitpunkt) sowie persönliche Bewertungen.
  - **Abruf von Buchdaten (Open Library):** Um das Hinzufügen von Büchern per ISBN-Suche zu erleichtern, werden Anfragen ausschließlich an den freien Dienst Open Library (Internet Archive) gesendet. Hierbei werden die gesuchte ISBN sowie technisch bedingt die IP-Adresse Ihres Geräts an Open Library übertragen.
- 🍾 **Pfand-Tracker:** Erfassung und Verwaltung von Pfandbeträgen. Es werden **ausschließlich das Datum der Erfassung und der Pfandbetrag in Euro** lokal auf dem Gerät gespeichert. *(100 % lokal)*
- 🍕 **Pizza-Tracker:** Erfassung und Verwaltung von Pizzen (Durchmesser, daraus berechnete Fläche, Datum und Uhrzeit der Erfassung, optionaler Standort nur bei ausdrücklicher Einwilligung). Vergleichsflächen (z. B. Sportfelder) werden ausschließlich lokal aus den erfassten Daten berechnet. *(100 % lokal)*
- 🧩 **Puzzle-Tracker:** Erfassung und Auswertung von Puzzles (z. B. gelöst, in Arbeit). Es werden Datum und Uhrzeit der Erfassung, Puzzle-Details (z. B. Titel/Typ, Status, Dauer) sowie optional Fotos des Puzzle-Fortschritts lokal gespeichert. *(100 % lokal)*
- 💶 **Trinkgeld-Tracker:** Eigenständige Erfassung und Berechnung von Schichteinnahmen, Arbeitszeiten und Trinkgeldern für Servicekräfte. *(100 % lokal)*

---

### 4. Besondere Funktionen & Geräteberechtigungen

- **Teilen-Funktion:** Das Teilen von Ständen erfolgt ausschließlich manuell auf Ihre ausdrückliche Initiative hin über die vom Betriebssystem bereitgestellten Funktionen.
- **Community-Ranglisten (Firebase / Google Cloud):** Die Teilnahme an den Ranglisten im *Kennzeichen-Tracker* und *Klimmzug-Tracker* ist freiwillig. Das Backend wird über Firebase (Cloud Functions und Cloud Firestore, Google Cloud Platform) in der EU-Serverregion `europe-west3` (Frankfurt am Main, Deutschland) betrieben. Bei der Nutzung werden technisch bedingt die IP-Adresse Ihres Geräts sowie – bei aktiver Teilnahme – Ihr Nickname, die anonyme UUID zur Kontozuordnung, Ihre Ranglistenwerte und Aktualisierungszeitstempel verarbeitet. Öffentlich in der Rangliste sichtbar sind ausschließlich Ihr Nickname, Rang, Score (bei Klimmzug ggf. inkl. Zusatzgewicht), Ihre beste Platzierung und der Zeitstempel der letzten Aktualisierung; die UUID wird nicht öffentlich angezeigt. Sie können Ihre Ranglisteneinträge sowie Ihren Nickname inklusive aller zugehörigen Serverdaten jederzeit direkt in den App-Einstellungen wieder löschen.
- **Kamera:** Wird im *Lesen-Tracker* (zum Scannen des ISBN-Barcodes) und im *Puzzle-Tracker* (zum optionalen Festhalten des Puzzle-Fortschritts per Foto) angefragt. Alle Aufnahmen verbleiben ausschließlich lokal auf Ihrem Gerät.
- **Benachrichtigungen:** Wird im *Klimmzug-Tracker* angefragt, um Sie nach dem Ablauf von Satzpausen lokal auf Ihrem Gerät zu benachrichtigen. Es werden dabei keinerlei Daten an Server übertragen.
- **Wetterdaten (Open-Meteo):** Wird im *Eisbad-Tracker* immer dann genutzt, wenn ein Eintrag einen Standort hat (Geräte-Standort ungefähr/genau nach Einwilligung oder manuell gesetzter Ort), um die Außentemperatur abzurufen. Die Außentemperatur kann nicht manuell eingegeben werden. Übertragen werden IP-Adresse und Koordinaten. Ohne Standort erfolgt kein Abruf. Es findet keine dauerhafte Standortübermittlung und kein Tracking durch Trackiverse statt.
- **Standort (GPS):** Wird in bestimmten Modulen (*Biermass-Tracker*, *Eisbad-Tracker*, *Eiskugeln-Tracker*, *Espresso-Tracker*, *Glühwein-Tracker*, *Kennzeichen-Tracker*, *Pizza-Tracker*) ausschließlich nach ausdrücklicher Einwilligung zur Ortserfassung eines Eintrags genutzt oder nach manueller Ortsangabe. Beim *Eisbad-Tracker* löst ein vorhandener Standort immer einen Abruf der Außentemperatur bei Open-Meteo aus. Es findet **keine dauerhafte Standortverfolgung** statt.

---

### 5. Rechte der betroffenen Personen & Datenlöschung (DSGVO)

Sie haben das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit sowie Beschwerde bei einer Datenschutzaufsichtsbehörde gemäß DSGVO. Sofern Sie an den Community-Ranglisten teilnehmen, können Sie Ihre Ranglisteneinträge und Ihren Nickname jederzeit selbstständig über die jeweilige App löschen.

---

## English

### 1. Controller & General Information

**Data Controller according to GDPR:**
Claus Gumbmann
Heinrich-Böll-Str. 29
90587 Veitsbronn
Germany

**Email:** spalier-02talg@icloud.com

All applications within **Trackiverse** are designed with privacy as the highest priority and can be used without registration.

---

### 2. Module Breakdown & Data Collection

- 🏔️ **Bergschein-Tracker:** Tracks personal Bergkirchweih status (e.g., myth level, gender, progress) and date/time strictly on your local device. *(100% local)*
- 🍺 **Biermass-Tracker:** Tracks beer consumption (number of Mass, dates, optional location upon consent). *(100% local)*
- 🧊 **Eisbad-Tracker:**
  - **Data stored locally:** bath duration (plan vs. actual if stopped early), optional manually entered water temperature, optional location (after granting approximate/precise device location or after setting a place manually), and outdoor/air temperature **only if a location exists** (then fetched from Open-Meteo). Outdoor temperature cannot be entered manually. *(local)*
  - **Weather lookup (Open-Meteo):** If an entry has a location, outdoor/air temperature is always requested from Open-Meteo (OpenMeteo GmbH, Switzerland). A location exists if you granted device location access (approximate or precise) **or** set the place manually. The request transmits your device IP address and the entry coordinates. Open-Meteo may keep connection logs (IP, URL, coordinates) for operations and abuse prevention and states that logs are deleted after 90 days. No Open-Meteo account is created. The returned outdoor temperature is then stored only on your device. Without a location, no request is made and no outdoor temperature is stored.
- 🍦 **Eiskugeln-Tracker:** Records ice cream consumption (scoops, date, optional location upon consent). *(100% local)*
- ☕ **Espresso-Tracker:** Records consumed espressos (date/time, count, optional location upon consent). *(100% local)*
- 🍷 **Glühwein-Tracker:** Tracks mulled wine consumption (number of mugs, dates, optional location upon consent). *(100% local)*
- 🚗 **Kennzeichen-Tracker:**
  - **Data stored locally:** Stores license plate data, status, and optionally date, location, or notes. *(100% local unless participating in leaderboards)*
  - **Optional Community Leaderboards:** Only if you actively register a nickname and submit your counts, your chosen nickname, a locally generated anonymous device/user ID (UUID), the number of spotted license plate districts (by country: DE, AT, CH, FR, and total), your best rank, and the update timestamp are transmitted to and stored on the leaderboard backend. Specific license plates, places, locations, or personal notes are **not** transmitted.
- 🏋️ **Klimmzug-Tracker:**
  - **Data stored locally:** Tracks pull-up progress (number of pull-ups, optional added weight, dates) strictly on your local device. Uses local notifications to alert you when a rest timer ends. *(100% local unless participating in leaderboards)*
  - **Optional Community Leaderboards:** Only if you actively register a nickname and submit your stats (available after at least 3 distinct training days), your chosen nickname, a locally generated anonymous device/user ID (UUID), your total pull-up repetitions, optional total added weight lifted, your best rank, and the update timestamp are transmitted to and stored on the leaderboard backend. (The number of training days is only checked during submission to verify eligibility and is not stored in the leaderboard entry.)
- 🍪 **Lebkuchen-Tracker:** Records only the date and time of Lebkuchen consumption. *(100% local)*
- 📖 **Lesen-Tracker:** Stores book details, local cover paths, reading sessions, and ratings. Uses **Open Library (Internet Archive)** exclusively to retrieve book data via ISBN search (transmits ISBN and device IP address for technical reasons).
- 🍾 **Pfand-Tracker:** Stores **only date of entry and deposit amount in Euro** locally. *(100% local)*
- 🍕 **Pizza-Tracker:** Records pizzas (diameter, calculated area, date/time of entry, optional location upon consent). Reference-area comparisons (e.g. sports courts) are calculated strictly on your local device from your logged data. *(100% local)*
- 🧩 **Puzzle-Tracker:** Stores date/time of entry, puzzle details (title/type, status, duration), and optional photos of puzzle progress strictly on your local device. *(100% local)*
- 💶 **Trinkgeld-Tracker:** Tracks shift earnings, working hours, and tips locally. *(100% local)*

---

### 3. Permissions & Third-Party Services

- **Community Leaderboards (Firebase / Google Cloud):** Participation in the *Kennzeichen-Tracker* and *Klimmzug-Tracker* leaderboards is optional. The backend runs on Firebase (Cloud Functions and Cloud Firestore, Google Cloud Platform) in the EU region `europe-west3` (Frankfurt, Germany). When using the feature, your device IP address is transmitted for technical reasons, and—if you actively participate—your nickname, anonymous UUID for entry management, leaderboard scores, and update timestamps are processed. Publicly visible on the leaderboard are only your nickname, rank, score (including added weight for pull-ups if applicable), best rank, and last update timestamp; the UUID is never shown publicly. You can delete your leaderboard entries as well as your nickname and all associated server data at any time directly within the app settings.
- **Camera Access:** Requested in *Lesen-Tracker* (for ISBN barcode scanning) and *Puzzle-Tracker* (for capturing optional photos of puzzle progress). All captured photos remain strictly on your local device.
- **Notifications:** Requested in *Klimmzug-Tracker* to alert you locally when a rest timer ends. No data is transmitted.
- **Weather data (Open-Meteo):** Used in *Eisbad-Tracker* whenever an entry has a location (device location after consent, approximate or precise, or a place set manually) to fetch the outdoor/air temperature. Outdoor temperature cannot be entered manually. The request transmits the device IP address and the entry coordinates. Without a location, no request is made. Trackiverse does not perform continuous location sharing or tracking.
- **Location Access:** Used in *Biermass-Tracker*, *Eisbad-Tracker*, *Eiskugeln-Tracker*, *Espresso-Tracker*, *Glühwein-Tracker*, *Kennzeichen-Tracker*, and *Pizza-Tracker* strictly upon explicit consent to assign a location to an entry, or after a place is set manually. In *Eisbad-Tracker*, a location always triggers an Open-Meteo request for outdoor temperature. No continuous tracking takes place.

---

### 4. User Rights (GDPR)

You have rights to access, rectification, erasure, restriction of processing, data portability, and to lodge a complaint with a supervisory authority under the GDPR. If you participate in the community leaderboards, you can delete your leaderboard entries and your nickname directly within the respective app at any time.
