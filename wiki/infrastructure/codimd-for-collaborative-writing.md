# CodiMD for Collaborative Writing

CodiMD is an online markdown editor that allows for live collaborative editing - like Google docs but with Markdown. CodiMD is the open source version of [HackMD](https://hackmd.io). We were long-time users of HackMD but switched to a self-hosted CodiMD for various reasons in early 2020. You can read more about the reasons [below](codimd-for-collaborative-writing.md#reasons-for-switching-to-codimd).

{% hint style="warning" %}
Our self-hosted CodiMD instance is here [ https://pad.correlaid.org](https://pad.correlaid.org). 
{% endhint %}

## Getting started

Before you can write away, you'll need to do some groundwork by [requesting an account](codimd-for-collaborative-writing.md#requesting-an-account) and [logging in for the first time](codimd-for-collaborative-writing.md#logging-in-for-the-first-time). Afterwards, you should be logged in or able to log into [pad.correlaid.org](https://pad.correlaid.org).

### Write your first note

Click on _"New Note" -_ this will open the editor. Play around by writing content in the left panel - it will appear on the right! Magic, right? You can also check out [this pad](https://pad.correlaid.org/features#)  with all the features CodiMD offers. If you haven't written Markdown before, the [typography section](https://pad.correlaid.org/features?both#typography) is a good place to start.

{% hint style="info" %}
Please delete your toy note afterwards - in this way our workspace does not get too crowded. 
{% endhint %}

### Setting permissions

As the owner of the note, you can set its permission. The permission determines who can read and edit your note. Three roles can be distinguished:

* the owner: the person who created the note
* signed-in users: everyone with an account for pad.correlaid.org, signed into the tool.
* guests: everyone without an account for pad.correlaid.org

The following permissions are available:

|  | Owner read/write | Signed-in read | Signed-in write | Guest read | Guest write |
| :--- | :---: | :---: | :---: | :---: | :---: |
|  **Freely** | ✔ | ✔ | ✔ | ✔ | ✔ |
|  **Editable** | ✔ | ✔ | ✔ | ✔ | ✖ |
|  **Limited** | ✔ | ✔ | ✔ | ✖ | ✖ |
|  **Locked** | ✔ | ✔ | ✖ | ✔ | ✖ |
|  **Protected** | ✔ | ✔ | ✖ | ✖ | ✖ |
|  **Private** | ✔ | ✖ | ✖ | ✖ | ✖ |

The default permission for all notes is **limited**. This is a sensible permission if only people from the core team are supposed to see and edit the content. 

Sometimes you might want to make content read-only for external folks. In this case, **editable** is good. If editing is also wanted for external users, you can set the permission to **freely**. Please make sure that the pad won't contain any sensible information like phone numbers or email addresses. 

## Authentication

We use our own Azure Active Directory for authentication. This means that you can't use your personal Microsoft account for our CodiMD. Instead, you get an acount from us.

### Requesting an account

Join the \#codimd-users channel on [Slack](../communication/slack.md#i-want-to-get-access-to-slack-how-do-i-get-it) and write a short post that you'd like an account. Within the next few hours, someone from the core team should contact you via DM with your account details. You get:

* a username of the form `firstname.firstletteroflastname@correlaid.onmicrosoft.com`. This is only a username, there's no mailbox associated with this "email" address.
* an initial password. 

### Logging in for the first time

Upon first logging in, you'll be prompted to change your initial passowrd. Please do so! You can also later change it \(see below\). You'll also be prompted to set up _2-Factor-Authentication_. We recommend to use the Microsoft Authenticator App \(available for Android and iOS\). If this is not an option for you for whatever reason \(no access to smarpthone, not enough storage on smartphone, app not available for your phone, ...\), please contact Frie \(@frie\) and we can figure something out! :\) 

### Changing your password later

If you need to change your password later on, log into your account on [login.microsoftonline.com](https://login.microsoftonline.com) and go to [https://portal.office.com/Account\#security](https://portal.office.com/Account#security). There, you can change your password. 

## Reasons for switching to CodiMD

* better knowledge management: on HackMD, all of our pads were scattered across our private accounts and there was no central point to see all of them. In contrast, we were able to modify the open source version according to our needs and now have a central page where logged-in users can browse all pads. In addition, all pads are now part of the same database, so we can easily do exports and dumps of all our content if needed.
* better access control: with the self-hosted version, we have complete control who we allow on our instance. In contrast, everyone could register for HackMD and read our pads when in possession of the link. For 97% of pads, this is not a problem - we love transparency. But for the remaining 3%, this could be a problem.

You can read more about the process and reasoning behind this change in [this internal blogpost.](https://pad.correlaid.org/_xR1EKkyRO26XyqLOTpNvA#) 

