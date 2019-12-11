# Ausschreiben des Projektes im Netzwerk



## Ausschreiben des Projektes im Netzwerk

###  <a id="ausschreiben"></a>

#### Überblick

\`\`\`{block, type='blue'}

* Ziel: Aufstellen eines passenden Projektteams aus dem CorrelAid-Netzwerk
* Zeitrahmen: 3 Wochen
* Zeitaufwand: 6-8 h
* Relevante Akteurinnen: Projektkoordinatorin, Core Team, Auswahlgruppe \(wird im Prozess gebildet\)

  \`\`\`

#### Prozessgrafik

* Einrichtung des Bewerbungsformulars _Tag 1_
* Ausschreibung des Projekts per MailChimp _Tag 1_
* Erneute Versendung der Ausschreibung per MailChimp _Tag 7_
* Bildung einer Auswahlgruppe _Tag 7_
* Zusammenfassung der Bewerbungen _Tag 14_
* Auswahlgruppe wählt Projektteam aus _Tag 15 - 18_
* Projektkoordinatorin schreibt Ausgewählte an und bittet um Bestätigung _Tag 15 - 20_
* Projektkoordinatorin verschickt Absagen an weitere Bewerberinnen sobald das Team steht _Tag 21_
* Projektkoordinatorin schickt eine Begrüßungsmail an das Projektteam _Tag 21_

#### Anleitung

**Einrichtung des Projekt-Factsheets**

Die Projektleiterin benutzt das Template für Projekt-Factsheet in der CorrelCloud und erstellt ein Projekt-Factsheet. Im Prozess von Projektkoordination bis zum Abschluss von Projekt sollte die Projektleiterin immer daran erinnern, relevante Informationen im Projekt-Fachsheet zu dokumentieren. Nach Projektabschluss veröffentlicht die Projektleiterin das Projekt-Factsheet im Channel "Vorstand" auf Slack. Es dient als Diskussionsvorlage für die Telefonkonferenz. Danach wird das Fachsheet in der CorrelCloud gespeichert.

Das Factsheet umfasst folgende Punkte, die im Laufe des Projektes ergänzt werden:

* Basic Information des Projekts
  * Projektinhalt
  * Partnerorganisation
  * Datum und Dauer
  * Projektleiterin, Projektkoordinatorin, Projektteammitglieder
* Zusammenfassung von Koordinationserfahrung
* Feedback des Projektteams
* Feedback der Projektleitung
* Tipps für die Zukunft

**Einrichtung des Formulars**

Die Projektkoordinatorin erstellt bei MailChimp ein Formular, über das sich Netzwerkmitglieder, die Interesse an der Mitarbeit haben, melden. Als Vorlage dient das Template aus der MailChimp-Vorlage.

Die Projektkoordinatorin definiert mit dem Vorstand und der Projektleitung, welche Skills für das Projekt gebraucht werden. Dinge, die nicht Voraussetzung sind, sollten nicht abgefragt werden. Erfahrung mit NextClould oder \(R\)MarkDown sind keine Voraussetzung und werden nicht im Formular abgefragt. Diese werden noch vom ausgewählten Team abgefragt, um diese Themen im Workshop entsprechend zu berücksichtigen. Im Bewerbungsprozess erheben wir nur die für die Auswahl und Kontaktaufnahme mit Projektteammitgliedern unbedingt notwendigen Daten.

Die Projektkoordinatorin teilt den Link zum Formular auf Slack im Channel `#projekte` und erbittet Feedback unter Nennung einer konkreten Deadline für das Feedback - wenige Tage. Die Projektkoordinatorin überarbeitet das Formular auf Basis des Feedbacks. Dazu legt sie bei MailChimp eine neue Kampagne an - als Vorlage dient das Template für Projektausschreibungen.

**Aussendungen über MailChimp**

Die Projektkoordinatorin verschickt die Projektausschreibung über das Netzwerk. Die Ausschreibung enthält einen Link zu dem Formular, über das sich Interessierte für das Projekt melden. Die Projektkoordinatorin macht dies selber oder bittet ein Mitglied des Kernteams mit Zugang zu MailChimp um Hilfe.

