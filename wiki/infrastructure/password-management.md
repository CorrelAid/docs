# Password management

{% hint style="info" %}
Valid once Google Drive is active/migrated to.
{% endhint %}

{% hint style="info" %}
Ideally, we would have a hosted password manager such as bitwarden or 1password for all of our active volunteers. Sadly, that's too expensive so we work with a file-based solution.
{% endhint %}

## KeePass vaults

If you are (co-)head of a local chapters and/or another team within CorrelAid (such as podcast, mentoring, ethics committee), you will get access to a **password-protected** [**KeePass**](https://keepass.info/) **database file** (.`kdbx`). This file is shared with **only you and your collaborators** via Google Drive. It will contain the login credentials for your shared Google account, e.g. konstanz@correlaid.org or podcast@correlaid.org as well as other relevant credentials.

What is KeePass?

> KeePass is a free open source password manager, which helps you to manage your passwords in a secure way. You can store all your passwords in one database, which is locked with a master key. So you only have to remember one single master key to unlock the whole database. Database files are encrypted using the best and most secure encryption algorithms currently known (AES-256, ChaCha20 and Twofish).

(Source: [https://keepass.info/index.html](https://keepass.info/index.html))

### How can I access the password(s)?

1. You get the master password for the database file from either Isabel (local chapters) or Frie (other teams) via a secure channel. Please store this password safely, e.g. in your personal password manager ([bitwarden](https://bitwarden.com/) is free!).
2. Download one of the KeePass [clients](https://keepass.info/download.html)
3. Download the database file - you can find it in the Shared Drive `08_vaults`.
4. Open the file in your KeePass client. It will ask you for the master password. Once you have unlocked the database, you will be able to access the password(s) stored in there.

### How do I add a new password/change a password?

Prerequesites: KeePass client (see above), master password (see above)

Optional but recommended: Sync Google Drive ([Windows, Mac](https://www.google.com/drive/download/), [Linux](https://itsfoss.com/use-google-drive-linux/)) to your personal laptop so that you have access to your Google Drive files via your file explorer.

1. Download the database file - you can find it in the Shared Drive `08_vaults`. Or find it in the synced folder if you have synced the Google Drive to your machine.
2. Open the file in your KeePass client. It will ask you for the master password. Once you have unlocked the database, you will be able to access the password(s) stored in there.
3. Edit the entry you want to edit or add a new entry. Lock the database/save it (depending on client).
4. Upload the database file back to Google Drive or let sync do this for you.

{% hint style="warning" %}
While you are editing the file, other collaborators from your team must not edit the file at the same time. Given that teams typically don't handle many passwords, this should rarely be a problem. :)
{% endhint %}

## Admin

### How do I add a new vault?

1. make sure you have a [keepass client](https://keepass.info/download.html) downloaded (Recommended MacPass for MacOS)&#x20;
2. create a new vault and create the items inside it. how you do that depends on your client.
3. secure the vault with a password, ideally a [passphrase](https://www.useapassphrase.com/)&#x20;
4. share the vault file with your teammates, e.g. in your Google Drive Workspace. This is ok - the vault can only be decrypted with the password.&#x20;
5. transmit the passphrase via  a secure, encrypted communication channel (not Slack or telegram). For example, signal, whatsapp or via voice.&#x20;
