# CodiMD for Collaborative Writing

CodiMD is an online markdown editor that allows for live collaborative editing - like Google docs but with Markdown. CodiMD is the open source version of [HackMD](https://hackmd.io). We were long-time users of HackMD but switched to a self-hosted CodiMD for various reasons in early 2020. You can read more about the reasons [below](codimd.md#reasons-for-switching-to-codimd).

{% hint style="warning" %}
Our self-hosted CodiMD instance is here [ https://pad.correlaid.org](https://pad.correlaid.org). 
{% endhint %}

## Getting started

Before you can write away, you'll need to do some groundwork by [requesting an account](codimd.md#requesting-an-account) and [logging in for the first time](codimd.md#logging-in-for-the-first-time). Afterwards, you should be logged in or able to log into [pad.correlaid.org](https://pad.correlaid.org).

### Write your first note

Click on _"New Note" -_ this will open the editor. Play around by writing content in the left panel - it will appear on the right! Magic, right? You can also check out [this pad](https://pad.correlaid.org/features#)  with all the features CodiMD offers. If you haven't written Markdown before, the [typography section](https://pad.correlaid.org/features?both#typography) is a good place to start.

{% hint style="info" %}
Please delete your toy note afterwards - in this way our workspace does not get too crowded. 
{% endhint %}

### Setting permissions

As the owner of the note, you can set its permission. The permission determines who can read and edit your note. You can change the permission by clicking on "Limited". 

![](../../.gitbook/assets/screenshot-2020-03-31-at-18.26.57.png)



Three types of users can be distinguished:

* the owner: the person who created the note
* signed-in users: everyone with an account for pad.correlaid.org, signed into the tool.
* guests: everyone with a link to the pad.

The following permissions are available:

|  | Owner read/write | Signed-in read | Signed-in write | Guest read | Guest write |
| :--- | :---: | :---: | :---: | :---: | :---: |
|  **Freely** | ✔ | ✔ | ✔ | ✔ | ✔ |
|  **Editable** | ✔ | ✔ | ✔ | ✔ | ✖ |
|  **Limited** | ✔ | ✔ | ✔ | ✖ | ✖ |
|  **Locked** | ✔ | ✔ | ✖ | ✔ | ✖ |
|  **Protected** | ✔ | ✔ | ✖ | ✖ | ✖ |
|  **Private** | ✔ | ✖ | ✖ | ✖ | ✖ |

The default permission for all notes is **limited** which means that only people with a pad.correlaid.org account can read and edit the note. This is a sensible permission if only people from the core team are supposed to see and edit the content. 

Sometimes you might want to make content read-only for external folks. In this case, **editable** is good. If editing is also wanted for external users, you can set the permission to **freely**. _Please make sure that the pad won't contain any sensible information_ like phone numbers or email addresses. If your goal is to make something readable for external people, [publishing](codimd.md#publishing-a-note) is a good alternative.

The other permissions are useful for more specific scenarios and should only be needed rarely:

* **locked**: only you can edit, everyone can read. Could be good for things that specifically only you want to be able to edit, e.g. personal thoughts. 
* **protected**: similar to locked, but guests cannot read, only logged-in users can. 
* **private**: only you can read + edit. Please don't use pad.correlaid.org for your personal stuff, [hackmd.io](https://hackmd.io) 's free version is super cool for individuals! 

### Publishing a note

You can also **publish** a note. This will create an additional link where only the "read" view is visible - the editor is not.This is perfect for sharing something with a larger audience where people would get confused by too many buttons etc. You can publish a note by clicking "Publish" in the navigation bar.

![](../../.gitbook/assets/screenshot-2020-03-31-at-18.26.57%20%281%29.png)

## Authentication

We use our own Azure Active Directory for authentication. This means that you can't use your personal Microsoft account for our CodiMD. Instead, you get an acount from us.

### Requesting an account

Join the \#codimd-users channel on [Slack](../communication/slack.md#i-want-to-get-access-to-slack-how-do-i-get-it) and write a short post that you'd like an account. Within the next few hours, someone from the core team should contact you via DM with your account details. You get:

* a username of the form `firstname.firstletteroflastname@correlaid.onmicrosoft.com`. This is only a username, there's no mailbox associated with this "email" address.
* an initial password. 

### Logging in for the first time

{% hint style="warning" %}
You have to log in using the "Log in using OAuth2" option. Don't try to use the "email/password" option - it won't work. 
{% endhint %}

Upon first logging in, you'll be prompted to change your initial password. Please do so! You can also later change it \(see below\). You'll also be prompted to set up _2-Factor-Authentication_. We recommend to use the Microsoft Authenticator App \(available for Android and iOS\). If this is not an option for you for whatever reason \(no access to smarpthone, not enough storage on smartphone, app not available for your phone, ...\), please contact Frie \(@frie\) and we can figure something out! :\) 

### Changing your password later

If you need to change your password later on, log into your account on [login.microsoftonline.com](https://login.microsoftonline.com) and go to [https://portal.office.com/Account\#security](https://portal.office.com/Account#security). There, you can change your password. 

## Reasons for switching to CodiMD

* better knowledge management: on HackMD, all of our pads were scattered across our private accounts and there was no central point to see all of them. In contrast, we were able to modify the open source version according to our needs and now have a central page where logged-in users can browse all pads. In addition, all pads are now part of the same database, so we can easily do exports and dumps of all our content if needed.
* better access control: with the self-hosted version, we have complete control who we allow on our instance. In contrast, everyone could register for HackMD and read our pads when in possession of the link. For 97% of pads, this is not a problem - we love transparency. But for the remaining 3%, this could be a problem.

You can read more about the process and reasoning behind this change in [this internal blogpost.](https://pad.correlaid.org/_xR1EKkyRO26XyqLOTpNvA#) 



## Troubleshooting

### My email / password does not work all of the sudden? / I can't log in

#### Reason 1: You have used the wrong log in procedure

Most likely: Have you accidentally tried to log in using the email / password box instead of the red "log in using OAuth2"? 

You always need to use the OAuth2 login option. The email / password box was added in ~October 2020 for a "machine user" that automatically backups all pads nightly to a secure location. All other users except this one user are Azure Active Directory users and hence need to log in using OAuth2. If you want to know more about why this is the case, you can read about it in this [internal blog post](https://pad.correlaid.org/_xR1EKkyRO26XyqLOTpNvA#).

#### Reason 2: You are logged into another Microsoft account

If you are logged into a different Microsoft account \(e.g. from university / work\), it could cause problems with CodiMD. We know it's annoying but please log out of the other Microsoft account and try logging in using the OAuth2 option with your @correlaid.onmicrosoft.com acccount.

#### Reason 3: You have forgotten your password

If you are sure that you are a\) using the correct login procedure \(OAuth2 instead of email / password\) and b\) that you are not logged into another account, then please reach out to Frie and request a password reset. 