Für die Projektausschreibung gibt es ein Template auf MailChimp, das die Projektkoordinatorin dafür nutzen soll. Die Textbausteine des Templates sind auch in diesem Abschnitt des Handbuchs unter Templates aufgeführt.

Die Projektkoordinatorin passt das Python-Skript für automatisierte Bestätigungs-E-Mail an und aktiviert es anschließend. Hierbei können Frie \(`@frie`\) oder Jan \(`@tollpatsch`\) um Hilfe gebeten werden. Das Skript prüft täglich, ob es neue Eintragungen in die Liste gab und verschickt an diese eine Bestätgigungs-Email, über den Erhalt der Bewerbung. Der Text dieser E-Mail muss projektspezifisch angepasst werden.

Die Projektkoordinatorin schickt nach Ablauf einer Woche eine Erinnerung an die Ausschreibung ans Netzwerk. Es handelt sich dabei um den ursprünglichen Ausschreibungstext, der um 1-2 Sätze ergänzt wird, dass es sich um eine Erinnerung an die in einer Woche ablaufende Ausschreibung handelt. Diese Erinnerung kann bei Verschicken der initialen Einschreibung schon versandfertig gemacht und vorgetimet werden.

**Bildung der Auswahlgruppe**

Direkt nach Versand der Ausschreibung kümmert sich die Projektkoordinatorin um die Bildung einer Auswahlgruppe, welche aus den Interessentinnen aus dem Netzwerk ein Projektteam auswählen wird. Dazu erstellt die Projektkoordinatorin im Slack-Channel `#general` eine Abstimmung mit der Frage "Möchtest Du an der Auswahlgruppe für das Projekt '\[Projektname\]'" teilnehmen. Alle Mitglieder des Kernteams \(also alle auf Slack\) können Teil der Auswahlgruppe werden.

Außerdem legt die Projektkoordinatorin bereits einen Termin für die Telefon- oder appear.in-Konferenz der Auswahlgruppe fest. Die Mitglieder des Kernteams sollen nur "Ja" sagen, wenn sie an diesem Termin können. Der Termin sollte möglichst unmittelbar nach Ablauf der Bewerbungsfrist liegen.

Abstimmungen können in Slack über die Polly-Erweiterung erstellt werden. Diese wird jeweils durch den Befehl `/poll` eingeleitet. Darauf folgen der Titel der Abstimmung "Wer möchte am xx.xx. Teil der \[Projektname\]-Auswahlgruppe sein?" sowie die Antwortmöglichkeiten "Ja :thumbsup:" und "Nein :thumbsdown:" jeweils in Anführungszeichen.

Ein Polly-befehl könnte also wie folgt aussehen:

```text
/Poll "Wer möchte am 23.08. Teil der Ashoka-Auswahlgruppe sein?" "Ja :thumbsup:" "Nein :thumbsdown:"
```

**Die Auswahlgruppe**

* 3 Mitglieder
  * die Projektkoordinatorin
  * mindestens 2 Mitglieder des Kernteams \(zufällig ausgewählt\)
  * bei der Bildung der Auswahlgruppe ist auf die Geschlechterparität zu achten
* Die Mitgliedschaft in der Auswahlgruppe und eine Bewerbung auf das Projekt schließen sich aus. Ob die Projektleiterin auch Teil der Auswahlgruppe ist, kann je nach Projekt entschieden werden.

**Auswahl eines Projektteams**

Die Projektkoordinatorin schließt das Formular. Sie exportiert anschließend die Liste aus MailChimp.

Sie nutzt das Template für die Bewerberinnenübersicht, um eine Übersicht über die Bewerberinnen für die Auswahlgruppe zu erstellen. Sie ändert dazu den Code am Anfang des RMarkdown-Dokuments so, dass dieses die aus MailChimp exportierte Liste der Bewerberinnen lädt und kompiliert das Dokument als PDF. Das Dokument schickt sie den Mitgliedern der Auswahlkommission entweder in einer persönlichen Nachricht per Slack oder in einer verschlüsselten E-Mail.

