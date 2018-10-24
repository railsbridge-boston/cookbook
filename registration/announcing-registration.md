# Announcing Registration

All credentials for Mailchimp, Eventbrite, Twitter, etc can be found in [this
repo][credentials].

[credentials]: https://github.com/railsbridge-boston/private/blob/master/credentials.md

## Make the event live

Sign into Eventbrite and find the appropriate event in [Your Events][events].

[events]: https://www.eventbrite.com/myevents/

Mark the event as live and ensure it's not password-protected.

Click "Edit" on the event and ensure the dates in the event description are correct

Then click the "Manage" tab and click "Order confirmation" in the left sidebar.
Ensure the dates for all of the order confirmation text are correct too.

## Unhide registration links on the RBB site

Don't forget to unhide registrations links on the RailsBridge site:

```
heroku config:set HIDE_REGISTRATION=false -a railsbridge-boston
```

## Update map on the RBB site

VENUE_MAP_URL is the environment variable to update in order to have the correct map appear on the RBB site.

## Mailchimp: Announce to the mailing list

This will create a campaign to send the announcement to the Upcoming Workshops
mailing list.

NOTE: This can be done ahead of time and saved until the announcement can be
sent out.

First, sign in to Mailchimp using the credentials [here].

[here]: https://github.com/railsbridge-boston/private/blob/master/credentials.md

1. Click "Create" in the top right of the dashboard
2. Select "Email Campaign" and go to the next step
3. Ensure "Regular" is selected from the choices on top
4. Title the list "June 2015 (or whatever month/year) Workshop Announcement"
5. Go to next step
6. Enter/confirm the campaign details.
  1. Recipients: Tell me about the next RailsBridge Boston Workshop
  2. Segment or Tag: All subscribers on list
  3. Personalize the `To:` field: `*|FNAME|*`
  4. From Name: RailsBridge Boston / railsbridgeboston@gmail.com
  5. Email subject: Next RailsBridge Boston Workshop - Applications Open
9.  Go to next step
10. Select "Saved Templates"
11. Select the appropriate workshop announcement template, i.e. either the Ruby
   one or the Rails one.
12. Select the corresponding section to edit the following information:
   1. Meta text at very top: "RailsBridge Boston [Month] workshop registration
      is open!"
   2. Main content: "[Month] Workshop"
   3. Main content:  Dates, location, and URLs
   4. Add any mentions of sponsors if necessary
   5. Update what the workshop will cover: is it Ruby basics or Rails?
   6. Likely most of this is in place already :)
13. Save & Close
14. Click on "Edit" next to Setting & Tracking at the bottom of the page and make sure Track opens is checked
15. Preview and test - look it over, send yourself a test email.
16. Find the very small "Edit" link on the campaign page near the Plain-Text email explanation and click it to make sure the formatting isn't wonky
17. Exit if you are not ready to send the campaign; send now or schedule if you are.

## Announce on twitter

Sign in to Twitter and tweet about the workshop, linking to the Eventbrite page.
