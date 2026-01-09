---
description: We use Pretix for the management of course registrations and payments.
---

# Pretix

### Create a Pretix Event

To create an event in Pretix, you can either create one from scratch or duplicate an existing one:

{% columns %}
{% column %}
<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure></div>
{% endcolumn %}

{% column %}
<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure></div>
{% endcolumn %}
{% endcolumns %}

### Add a Calendar-Entry to a Pretix Event

To add a calendar entry to an event, select the event, go to E-Mail setting and the tab calendar invitations:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure></div>

### Customize Pretix Mails and Add Zoom Links

To customize mails and add Zoom links, select the event, go to E-Mail settings and the tab E-Mail content:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure></div>

Please double check with the tab "Digital Contents" / "Digitale Inhalte":

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure></div>

### Automated Reminder Mails to registered Participants

In the respective event in the menu bar on the left:\
“Send emails” → “Scheduled emails” → “Create new rule”

When you scroll down, the last item is “Time.” There, you can set, for example, that an email reminder is always sent one day before the event begins.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure></div>

### Certificates of Attendance

Certificates of attendance can be created for each course. The item can be found at the bottom left of the menu. If no button is visible there yet, you will need to activate the participation certificates under Settings -> Extensions.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Bildschirmfoto 2025-10-15 um 16.02.23.png" alt=""><figcaption></figcaption></figure></div>

{% columns %}
{% column width="33.33333333333333%" %}
<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (7) (1).png" alt="" width="151"><figcaption></figcaption></figure></div>


{% endcolumn %}

{% column width="66.66666666666667%" %}
If you click on “Print certificates of attendance”, the template that is selected as the default will be used and the certificates for all participants will be created in a pdf file.&#x20;

There is also the option of creating one for individual participants if you call up the participant's mask (there is a corresponding button there).

To create a layout for a certificate of attendance, you upload the pdf as a background (RLernen [here](https://drive.google.com/drive/folders/1_yBtA5t_JRsAKimdnny48Uot0ZZMuG3c), Data Literacy [here](https://drive.google.com/drive/folders/1235Uck0VAc7eFu0b6se0-hmKjinO4rn7)) and then insert blocks for the name and the course date. Ensure that you create personalised tickets for the event (under Products -> Personalisation) so that you can use the participant's name for the certificates.
{% endcolumn %}
{% endcolumns %}

### Cancel an Event on Pretix

Events that are created as independent events, can be cancelled via settings and "Cancel or Delete Event":

{% columns %}
{% column %}
<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure></div>
{% endcolumn %}

{% column %}
<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure></div>
{% endcolumn %}
{% endcolumns %}

For event series, individual dates can be deleted (trash can icon on the right), but not “cancelled.” Notifications and refunds must then be made manually for each individual order.

### Sending automated emails to people who did not attend the event (no-shows)

Automated emails can be set up in each event in the menu on the left under “Send emails” → “Scheduled emails” → “Create new rule.”

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure></div>

It is important to link the mailing to the check-in status (“unchecked-in participants”) and then to keep the check-in list in Pretix at the event itself:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure></div>
