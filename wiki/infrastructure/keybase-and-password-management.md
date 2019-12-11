# Keybase and Password Management

### Keybase

CorrelAid has a Keybase _big team_ with the name **wearecorrelaid:** [https://keybase.io/team/wearecorrelaid](https://keybase.io/team/wearecorrelaid). A Keybase _big team_ is more or less like a Slack workspace, e.g. channels can be created etc.

Within the CorrelAid teams, there is the subteam **wearecorrelaid.chamberofsecrets**. Members of this teams have access to the encrypted git `correlaid_secrets` which contains the kdbx files needed to access passwords of CorrelAid accounts. See Password Management.

#### Keybase Resources

* [https://keybase.io/](https://keybase.io/)
* [Keybase Identity Verification & Encrypted End to End Communications](https://www.youtube.com/watch?v=Xcvx10ZUV5w)
* [PGP Intro Playlist](https://www.youtube.com/watch?v=fP0x-YFSh-E&list=PLOZKbRUo9H_pCTg8XdvkyGZ_lJbl1AA5X)
* [What is PGP/GPG Encryption? In 3 Minutes - PGP/GPG Tutorial for Beginners](https://www.youtube.com/watch?v=1-MPcUHhXoc&t=39s)
* [GPG, Web of Trust, and Keybase.io](https://snorre.io/gpg-web-of-trust-and-keybase-io/)
* [Enable Sync \(offline access\) for KBFS](https://news.ycombinator.com/item?id=20166010)

### Password Management

### Passwortmanagement

* mehrere kdbx Dateien 
  * twitter
  * azure / microsoft admin frie account
  * correlcloud admin
  * correlaid.org webadmin
  * dns server manitu
  * podcast soundcloud 
* Ablageort der kdbx Dateien: **encrypted git auf keybase.io, Zugriff für Mitglieder des Subteams "wearecorrelaid.passwords"** \(siehe {\#keybase}\)
* für jede kdbx Datei braucht man ein Master-Passwort zum Entsperren. Master Passwörter werden über eine private Nachricht in Keybase von Frie geteilt und von Personen in privaten Passwortmanagern oder offline an einem sicheren Ort hinterlegt
  * -&gt; **nicht** in unverschlüsselten Dateien auf dem PC 
* System basiert auf **Vertrauen**. Passwörter werden nur an vertrauenswürdige Personen weitergegeben. Wenn sich eine Person als nicht vertrauenswürdig herausstellt, müssen die Passwörter geändert werden, auf die die Person Zugriff hatte. 
* Zugänge in den kdbx Dateien können gerne auch in privaten Passwortmanagern gespeichert werden
* Wer im Besitz welcher Master-Passwörter \(und damit Zugängen\) ist, wird im README des Repositories von der Person, die das Master Passwort weitergegeben hat, dokumentiert. 

**Prozess anhand eines Beispiels**

1. Anne möchte Zugriff auf den Soundcloud Account haben, um dort eine neue Podcast Folge hochzuladen, weil Jasmin im Urlaub ist
2. Sie legt sich einen keybase Account an und teilt Frie ihren Keybase username mit 
3. Frie fügt Anne zum keybase team "correlaid\_pass" hinzu und schickt Anne über eine Direktnachricht in Keybase das Master-Passwort für `soundcloud.kdbx`
4. Anne klont das encrypted Git Repository, das "correlaid\_pass" zugeordnet ist
5. Anne installiert einen keepass client für ihr Betriebssystem \([https://keepass.info/](https://keepass.info/)\) 
6. Anne öffnet `soundcloud.kdbx` in ihrem keepass client und entsperrt die Datei mit dem Master Passwort.

   7.

7. Anne hinterlegt das **Master Passwort an einem sicheren Ort**, um in Zukunft bei Bedarf `soundcloud.kdbx` entsperren zu können \(offline an einem sicheren Ort oder in ihrem privaten Passwordmanager\).
8. **oder**: Alternativ kann sie die Soundcloud **Zugangsdaten in ihrem privaten Passwortmanager** abspeichern. Dann braucht sie `soundcloud.kdbx` nicht mehr. 
9. Frie dokumentiert im README des Repositories, dass Anne das Master-Passwort für `soundcloud.kdbx` hat.

**Anmerkungen**

* wenn euer privater Passwortmanager mit Passwort `1234` abgesichert ist oder ihr Passwörter auf Post-Its auf dem Tisch liegen habt, ergibt das ganze keinen Sinn. :wink: 

