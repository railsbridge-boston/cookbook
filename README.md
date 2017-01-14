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

Checking in on a weekly basis in between workshops should suffice. As we get
closer to a workshop though, the inbox should be checked more frequently since
people may have last-minute questions, cancellations, or maybe child care requests.

It would also be good to check often right after a workshop has happened as
well.

## 6 months before (Venue Coordinator)

Book a venue for the event. It should be free, hold at least 100 people, and be
as easily accessible as possible (e.g. the T, parking).

The timeframes we need are: **Friday 6:00-9:30pm** and **Saturday
9:00am-5:30pm**. These timeframes include 30-minute prep/setup at the beginning
of each day and then a little bit of time to clean up at the end. If we could
arrive earlier to accommodate catering arrivals, that would be great.

When talking to someone about the venue, be sure to ask about any logistics when
using the space, e.g. what's off-limits, equipment use, catering (do they have
preferred vendors, where should they come in, etc.), security, etc.

If we're offering onsite childcare, we make sure there's a separate room that
our babysitter and children can stay in.

Create a *private* (password-protected) copy of the most recent Eventbrite
event. Instructions are in the [eventbrite doc](/eventbrite.md).

To make it private, scroll down to "3. Additional Settings", click "Private
page", and add a password. Now you have something to fill in the "Event
registration link" with.

It will still pop up on the RailsBridge Boston web site, which pulls in
Eventbrite events automatically. You should hide it by running:

```
heroku config:set HIDE_REGISTRATION=true -a railsbridge-boston
```

## 8 weeks before (Sponsorship Coordinator)

Start emailing potential sponsors. There's more in the [sponsorship
document](/sponsorship.md).

## 5 weeks before (Registration Coordinator)

Set up registration. There should already be an Eventbrite event that you
created (see above under venue), but:

* We should have 100 student tickets
* We should have 20 TA tickets (password-protected)

## 3 weeks before (Registration Coordinator)

Open up registration. Step-by-step information on announcing the newly-open
registration is in [this document](/announce-registration.md).

Plan to spend 30-60 minutes per day on the RBB email account after registration
opens; we have some [answers to FAQs](/how-to-set-up-registration.md#faqs).

Student registration usually fills up in a day. We open up TA registration a
week after student registration so that we know how many students will attend.
Both ticket types (student and TA) should stop accepting new entries about a
week before the event so that we can review and accept TAs, print out name tags,
etc.

## 2 weeks before (Organizer)

Find an MC.

## 1.5 weeks before (Catering Coordinator)

We place catering orders ~1.5 weeks before the workshop. We assume about 75% of
the people who registered + number of TA's will attend, but double check that
number. For more information, see [this document](/catering.md).

## 1 week before (Child Care Coordinator)

View the registrations and check for those who've opted in for child care. Send
them an email (all BCC'ed), explaining how it works, have them confirm that they
still need care, and if so, ask them for details about their children (age,
gender, special needs, which days and how long they need care for).

Give them 2-3 days to respond to you. Coordinate payment between the sponsor and
the child care provider.

## 1 week before (Venue Coordinator)

Find and book a bar/restaurant for our after-party at least a week in advance.
For more information see our [after party venues doc](/after-party-venues.md).

## 1 week before (Organizer)

Make sure the docs are updated and any changes to Installfest VMs are live on
the website.

Remind attendees about attending (instructions [here][remind]).

[remind]: /how-to-set-up-registration.md#week-of-workshop

## 1 week before (MC)

MC should ready a  slide deck with:

* Sponsor logos
* Link to Friday/Saturday Google docs
* Schedule for Friday/Saturday

We have sample slide decks in [the MC directory](/mc).

## 3 days before (Venue Coordinator)

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

Send an Eventbrite email to everyone, TAs *and* students, asking them to be sure
that they bring a photo ID, per NERD Center policy.

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
programmers. Look at our [Friday TA pep talk](/ta-pep-talk/friday.md).

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

[friday-registration]: /how-to-set-up-registration.md#friday-of-the-workshop

## Saturday, the big event (Everyone)

#### TA Coordinator

Remind the TAs about the kind of conduct we expect and how to talk to new
programmers. Look at our [Saturday TA pep talk](/ta-pep-talk/saturday.md).

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
