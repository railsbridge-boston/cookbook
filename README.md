# RailsBridge Boston Cookbook

This is the RailsBridge Boston cookbook, which includes various "How to" and
planning documents. This README is the timeline for planning a workshop.

Ask a lead organizer for access to credentials to the various services we use.

Here's a list of roles that are involved in organizing a workshop:

* 1-2 Lead Organizers
* Venue Coordinator - The venue may change with each workshop. Whoever does it
should commit to owning the process and maintaining communication with the venue
contact(s).
* Registration Coordinator
* Catering Coordinator
* Sponsorship Coordinator
* TA Coordinator
* Child Care Coordinator
* Installfest Coordinator
* MC

## Answering email (Organizer)

This is year-round task that involves monitoring the inbox and answering any
questions about the organization or the events we run.

We use [Inbox by Zendesk][inbox] to manage emails sent to the RBB. Anything that
is sent to the RBB address is automatically forwarded to our personal ones.

If there are multiple people managing the inbox, please make sure to assign
yourself to the email threads that you are participating in. If a conversation
is complete, please also mark it as "Done".

Checking in on a weekly basis in between workshops should suffice. As we get
closer to a workshop though, the inbox should be checked more frequently since
people may have last-minute questions, cancellations, or maybe child care requests.

It would also be good to check often right after a workshop has happened as
well.

[inbox]: https://www.zendesk.com/inbox/

## 6 months before

### Venue Coordinator

Book a venue for the event. See
[guidelines](/venue-coordination/README.md#workshop-venue-guidelines).

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

## 3 months before (Organizer)

Create a new Trello board based on the [Workshop Template].

Set up a meeting for everyone who's interested in coordinating for the next
workshop and invite them to the new Trello board.

[Workshop Template]: https://trello.com/b/AIqOY0yW/workshop-template

## 8 weeks before (Sponsorship Coordinator)

Start emailing potential sponsors. There's more in the [sponsorship
document](/sponsorship.md).

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

## 1 week before (Child Care Coordinator)

View the registrations and check for those who've opted in for child care. Send
them an email (all BCC'ed), explaining how it works, have them confirm that they
still need care, and if so, ask them for details about their children (age,
gender, special needs, which days and how long they need care for).

Give them 2-3 days to respond to you.

Use Sitter City to find a sitter that would accommodate the children that need
care. Be sure to coordinate how payment will work with the sitter.

## 1 week before

### Venue Coordinator

Find and book a bar/restaurant for our after-party at least a week in advance.
See the guidelines
[here](/venue-coordination/README.md#after-party-venue-guidelines).

### Installfest Coordinator

Make sure the docs are updated and any changes to Installfest VMs are live on
the website.

Run the spoon-building script to update the download files.

### Registration Coordinator

Remind attendees about attending (instructions [here][remind]).

[remind]: /registration/setting-up-registration.md#week-of-workshop

### MC

Prepare a slide deck with:

* Sponsor logos
* Link to Friday/Saturday Google docs
* Schedule for Friday/Saturday

We have sample slide decks in [the MC directory](/mc).

## 3 days before

### Venue Coordinator

Send NERD a list of names of everyone who might be there.

* It must be submitted 3 days in advance so they can distribute it to the
  security desk.
* Include all attendees, coordinators, TAs, guests, and waitlist names.
* Include the name of the event, dates, and room in the body of the email. For
  example.:

    > RailsBridge Boston event on 10/4/2013 from 7pm-10pm and 10/5/2013
    > from 9:30am-5pm in the Mann/Sampson/Paul room

* Send the list as a file attachment to nerdconf@microsoft.com, CC'ing whoever
  our NERD Center contact is and the lead coordinators. Re-emphasize that we
  want the desks set up in U shaped clusters.

### Registration Coordinator

If applicable, send an Eventbrite email to everyone about remembering their IDs
for front security.

## Friday afternoon (Organizer)

Get the following together to bring to the Installfest:

* 2 or 3 devices with Eventbrite check-in app installed
* Name tags (preprinted)
* Blank Hi-My-Name-Is name tags
* 2 hardcopies of attendee & TA list in case of manual check-in or front desk lost copy
* Sharpie markers
* RailsBridge stickers to give away
* Raffle tickets if a sponsor is doing a giveaway
* Colored dot stickers
* 15 USB flash drives with *updated* installation software
* 2 colors of post-it notes ("I'm all set" & "I have a question")

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
  (like anything in the NERD Center kitchen), etc.

#### Catering Coordinator

* Be at the NERD center when the delivery arrives before Friday night.

#### Organizer

* Bring badges for TAs
* Bring colored dot stickers for students so we know they went through the
  Installfest
* Handle Eventbrite check-ins as detailed [here][friday-registration]

[friday-registration]: /registration/setting-up-registration.md#friday-of-the-workshop

## Saturday, the big event (Everyone)

#### TA Coordinator

Remind the TAs about the kind of conduct we expect and how to talk to new
programmers. Look at our [Saturday TA pep talk](/TAs/giving-the-pep-talk.md#saturday).

#### MC

* Re-welcome everyone
* Go over the plan for the day
* Thank sponsors again
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
