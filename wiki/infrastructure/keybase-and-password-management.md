# Keybase and Password Management

## Keybase

CorrelAid has a Keybase _big team_ with the name **wearecorrelaid:** [https://keybase.io/team/wearecorrelaid](https://keybase.io/team/wearecorrelaid). A Keybase _big team_ is more or less like a Slack workspace, e.g. channels can be created etc. For more info on what keybase is and does, check the [Keybase and Password Management](keybase-and-password-management.md#keybase-resources) at the bottom of this page.

Within the CorrelAid teams, there is the subteam **wearecorrelaid.chamberofsecrets**. Members of this teams have access to the encrypted git `correlaid_secrets` which contains the kdbx files needed to access passwords of CorrelAid accounts. See the following section.

## Password Management

Good password management is complicated. Thankfully, password managers exist and make it easier **not** to have passwords like "CorrelAidCorrelAid". However, having a password manager solution for more than a few people does get expensive very quickly. Hence, we currently have a setup that might be a bit workaround-y. But it works! Plus, it's open source: **Keybase, git and KeePass**.&#x20;

The different logins live in multiple `kdbx` files. `kdbx` is the file extension associated with the open source password manager [KeePass](https://keepass.info). Don't be scared off by the old-fashioned website - there are pretty cool KeePass clients for every operating system. Check the [downloads](https://keepass.info/download.html) page.

For instance, we might have a `twitter.kdbx` file which just contains the Twitter login credentials. In a similar fashion, we have `kdbx` files for all the other accounts / logins. Each `kdbx` file is also secured with a master password.&#x20;

This collection of `kdbx` files is part of an **encrypted git repository** on [keybase](https://keybase.io). This repository is linked to the **wearecorrelaid.chamberofsecrets **subteam (see [above](keybase-and-password-management.md#keybase)). This means that only members of this subteam have access to the password files.

Members receive the master password for the file they want to open from Frie in a **private keybase message**. They are obligated to store this master password **at a safe place**, preferably their own private password manager.** **Alternatively, they can store the credentials contained in the file in their private password manager. \


{% hint style="warning" %}
If your private password manager's password is `1234` or if you leave any master passwords laying around on post-its, **this whole thing does not make sense**!
{% endhint %}

{% hint style="warning" %}
The system is based on **trust**. Passwords are made accessible only to trustworthy persons. If a person turns out to not be trustworthy, all passwords that they had access to need to be changed.
{% endhint %}

### Process with an example

{% hint style="success" %}
1. Anne wants access to the Twitter account to upload a new episode there because Jasmin is on holiday.
2. Anne registers for **keybase** and writes Frie her username.
3. Frie adds Anne to the **wearecorrelaid team **and then to the **chamberofsecrets subteam **and also sends Anne the **master password** for the `twitter.kdbx` file in a private keybase message.
4. Anne clones the encrypted Git repository called `correlaid_secrets`&#x20;
5. Anne installs a KeePass client for her operating system&#x20;
6. Anne opens `twitter.kdbx`  in her KeePass client and unlocks the file with the master password.
7. Anne **either** stores the master password in her own private password manager **or** stores the Twitter login details in her private password manager.
8. Frie adds to the README of the repository that Anne has the master password for `twitter.kdbx. `
{% endhint %}

## FAQ

### I need to be added to the Keybase team. Who can help me?

{% hint style="info" %}
Ping Frie (@frie) on Slack or on Keybase (@friep). She'll add you to the Keybase team and  send you the master passwords you need.
{% endhint %}

### Links

#### Keybase Resources

* [https://keybase.io/](https://keybase.io)
* [Keybase Identity Verification & Encrypted End to End Communications](https://www.youtube.com/watch?v=Xcvx10ZUV5w)
* [PGP Intro Playlist](https://www.youtube.com/watch?v=fP0x-YFSh-E\&list=PLOZKbRUo9H\_pCTg8XdvkyGZ\_lJbl1AA5X)
* [What is PGP/GPG Encryption? In 3 Minutes - PGP/GPG Tutorial for Beginners](https://www.youtube.com/watch?v=1-MPcUHhXoc\&t=39s)
* [GPG, Web of Trust, and Keybase.io](https://snorre.io/gpg-web-of-trust-and-keybase-io/)
* [Enable Sync (offline access) for KBFS](https://news.ycombinator.com/item?id=20166010)
