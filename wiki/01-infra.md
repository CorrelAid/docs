---
output: html_document
---

# Infrastruktur 
 
## Passwortmanagement 
-  mehrere kdbx Dateien 
    -  twitter
    -  azure / microsoft admin frie account
    -  correlcloud admin
    -  correlaid.org webadmin
    -  dns server manitu
    -  podcast soundcloud 
- Ablageort der kdbx Dateien: **encrypted git auf keybase.io, Zugriff für Mitglieder des Subteams "wearecorrelaid.passwords"** (siehe {#keybase})


- für jede kdbx Datei braucht man ein Master-Passwort zum Entsperren. Master Passwörter werden über eine private Nachricht in Keybase von Frie geteilt und von Personen in privaten Passwortmanagern oder offline an einem sicheren Ort hinterlegt
    - -> **nicht** in unverschlüsselten Dateien auf dem PC 
- System basiert auf **Vertrauen**. Passwörter werden nur an vertrauenswürdige Personen weitergegeben. Wenn sich eine Person als nicht vertrauenswürdig herausstellt, müssen die Passwörter geändert werden, auf die die Person Zugriff hatte. 
- Zugänge in den kdbx Dateien können gerne auch in privaten Passwortmanagern gespeichert werden
- Wer im Besitz welcher Master-Passwörter (und damit Zugängen) ist, wird im README des Repositories von der Person, die das Master Passwort weitergegeben hat, dokumentiert. 

#### Prozess anhand eines Beispiels
1. Anne möchte Zugriff auf den Soundcloud Account haben, um dort eine neue Podcast Folge hochzuladen, weil Jasmin im Urlaub ist
2. Sie legt sich einen keybase Account an und teilt Frie ihren Keybase username mit 
3. Frie fügt Anne zum keybase team "correlaid_pass" hinzu und schickt Anne über eine Direktnachricht in Keybase das Master-Passwort für `soundcloud.kdbx`
4. Anne klont das encrypted Git Repository, das "correlaid_pass" zugeordnet ist
5. Anne installiert einen keepass client für ihr Betriebssystem (https://keepass.info/) 
6. Anne öffnet `soundcloud.kdbx` in ihrem keepass client und entsperrt die Datei mit dem Master Passwort. 
7.
- Anne hinterlegt das **Master Passwort an einem sicheren Ort**, um in Zukunft bei Bedarf `soundcloud.kdbx` entsperren zu können (offline an einem sicheren Ort oder in ihrem privaten Passwordmanager). 
- **oder**: Alternativ kann sie die Soundcloud **Zugangsdaten in ihrem privaten Passwortmanager** abspeichern. Dann braucht sie `soundcloud.kdbx` nicht mehr. 
8. Frie dokumentiert im README des Repositories, dass Anne das Master-Passwort für `soundcloud.kdbx` hat.

#### Anmerkungen
- wenn euer privater Passwortmanager mit Passwort `1234` abgesichert ist oder ihr Passwörter auf Post-Its auf dem Tisch liegen habt, ergibt das ganze keinen Sinn. :wink: 

## Keybase {#keybase}

Auf Keybase ist CorrelAid als sogenanntes *big team* mit dem Namen **wearecorrelaid** vertreten: https://keybase.io/team/wearecorrelaid . 

Ein *big team* entspricht mehr oder weniger einem Slack Workspace. Z.B. können Channel erstellt werden. 

Innerhalb des wearecorrelaid Teams gibt es das Subteam **wearecorrelaid.chamberofsecrets**. Mitglieder dieses Teams haben Zugriff auf das encrypted git `correlaid_secrets`, in dem die kdbx Dateien versioniert sind. 

### Keybase Ressourcen
- https://keybase.io/
- [Keybase Identity Verification & Encrypted End to End Communications](https://www.youtube.com/watch?v=Xcvx10ZUV5w)
- [PGP Intro Playlist](https://www.youtube.com/watch?v=fP0x-YFSh-E&list=PLOZKbRUo9H_pCTg8XdvkyGZ_lJbl1AA5X)
- [What is PGP/GPG Encryption? In 3 Minutes - PGP/GPG Tutorial for Beginners](https://www.youtube.com/watch?v=1-MPcUHhXoc&t=39s)
- [GPG, Web of Trust, and Keybase.io](https://snorre.io/gpg-web-of-trust-and-keybase-io/)
- [Enable Sync (offline access) for KBFS](https://news.ycombinator.com/item?id=20166010)


## GitHub 
- GitHub Organisation: www.github.com/CorrelAid
- "Core" CoreTeam Mitglieder sind **Members** der GitHub Organisation
    - haben über coreteam GitHub Team "Write" Zugriff auf viele Repositories (alle außer Projektrepositories)
    - **können Repositories und Teams erstellen (aka ein neues Projekt onboarden (?))**
- Teil der Members sind **Owners**
    - können alle Repositories verwalten und neue Mitglieder zur Organisation hinzufügen
    - können Repositories löschen, etc. (siehe https://help.github.com/en/articles/repository-permission-levels-for-an-organization)
- **Wichtig**: Projektteammmitglieder und temporäre Mitarbeiter\*innen werden als **External Collaborateurs** mit read/write Rechten zu den relevanten Repositories hinzugefügt --> werden **nicht** zur CorrelAid Organisation hinzugefügt.  
    - "Outside collaborators: Repository collaborators can include organization members or outside collaborators. An outside collaborator is a person who has access to one or more organization repositories but is not explicitly a member of the organization, such as a consultant or temporary employee." (https://help.github.com/en/articles/repository-permission-levels-for-an-organization)

## Azure

## Hackmd 

## GoogleMail
- wearecorrelaid@gmail.com -> kein Zugang mehr (:see_no_evil:). waren aber keine relevanten Accounts verknüpft

## Social Media

### Twitter
- twitter.com/CorrelAid
- Username: @CorrelAid 
- Passwort: siehe Passwortmanagement


### Facebook
- https://www.facebook.com/WeAreCorrelAid/
- Rollen
    - Page Admins
        - Frie Preu
        - Johannes Müller
    - Editors:
        - Yannik Buhl
        - Rahel Becker
        - Arndt Leininger
        - Damon Raeis-Dana
- Zugriff bekommen:
    - Admin kann dich als Editor hinzufügen

## Webspace 

Unser Webspace ist gehostet bei manitu.net .
Er umfasst:
- Website Hosting
- Domains
- SQL Datenbanken
- Email 

## CorrelCloud
Die CorrelCloud ist eine NextCloud Instanz, die auf Manitu gehostet ist. 

- correlcloud.org
- Admins


## Slack
https://correlaid.slack.com/

## Kalender

- eingerichtet auf @frie's nextcloud/correlcloud Account

### Zugriffsrechte
- read+write: Alle Personen mit CorrelCloud Zugang (Benutzergruppe "user")
- read: Zugriff über public link (s.u.)
 
### Links und Iframe
- **Links**: es gibt zwei Typen von Links, um auf den Kalender zuzugreifen
    - persönlicher **read+write** Link (CalDav): **nur für CorrelCloud Benutzer** 
        1. gehe zum Calendar Tab in der CorrelCloud (oben links)
        2. klicke auf das Symbol mit drei Punkten rechts neben dem Kalender "CorrelAid"
        3. klicke auf "Link". Dies ist der Link für read+write Zugriff. Sollte folgende Form haben: `https://correlcloud.org/remote.php/dav/calendars/ + username + /correlaid/`
    - öffentlicher **read** Link (webcal):
        - Anschauen: https://correlcloud.org/index.php/apps/calendar/p/A1BW22MPMSWCNR5D
        - Einbinden in Clients (s.u.):  webcal://correlcloud.org/remote.php/dav/public-calendars/A1BW22MPMSWCNR5D?export
- **iframe** (für @jan):
      ```
       <iframe width="400" height="215" src="https://correlcloud.org/index.php/apps/calendar/embed/A1BW22MPMSWCNR5D"></iframe>
    ```
    
### Clients 
- **Thunderbird/Lightning**
        1. rechts klick in Kalenderarea, "neuer Kalender"
        2. "Im Netzwerk" auswählen + weiter
    - read+write:
        3. Format CalDav auswählen und persönlichen Link (s.o.) einfügen + weiter
        4. Login-Daten für CorrelCloud eingeben + weiter
    - read: 
        3. Format icalendar/ICS auswählen und Read Link (webcal://...) einfügen (s.o.) 
- **Android**
    - read+write: 
        1. App [OpenSync](https://play.google.com/store/apps/details?id=com.deependhulla.opensync) (kostenlos) oder [DavDroid](https://play.google.com/store/apps/details?id=at.bitfire.davdroid) (3,79 Euro) - beide OpenSource - installieren
        2. CalDav Server in der App einrichten basierend auf persönlichem Link (s.o.) (bei Detailfragen @frie fragen im #infrastruktur Channel)
        3. Kalender sollte nun in der calendar App erscheinen, evtl. muss die Anzeige noch aktiviert werden 
    - read: 
        1. calendar.google.com
        2. unter "Weitere Kalender" oben rechts auf den Pfeil klicken und "Über URL hinzufügen"
        3. Read Link (webcal://.., s.o.) eingeben und hinzufügen klicken 
- **Outlook**
    - bitte ergänzen (google: "webcal outlook" für read, "caldav" für read+write)
    - Anmerkung: webcal ist so ähnlich wie ical/ics, so wie ich das verstehe. 
- **IOS**
    - bitte ergänzen (google: "webcal ios" für read, "caldav" für read+write)
    - Anmerkung: webcal ist so ähnlich wie ical/ics, so wie ich das verstehe.
