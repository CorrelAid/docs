# CorrelCloud

The CorrelCloud is a NextCloud instance hosted on our Manitu. There, we have cloud storage \(like Dropbox\) for administrative files, pictures from meetups, etc. 

* [correlcloud.org](https://correlcloud.org)

{% hint style="info" %}
Need access to the CorrelCloud? Ask **Thomas \(@thomas\)** or Frie \(@frie\) on Slack.
{% endhint %}

### Troubleshooting

#### The "CorrelCloud Webhosting Package" is running out of space. Why? 

Screenshot of the "Speicherplatz" area of the administration page for the CorrelCloud webhosting package which is accessible [here](https://mein.manitu.de/webhosting/) when logged in with the admin user.

![](../../.gitbook/assets/screenshot-2021-03-31-at-10.02.54.png)

This might be because certain users have not emptied their [trash bins](https://docs.nextcloud.com/server/13.0.0/user_manual/files/deleted_file_management.html) and old, large files might be occupying space in the bin. To solve, tell the suspected users to empty their trash bin via the CorrelCloud Web Interface \(in the side bar on the bottom left "Deleted Files"\). Alternatively, you can delete single files from users' trash bins via the WebFTP interface \(accessible from the administration page of the CorrelCloud webhosting package\). 

After emptying the trash bin of a CorrelCloud "power user":

![](../../.gitbook/assets/screenshot-2021-03-31-at-14.01.50.png)

