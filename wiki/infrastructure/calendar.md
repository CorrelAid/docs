# Calendar

### Kalender

* eingerichtet auf @frie's nextcloud/correlcloud Account

#### Zugriffsrechte

* read+write: Alle Personen mit CorrelCloud Zugang \(Benutzergruppe "user"\)
* read: Zugriff über public link \(s.u.\)

#### Links und Iframe

* **Links**: es gibt zwei Typen von Links, um auf den Kalender zuzugreifen
  * persönlicher **read+write** Link \(CalDav\): **nur für CorrelCloud Benutzer** 
    1. gehe zum Calendar Tab in der CorrelCloud \(oben links\)
    2. klicke auf das Symbol mit drei Punkten rechts neben dem Kalender "CorrelAid"
    3. klicke auf "Link". Dies ist der Link für read+write Zugriff. Sollte folgende Form haben: `https://correlcloud.org/remote.php/dav/calendars/ + username + /correlaid/`
  * öffentlicher **read** Link \(webcal\):
    * Anschauen: [https://correlcloud.org/index.php/apps/calendar/p/A1BW22MPMSWCNR5D](https://correlcloud.org/index.php/apps/calendar/p/A1BW22MPMSWCNR5D)
    * Einbinden in Clients \(s.u.\):  webcal://correlcloud.org/remote.php/dav/public-calendars/A1BW22MPMSWCNR5D?export
* **iframe** \(für @jan\):

  ```text
       <iframe width="400" height="215" src="https://correlcloud.org/index.php/apps/calendar/embed/A1BW22MPMSWCNR5D"></iframe>
  ```

#### Clients

* **Thunderbird/Lightning**
  1. rechts klick in Kalenderarea, "neuer Kalender"
  2. "Im Netzwerk" auswählen + weiter
     * read+write:
  3. Format CalDav auswählen und persönlichen Link \(s.o.\) einfügen + weiter
  4. Login-Daten für CorrelCloud eingeben + weiter
     * read: 
  5. Format icalendar/ICS auswählen und Read Link \(webcal://...\) einfügen \(s.o.\) 
* **Android**
  * read+write: 
    1. App [OpenSync](https://play.google.com/store/apps/details?id=com.deependhulla.opensync) \(kostenlos\) oder [DavDroid](https://play.google.com/store/apps/details?id=at.bitfire.davdroid) \(3,79 Euro\) - beide OpenSource - installieren
    2. CalDav Server in der App einrichten basierend auf persönlichem Link \(s.o.\) \(bei Detailfragen @frie fragen im \#infrastruktur Channel\)
    3. Kalender sollte nun in der calendar App erscheinen, evtl. muss die Anzeige noch aktiviert werden 
  * read: 
    1. calendar.google.com
    2. unter "Weitere Kalender" oben rechts auf den Pfeil klicken und "Über URL hinzufügen"
    3. Read Link \(webcal://.., s.o.\) eingeben und hinzufügen klicken 
* **Outlook**
  * bitte ergänzen \(google: "webcal outlook" für read, "caldav" für read+write\)
  * Anmerkung: webcal ist so ähnlich wie ical/ics, so wie ich das verstehe. 
* **Google Calendar**
  * "Other calendars" -> "Add other calendars" -> "From URL" -> "Add calendar"
* **iCalendar**
  * "File" -> "New Calendar Subscription" -> Link von oben eingeben
* **iOS**
  * \(google: "webcal ios" für read, "caldav" für read+write\)
  * Anmerkung: webcal ist so ähnlich wie ical/ics, so wie ich das verstehe.