In dieser Nachricht schickt die Projektkoordinatorin auch eine Erinnerung an die Konferenz der Auswahlgruppe. Diese findet per Telefon oder appear.in statt. Die Auswahlgruppe hält ihre Entscheidung in einem Protokoll fest. Dazu wird eine Protokollantin bestimmt.

Bei der Auswahl kann es hilfreich sein, die Aufgabe als das Befüllen einer Berufungsliste zu betrachten. Zunächst soll die beste Bewerberin identifiziert werden, dann die zweite und so weiter. Dabei ist zu beachten, dass nicht nur die statistischen und technischen Fähigkeiten, sondern auch inhaltliche Interessen und Kompetenzen sowie Soft Skills beachtet werden sollen. Außerdem wollen wir explizit nicht die technisch besten auswählen, sondern auch gezielt Interessierte mit Lernpotenzial auswählen. **Den BewerberInnen wird niemals eine Rangfolge kommuniziert. Diese soll nur eine Hilfestellung für den Auswahlprozess sein.**

Die Auswahlgruppe wählt immer zwei Personen zusätzlich aus welche die Projektkoordinatorin direkt anfragen kann, falls eine der anderen ausgewählten Bewerberinnen unerwartet absagt.

Vorschlag für den Ablauf der Telefonkonferenz:

1. Die Projektkoordinatorin begrüßt alle Teilnehmenden und prüft, ob alle Mitglieder der Auswahlgruppe anwesend sind und, dass niemand dabei ist, die nicht teilnehmen sollte.
2. Die Projektkoordinatorin erläutert die Grundsätze der Teamauswahl. Sie fragt, ob es dazu Fragen gibt.
3. Die Projektkoordinatorin geht kurz die Profile der Bewerberinnen durch.
   * Falls darunter Bewerberinnen sind, die sich bereits erfolglos beworben haben oder schon mal an einem Projekt teilgenommen habe weist sie darauf hin.
4. Die Projektkoordinatorin versucht einen Konsens zu finden, welche Person auf Platz 1 gesehen wird. Und so weiter.
5. Die Projektkoordinatorin fasst die Auswahl zusammen. Sie rückversichert sich, dass diese Entscheidung von allen Mitglieder der Auswahlgruppe mit getragen wird.

**Grundsätze der Teamauswahl**

* Die Auswahl erfolgt ungeachtet von Staatsangehörigkeit, Hautfarbe, Religion und sexueller Orientierung.
* Wir achten auf eine angemessen Repräsentation von Frauen in unseren Projektteams.
* Mindestens 50% der Mitglieder unserer Projektteams sind Frauen.
* Wir achten auf eine ausgewogene Besetzung der Projektteams nach verschiedenen Levels an Erfahrung.
* Interessierte, die bereits an einem anderen Projekt mitarbeiten wollten und dort nicht zum Zuge gekommen sind, werden bevorzugt berücksichtigt. Interessierte, die sich erstmals für ein Projekt bewerben, werden gegenüber Interessentinnen, die bereit an einem Projekt teilgenommen haben, bevorzugt berücksichtigt.
  * Wir führen dazu eine Liste sämtlicher bisheriger Bewerberinnen und Projektteammitglieder. Wir speichern dabei nur Name, E-Mail-Adresse und Geschlecht der Personen.
  * Diese Liste ist im Vorstandsordner auf der CorrelCloud gespeichert.
  * Die Projektkoordinatorin bekommt für die Dauer des Auswahlprozesses diese Liste zur Verfügung gestellt mit der Maßgabe sie ergänzt zurückschicken und im Anschluss auf ihrem privaten Rechner zu löschen.
* Bewerbungsgespräche führen wir nicht durch. Die Auswahlgruppe entscheidet auf Grundlagen der schriftlichen Bewerbungen.
* Die Auswahlgruppe versucht, nach dem Konsensprinzip zu entscheiden.
* Ist ein Konsens nicht herzustellen erfolgt eine Mehrheitsentscheidung.
* Bei Stimmengleichheit gibt die Stimme der Projektkoordinatorin den Ausschlag.

