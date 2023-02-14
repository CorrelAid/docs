# Newsletter: MailerLite

## Groups and segments&#x20;

MailerLite does not have separate "Audiences" like Mailchimp. All subscribers are part of the same table/database.&#x20;

MailerLite differentiates between groups and segments. Segments are dynamic based on subscriber information, e.g. based on when the subscriber last openend an email. Groups are static, i.e. users have to be added to them, either manually or through a signup form. Learn more [here](https://www.mailerlite.com/video-tutorials/groups-vs-segments).

### Groups

Groups are most like our old "Audiences". Hence, they are the primary way how we group subscribers and send emails to specific people.&#x20;

Currently, we have **groups** for the following:&#x20;

* Volunteer Newsletter: the "main" big newsletter. Subscribers are added through the signup form embedded on our website (see "Forms")
* one group per (active) CorrelAidX chapter: subscribers are added to this group through the signup form for the volunteer newsletter if they tick the corresponding checkbox for the local chapter.&#x20;
* Nonprofit Newsletter: the newsletter for nonprofits. Subscribers are added through the signup form embedded/linked to on our website (see "Forms")
* Mitglieder: Members of CorrelAid e.V. Subscribers are added and managed manually by the Board of CorrelAid e.V.&#x20;

It is important to note, that people can be part of multiple groups. For example, a person might subscribe to the volunteer newsletter and one CorrelAidX chapter. In addition, they're also member of the CorrelAid e.V.. Despite this, **there would only be one entry for this person in the overall subscriber database** (except if they gave a different email in the "become member" form).&#x20;

### Segments

In addition, we also use segments.&#x20;

#### GDPR segments&#x20;

Segments that are based on consent (according to GDPR) given by the subscriber in the signup forms.

* Volunteer Analysis: all subscribers of the volunteer newsletter who have consented to their personal data (gender, year of birth, country of residence, city of residence) being used for anonymous statistics. This segment should be exported/used when doing analytics.
* Volunteer Contact New Chapters: all subscribers of the volunteer newsletter who have consented to their personal data (city of residence, country of residence) being used when a new chapter opens or is reactivated in their area.&#x20;
  * This segment should be subset further and then used whenever we want to reach out to people for starting a new chapter.&#x20;
  * Once a new chapter is established in the area and we have created a _group_ (see above), we can transfer the affected users to the group.

## Sending a newsletter

In general, sending a newsletter (a "campaign" in MailerLite terms) is easy:

1. Go to [Campaigns](https://dashboard.mailerlite.com/campaigns/) and click "Create Campaign"&#x20;
2. Follow the wizard

{% hint style="success" %}
You select the audience / people you want to send the newsletter to in step 3 of the wizard.&#x20;
{% endhint %}

