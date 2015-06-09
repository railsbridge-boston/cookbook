# Announcing Registration

All credentials for Mailchimp, Eventbrite, Twitter, etc can be found in [this
repo][credentials].

[credentials]: https://github.com/railsbridge-boston/private/blob/master/credentials.md

## Make the event live

Sign into Eventbrite and find the appropriate event in [Your Events][events].

[events]: https://www.eventbrite.com/myevents/

Mark the event as live and ensure it's not password-protected.

## Unhide registration links on the RBB site

Don't forget to unhide registrations links on the RailsBridge site:

```
heroku config:set HIDE_REGISTRATION=false -a railsbridge-boston
```

## Mailchimp: Announce to the mailing list

This will create a campaign to send the announcement to the Upcoming Workshops
mailing list.

NOTE: This can be done ahead of time and saved until the announcement can be
sent out.

First, sign in to Mailchimp using the credentials [here].

[here]: https://github.com/railsbridge-boston/private/blob/master/credentials.md

1. Click "Create Campaign" in the top right of the dashboard
1. Select "Regular Campaign" and go to the next setp
1. Select the "Tell me about the next RBB workshop" list
  1. Select the entire list
  1. Go to next step
1. Enter/confirm the campaign details.
   1. Campaign name: June 2015 (or whatever month/year) Workshop Announcement
   1. From Name: RailsBridge Boston
   1. Email subject: Next RailsBridge Boston Workshop - Applications Open
   1. Reply-to email address: `railsbridgeboston@gmail.com`
   1. Personalize the `To:` field: `*|FNAME|*`
   1. Track opens
   1. Authenticate campaign
   1. Go to next step
1. Select "Saved Templates"
1. Select the appropriate workshop announcement template, i.e. either the Ruby
   one or the Rails one.
1. Select the corresponding section to edit the following information:
   1. Meta text at very top: "RailsBridge Boston [Month] workshop registration
      is open!"
   1. Main content: "[Month] Workshop"
   1. Main content:  Dates, location, and URLs
   1. Add any mentions of sponsors if necessary
   1. Update what the workshop will cover: is it Ruby basics or Rails?
1. Preview and test
1. Save
1. Look over the Plain Text version and go to next step.
1. Confirm the information. Exit if you are not ready to send the campaign; send
   now if you are.

## Announce on twitter

Sign in to Twitter and tweet about the workshop, linking to the Eventbrite page.

## Tell relevant groups

Send a message to relevant groups like DevChix, Boston Ruby, RailsBridge.

Possibly: The Girl Develop It and Womens Coding Collective.