**Zusammenstellen des Projektteams**

Die Projektkoordinatorin kontaktiert nun sofort die ausgewählten Bewerberinnen und bittet um schnelle Bestätigung. Sagt eine Bewerberin ab, wird die erste Person auf der Nachrückerinnen-Liste angeschrieben. Erst wenn Zusagen von allen Projektteammitgliedern eingegangen sind, werden Absagen an verschickt. Für Zu- und Absagen gibt es ein Template, das genutzt werden kann.

**Begrüßung des neuen Teams**

Die Projektkoordinatorin sendet eine Begrüßungsemail an das Projektteam \(inkl. Projektleiterin\). Darin:

* begrüßt sie alle herzlich im Team
* stellt die Projektleiterin kurz vor
* stellt alle Teammitglieder kurz vor
* weist auf den Workshoptermin hin
* lädt die Teammitglieder zu Slack ein

Die Projektkoordinatorin lädt die Teammitglieder zu Slack sein. Hierfür geht man im Menü des Correlaid-Channels auf die Option "Invite people". In der sich daraufhin öffnenden Maske werden die Mailadressen der jeweiligen Teammitglieder sowie deren Namen eingetragen. Hat die Projektleiterin noch keine Administratorenrechte für Slack haben sollte dies nachgeholt werden.

Die Projektkoordinatorin richten einen geschlossenen Channel für das Team ein. Darin sind nur die Projektkoordinatorin, die Projektleiterin und die Projektteammitglieder.

Die Projektkoordinatorin ergänzt die Liste unserer Projekte auf der CorrelCloud um das neue Projekte und die Mitglieder des Projektteams.

**Projektteam über den Workshop informieren**

Die Projektkoordinatorin sendet eine separate Email an das Projektteam \(inkl. Projektleiterin\) zu Workshop. Darin gibt die Projektleiterin folgende Information:

* Ziel von Workshop
* Ort und Termin von Workshop
* Teilnehmer von Workshop
* Organisatorische Arbeit \(Transport, Übernachtung\)
* Vorläufiges Workshop-Programm
* Ansprechspartner\_in \(Projektkoordinatorin/Projektleiterin\), je nachdem wer zuständig für Vorbereitung und Durchsetzung von Projekt ist.

#### Checkliste

* [ ] Die Ausschreibung ist raus und das Formular online
* [ ] Die Auswahlgruppe ist zusammengestellt
* [ ] Das Team ist ausgewählt. Von den Ausgewählten wurde die Zusage eingeholt und den weiteren Bewerberinnen abgesagt.
* [ ] Das Team wurde begrüßt und zu Slack und der CorrelCloud eingeladen.

#### Templates

* Template für Formular
* Template für Ausschreibung
* Template für Übersicht über Bewerberinnen
* Template für Protokoll der Auswahlgruppe
* Templates für Zu- und Absagen
* Template für Begrüßungsemail

**Template Formular**

\`\`\`{block, type='yellow'}

### CorrelAid: Projektausschreibung \[Projektname\]

#### Rahmendaten

**Bewerbungsfrist:** \[Datum\]

**Team:** X x DatenanalystInnen

**Projektzeitraum:** Mitte Oktober 2016 bis Ende Dezember 2016

#### Formular

Vorname\*

Name\*

E-Mail-Adresse\*

Gender \*

* Weiblich
* Männlich
* Möchte ich nicht angeben/so definieren.

Stadt \*

Universität/Arbeitgeber

Mit welcher Statistik-Software arbeitest du hauptsächlich?\*

* R
* Python
* Andere \(siehe Textfeld in der nächsten Zeile\)

Welche weitere Software nutzt du? \[Textfeld\]

Meine Einschätzung zu meinen R-Kenntnissen

Projektspezifischen Fragen

\*Pflichtfeld

```text
### Template für Ausschreibung

