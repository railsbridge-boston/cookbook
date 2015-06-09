# RailsBridge Boston Cookbook

This is the RailsBridge Boston cookbook, which includes various "How to" and
planning documents. This README is the timeline for planning a workshop.

Look in our [private repo][private] for credentials for our GMail/Twitter/etc.

[private]: https://github.com/railsbridge-boston/private

Here's a list of who's who:

* Organizer: May change depending on the workshop, ask Melissa Xie if you don't
  know who it is
* Venue Coordinator: changes with each workshop, whoever does it should commit
  to owning the process
* Registration Coordinator: usually the organizer, again
* Catering Coordinator: Mash Inglis
* Sponsorship Coordinator: Julissa Jansen
* TA Coordinator: Margaret Scott
* MC: changes with each event. We try to get an MC a few weeks before.

## Answering email (Organizer)

This is not around  organizing a specific event - the organizer should check in
with email every so often.

People will have questions, especially as the event approaches and immediately
after an event.

## 6 months before (Venue Coordinator)

Book a venue for the event. It should be free, hold at least 100 people, and be
as easily accessible as possible (e.g. the T, parking).

After booking, the organizer will coordinate with the venue contact over any
logistics when using the space, e.g.  what's off-limits, equipment use,
catering, security, etc.

We like using the Microsoft NERD center to host our events, because it's free
and and they handle a lot of things for us. They require a lot of advance
notice, though, so *at least* 6 months before the event, fill out [this
form][nerd-form].

[nerd-form]: http://microsoftcambridge.com/eventmanager/

They will reply with a confirmation email that includes a link to an event
details form. Here are some things you can use to fill out that form:

* Event title: RailsBridge Boston
* Event audience: Women in Boston
* Registration link: Eventbrite link
* Twitter handle: railsbridgebos
* Event description: RailsBridge Boston (http://www.railsbridgeboston.org/) is a
  two-day workshop that Ruby on Rails to women in the Boston community.
* Event logo: Use [this file](/logos/logo.png).

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

We place catering orders ~1.5 weeks before the workshop. We assume about 100
people will attend, but double check that number. For more information, see
[this document](/catering.md).

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
