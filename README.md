# RailsBridge Boston Cookbook

This is the RailsBridge Boston cookbook, which includes various "How to" and
planning documents. This README is the timeline for planning a workshop.

Ask a lead organizer for access to credentials to the various services we use.

Here's a list of roles that are involved in organizing a workshop:

* 1-2 Lead Organizers
* Venue Coordinator
* Registration Coordinator
* Catering Coordinator
* Sponsorship Coordinator
* TA Coordinator
* Child Care Coordinator
* Installfest Coordinator
* MC

## 6 months before

### Registration Coordinator

Once a space has been booked, create a *private* (password-protected) copy of
the most recent Eventbrite event. Instructions are in the [eventbrite
doc](/registration/eventbrite.md).

Copy the event ID from the Eventbrite URL and update the `NEXT_EVENT_ID`
environment variable on Heroku using that value. If you don't have Heroku access
to the app, ask a Lead Organizer for access or for them to update it for you.

The RailsBridge Boston website will automatically fetch details about the event
and display it. For now, hide that section temporarily by setting the
`HIDE_REGISTRATION` variable to `true`.

## 8 weeks before (Sponsorship Coordinator)

Start emailing potential sponsors. There's more info in the [finances
document](/finances.md).

## 5 weeks before (Registration Coordinator)

Update any necessary information on the event page (check the Eventbrite docs).

Open up registration. Step-by-step information on announcing the newly-open
registration is in [this document](/registration/announcing-registration.md).

Unhide registration on the website by setting `HIDE_REGISTRATION` to `false`.

Plan to spend 30-60 minutes per day on the RBB email account after registration
opens; we have some [answers to FAQs](/registration/setting-up-registration.md#faqs).

## 1.5 weeks before (Catering Coordinator)

Find 2-3 different vendors that we can work with. If our venue has a specific
list of vendors we can use, please accommodate that.

Get a CSV of all the attendees, including TAs, to get a rough head count and a
sense of what the dietary restrictions are.

Assume about 60% of the people who registered + number of TA's will attend.  For
more information, see [this document](/catering.md).

## 1 week before

### Installfest Coordinator

Make sure the docs are updated and any changes to Installfest VMs are live on
the website.

Run the [spoon-building
script](https://github.com/railsbridge-boston/spoon-builder) to update the
download files.

### Registration Coordinator

Remind attendees about attending (instructions [here][remind]).

[remind]: /registration/setting-up-registration.md#week-of-workshop

### MC

Prepare a slide deck with:

* Sponsor logos
* Link to Friday/Saturday Google docs
* Schedule for Friday/Saturday

We have sample slide decks in [the MC directory](/mc).
We have a more detailed outline for MCing [here](/mc/mc-tips.md).

### Child Care Coordinator

View the registrations and check for those who've opted in for child care. Send
them an email (all BCC'ed), explaining how it works, have them confirm that they
still need care, and if so, ask them for details about their children (age,
gender, special needs, which days and how long they need care for).

Give them 2-3 days to respond to you.

Use Sitter City to find a sitter that would accommodate the children that need
care. Be sure to coordinate how payment will work with the sitter.

## 3 days before

### Registration Coordinator

If applicable, send an Eventbrite email to everyone about remembering their IDs
for front security.


## Friday Night (everyone)

#### TA Coordinator

Remind the TAs about the kind of conduct we expect and how to talk to new
programmers. Look at our [Friday TA pep talk](/TAs/giving-the-pep-talk.md#friday).

#### MC

* Welcome everyone
* Brief intro of what to expect this weekend
* Thank sponsors
  * show logos
  * give special "shout outs" to any organizations that are sponsoring any
    specific portion of the weekend, e.g. a whole meal, the whole workshop, the
    after-party, etc.
  * have sponsor representatives do an intro
* TA introductions - name and what they do
* Go over the plan for the night
  * point them to the pages with instructions
  * make sure the TAs are evenly distributed across the room, especially
    according to OSes
* Go over any other logistics - e.g. where the bathrooms are, what's off limits
  (like anything in the venue kitchen), etc.
* Announce that photography will be taking place for social media and marketing
  purposes. Remind people that red dots are available at the sign-in desk.

For more details go [here](/mc/mc-tips.md).

#### Catering Coordinator

* Be at the venue when the delivery arrives before Friday night.

## Saturday, the big event (Everyone)

#### TA Coordinator

Remind the TAs about the kind of conduct we expect and how to talk to new
programmers. Look at our [Saturday TA pep talk](/TAs/giving-the-pep-talk.md#saturday).

#### MC

* Re-welcome everyone
* Go over the plan for the day
* Thank sponsors again
* Remind about photography and the red stickers again
* Have TAs form small groups
* Announce meals
* Mention after-party - how to get there, what is covered, who's sponsoring
* Lead or encourage frequent stretching in between sections
* Talk about next steps
* Encourage connecting with TAs and other attendees

#### After-party

We offer the first round of drinks and appetizers, which typically costs about
$700, based on 30-40 of the 80-90 attending. Feel free to add another round of
drinks or more food as the budget allows. We paty for the food and drinks on
that day, directly to the bar.