```{block, type='yellow'}

Betreff: [CorrelAid] Projektausschreibung: [Projektname]

## Rahmendaten

**Organisation:** Name der Orga
**Team:** 1 TeamleiterIn (Name), 3 DatenanalystInnen (Du?)
**Thema:** 1-2 allgemeine Worte zu den durchzuführenden Analyen
**Projektzeitraum:** 

## Das Projekt

Absatz zur Oroganisation

Absatz zum Inhalt des Projekts

Wenn ihr an dem Projekt mitarbeiten wollt, solltet ihr mindestens X Stunden pro Woche für aufwenden können. Uns ist zudem eine kontinuierliche Mitarbeit am Projekt wichtig. 

*Bitte beachte, dass sicher deutlich mehr Leute ihr Interesse an dem Projekt bekunden werden als in dem Projektteam mitarbeiten können. Wir bitten um dein Verständnis, solltest du bei diesem Projekt nicht dabei sein können. Dieses Projekt wird sicher nicht unser letztes sein, sodass sich bestimmt noch weitere Möglichkeiten ergeben, aktiv bei CorrelAid mitzuwirken.*

*Alle Interessensbekundungen werden nach Ablauf der Ausschreibungsfrist am DATUM von unserer Auswahlgruppe gesichtet. Innerhalb einer Woche erfährst, ob du bei dem Projekt dabei bist.*

[Button: Apply now]

Bei Fragen schreibe gerne eine Mail an [E-Mail der Projektkordinatorin]
```

**Template für Übersicht über Bewerberinnen**

\`\`\`{block, type='yellow'}

| No. | Gender | Stadt | Ausbildung | Relevante berufliche Erfahrung | Statistik-Software | Weitere Software | Einschätzung zu R-Kenntnissen | Projektspezifische Fragen |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Bewerber\_in 1 |  |  |  |  |  |  |  |  |
| Bewerber\_in 2 |  |  |  |  |  |  |  |  |
| Bewerber\_in 3 |  |  |  |  |  |  |  |  |

```text
### Template für Beurteilungstabelle 

```{block, type='yellow'}

| No. | Persönliche Daten |persönliche Ausgeglichenheit| Datenanalysekenntnisse| Projektrelevante Kenntnisse
| -------- | -------- | -------- | -------- | -------- | -------- |-------- |-------- | -------- |
| Bewerber_in 1    |      |      |
| Bewerber_in 2    |      |      |
| Bewerber_in 3    |      |      |
```

**Template für Zusage**

\`\`\`{block, type='yellow'}

Betreff: \[CorrelAid\] Deine Bewerbung auf das Projekt "\[Projektname\]"

Liebe/r \[Name Bewerberin\],

vielen Dank für Deine Bereitschaft, an unserem Projekt für \[Name Organisation\] mitzuwirken. Ich freue mich sehr, Dir sagen zu können, dass Du bei unserem Projekt mit dabei bist.

Bitte gib mir schnell Bescheid, ob Du nachwievor mitmachen möchtest.

Weitere Details folgen dann in Kürze. Der Projektworkshop findet schon bald und zwar am \[Datum\] statt. Du erhältst bald mehr Infos dazu. Bitte trage Dir diesen Termin schon mal in Deinem Kalender ein.

Unter meiner E-Mail findest Du nochmal zur Erinnerung die Projektbeschreibung.

Herzliche Grüße

\[Projektkoordinatorin\]

```text
### Template für Absage

