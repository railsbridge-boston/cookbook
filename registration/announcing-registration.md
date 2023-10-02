# Announcing Registration

## Make the event live

Sign into Eventbrite and find the appropriate event in [Your Events][events].

[events]: https://www.eventbrite.com/myevents/

Mark the event as live and ensure it's not password-protected.

Click "Edit" on the event and ensure the dates in the event description are correct

Then click the "Manage" tab and click "Order confirmation" in the left sidebar.
Ensure the dates for all of the order confirmation text are correct too.

## RailsBridge Boston website

To show the registration link on the website, we need to set the following
environment variables:

|variable|value|
|---|---|
|`HIDE_REGISTRATION`|`true`/`false`|
|`EVENT_URL`|registration URL|
|`VENUE_NAME`|name of the venue|
|`VENUE_ADDRESS`|full address of venue|
|`VENUE_MAP_URL`|Google Maps embed URL|

## MailChimp

This will create a campaign to send the announcement to the Upcoming Workshops
mailing list.

NOTE: This can be done ahead of time and saved until the announcement can be
sent out.

ALSO NOTE: Some of this interface is somewhat confusing and possibly unclear since the last time this page was updated. Use these steps as a guide, not as a required checklist. You maybe have to improvise and use some best judgement to get this done. But you're smart and can totally handle it.

First, sign in to Mailchimp.

1. Click "See all campaigns" 
2. Click "Create new" in the top right of the dashboard
3. Select "Email Campaign" and go to the next step
4. Ensure "Regular" is selected from the choices on top
5. Title the list "June 2015 (or whatever month/year) Workshop Announcement"
6. Go to next step
7. Enter/confirm the campaign details.
  1. Recipients: Tell me about the next RailsBridge Boston Workshop
  2. Segment or Tag: All subscribers on list
  3. Personalize the `To:` field: `*|FNAME|*`
  4. From Name: RailsBridge Boston / railsbridgeboston@gmail.com
  5. Email subject: Next RailsBridge Boston Workshop - Applications Open
9. Click `Design Email` to go to next step
10. Select "Saved Templates"
11. Select the appropriate workshop announcement template, i.e. either the Ruby
   one or the Rails one.
12. Select the corresponding section to edit the following information:
   1. Note: Likely most of this is in place already :)
   2. Meta text at very top: "RailsBridge Boston [Month] workshop registration
      is open!"
   3. Main content: "[Month] Workshop"
   4. Main content:  Dates, location, and URLs
   5. Add any mentions of sponsors if necessary
   6. Update what the workshop will cover: is it Ruby basics or Rails?
13. Save & Close
14. Click on `Edit` next to Setting & Tracking at the bottom of the page and make sure Track opens is checked
15. Click `Save`
16. Preview and test - look it over, send yourself a test email.
17. Find the very small "Edit" link on the campaign page near the Plain-Text email explanation and click it to make sure the formatting isn't wonky
18. Exit if you are not ready to send the campaign; send now or schedule if you are.

## Twitter

Sign in to Twitter and tweet about the workshop, linking to the event page.

## Craigslist

You can post an event under the community pages in Craigslist: Boston -> Community, then pick a category (perhaps "events" or "classes"). 

Here's an example post:

![image](https://github.com/railsbridge-boston/cookbook/assets/222655/1c782277-689f-446d-9461-7d077a997988)

You should post from a registered craigslist account so you can log in weekly and "renew" the listing so it appears on the index page again: 
![image](https://github.com/railsbridge-boston/cookbook/assets/222655/5fd52b40-ffbf-4e1c-90db-ebd1237c7299)

If you don't do this, it will disappear entirely from the site in a few days.
