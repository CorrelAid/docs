# Kobotoolbox for Forms

We host our own instance of [kobotoolbox](https://www.kobotoolbox.org/) at [kobo.correlaid.org](https://kobo.correlaid.org).

## User management

Users are managed by _super admins_ in the administrative backend which is available at [kobo.correlaid.org/admin](https://kobo.correlaid.org/admin).

Here, admins can create and delete users and manage other settings of the Kobo instance \(but most of which should be just left alone\). 

**Important**: this is not where you give access to individual surveys etc. This is done in the User Interface at [kobo.correlaid.org](https://kobo.correlaid.org).

### Adding a User

Click on "Add" next to "Users" and you can set a user name and password for the new user. 

Important: **User names should follow the {firstname}-{lastname} format** \(similar to [Manitu](email.md#user-name-and-inbox) username\). Using dots \("."\) in user names definetly causes some weird problems, so this should be avoided at all cost. The password should obviously follow good password principles.  

![](../../.gitbook/assets/screenshot-2021-03-03-at-09.53.17.png)

Once you click on "Save", you'll be redirected to the settings page for this user. Leave the default settings and click "Save" again.

## Subscribe to the CorrelAid collection

We have created the **public CorrelAid collection** which you can see when going to [https://kobo.correlaid.org/\#/library](https://kobo.correlaid.org/#/library) and selecting "Public collections" in the bar on the left. The collection provides template surveys and question blocks for questions that we ask. In order to use the questions and template surveys in this collection, you need to "subscribe" to it. Unfortunately, there is a [bug](https://github.com/kobotoolbox/kpi/issues/2813) in the frontend of Kobo - the "Subscribe" button does not work. However, there is a workaround:

1. Open [https://kobo.correlaid.org/collection\_subscriptions/](https://kobo.correlaid.org/collection_subscriptions/). 
2. In the dropdown at the bottom, select "CorrelAid" if it is not already selected. 
3. Click "POST"
4. If you go back to [https://kobo.correlaid.org/\#/library](https://kobo.correlaid.org/#/library), the CorrelAid collection should now be in your personal library and you can use the questions and/or the template surveys.

![](../../.gitbook/assets/screenshot-2021-03-03-at-10.04.42.png)

#### Use the template surveys

When creating a new project, you can use the template surveys by selecting "Use a template" in the "Create project" dialogue. This will copy the template survey into your project.

![](../../.gitbook/assets/screenshot-2021-03-03-at-10.09.44.png)