```{block, type='yellow'}

Betreff: [CorrelAid] Deine Bewerbung auf das Projekt "[Projektname]" 

Liebe/r [Name Bewerberin],

vielen Dank für Dein Interesse, an unserem Pilotprojekt 
mitzuarbeiten. Wir haben uns über die Resonanz, die wir
erhalten haben, sehr gefreut. Leider bringt die Vielzahl an 
Rückmeldungen mit sich, dass wir eine Auswahl treffen 
mussten.

Leider bist Du bei unserem Pilotprojekt nicht dabei. Das solltest Du
keinesfalls als negative Wertung Deiner Fachkenntnisse betrachten. Bei
unserer Auswahl haben eine Vielzahl an Kriterien eine Rolle gespielt -
so haben wir auch darauf geachtet, dass wir eben nicht nur nach den
besten Statistikkenntnissen auswählen, sondern ein Team mit vielfältigen
Erfahrungen und Interessen zusammenstellen.

Unserem Pilotprojekt werden bald weitere Projekte folgen. Bei der
Auswahl berücksichtigen wir auch, ob AnalystInnen in der Vergangenheit
leider nicht zum Zuge kamen. Die nächste Möglichkeit zur
Projektmitarbeit kommmt also sicher bald.

Mit Fragen und Ideen kannst Du Dich auch gerne jederzeit an mich wenden.

Herzliche Grüße

[Projektkoordinatorin]
```

**Template für Begrüßung des Projektteams**

\`\`\`{block, type='yellow'}

Betreff: \[CorrelAid\] Herzlich willkommen im Projektteam

Liebe \[alle Namen des Projetteams auflisten\]

herzlich willkommen im Projektteam, das in den nächsten Wochen das Projekt für \[Organisation\] bearbeiten wird. Ich freue mich sehr, dass ihr mit dabei seid.

Ich bin \[Name Projektkordinatorin\] und koordiniere dieses Projekt für CorrelAid. Ich kümmere mich um organisatorische Aspekte.

Eure Projektleiterin ist \[Name Projektleiterin\]. \[Vorstellung der Projektleiterin\]

Ihr werdet euch alle auf dem Workshop kennenlernen. Hier schon mal mit einem Satz zu jedem wer alles im Team mit dabei ist.

\[Vorstellung Teammitglieder\]

Der Workshop wird am \[Datum\] in \[Ort\] stattfinden. Orgasachen abfragen.

Zur Kommunikation im Team nutzen wir das Tool Slack. Dazu erhaltet ihr separat von mir eine Einladung. Ihr könnt euch dort gerne schon vor dem Workshop anmelden und als Team kommunizieren. Auf dem Workshop werden wir das Tool und wie wir es nutzen vorstellen.

Die Projektarbeit mit euch gliedert sich im Folgenden in 3 Phasen: Zunächst kommt der Workshop in dem ihr \[die Organisation\] sowie die weiteren Projektmitglieder kennenlernt. Hier lernt ihr unsere Tools kennen und erarbeitet ein Vorgehen für eure Projektarbeit. Daran schließt das eigentliche Projekt an welches mit einem Abschlussbericht beendet wird. Dieser Bericht geht anschließend in ein Peer Review Verfahren mit erfahrenen Mitgliedern aus unserem Netzwerk.

Herzliche Grüße Arndt

```text
### Template für Fact Sheet

```{block, type='yellow'}

- Basic Information von Projekt 
    - Projektinhalt
    - Partnerorganisation
    - Datum und Dauer
    - Projektleiter, Projektkoordinatorin, Auswahlkommission, Projektteammitglieder
- Zusammenfassung von Koordinationserfahrung
    - Ausschreiben des Projektes
    - Vorbereitung und Koordination von Workshop
    - Unterstützung bei der Projektarbeit
    - Peer Review
    - Organisationsarbeit nach Abgabe von Projektbericht (Feedbackgespräche, Erstellung von Testimonial usw.)
- Feedback von Projektteam und Projektleitung
    - Feedback zu Projektarbeit
    - Feedback zu CorrelAid
- Feedback von Partnerorganisation
    - Feedback zu Projektarbeit und Projektleiterin
    - Feedback zu Koordinationsarbeit von Projektkoordinatorin
    - Bereitschaft, Vorschläge durchzusetzen
    - Künftige Kooperationsmöglichkeit
- Tipps für Zukunft
```

#### Referenzen und Hinweise

* [MailChimp](http://mailchimp.com/)
  * Zugang
* Hinweis wo sich die Liste der bisherigen Projektteammitglieder und BewerberInnen befindet

