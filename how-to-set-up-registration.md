## CREATE AN EVENTBRITE EVENT

1. This can be done well in advance; EventBrite keeps drafts private until you
   make them live.

2. Ask an organizer for the RailsBridge Eventbrite account login information.

3. Copy the event page from the last workshop
   (http://help.eventbrite.com/customer/portal/articles/426069-copy-an-event-page)

4. Update the relevant information for the new workshop: *dates*, *location*,
   *number of tickets* available.

  Note that the event dates appear in several places, including the confirmation
  email text. The format for the custom URL is: railsbridgeboston[month and year
  of event].eventbrite.com.  For the Ruby workshop, be super-explicit that it's a
  mostly self-paced tutorial and that it doesn't include Rails.

5. Update the Order Confirmation page with the same info.

6. Reevaluate the number of tickets available.

The fire code limits us to 120 people (participants and TAs both) at the NERD
center.  We aim for 1 TA per 3 participants, so that's about 90 participants and
30 TAs.  For workshop 7 (January) we started with 110 tickets, which was about
perfect - 89 participants after cancellations, 82 showed up.  For workshops 5
and 6 we kept 90 available, churned through the waitlist, and had about 50
attendees.  We've been raising the initial number of tickets.

EventBrite will automatically trigger the waitlist when all tickets are sold,
but will NOT offer tickets to people on the wait list if tickets become
available through cancellation.

7. Make sure the childcare question is re-enabled or re-added.

It should be a radio button question that says, "Thanks to thoughtbot, we're
offering free in-home childcare through Parents in a Pinch. Do you need backup
childcare to attend the workshop?"

Add a secondary text field question for "Yes" answers that says, "Please provide
us with your phone #.  The child care coordinator will contact you to make
arrangements."

##  CREATE A MAILING CAMPAIGN
Create a campaign to send the announcement to the Upcoming Workshops mailing list.
NOTE: This can be done ahead of time and saved until the announcement can be sent out.

1. Ask an organizer for the MailChimp account login information.
2. Click Create Campaign    NOTE: MailChimp automatically saves all your changes.
3. Select "Regular Campaign" [Go to the next step.]
4. Select "Send to entire list" [Next step.]
5. Enter/confirm the campaign details.
      * Campaign name = [Month/year of the workshop] Workshop Announcement
      * From Name = RailsBridge Boston
      * Email subject = Next RailsBridge Boston Workshop - Applications Open
      * Reply-to email address = railsbridgeboston@gmail.com
      * Personalize the To: field = *|FNAME|*
      * Track opens
      * Authenticate campaign [Next step.]
6. Select "Saved Templates"
7. Select the appropriate workshop announcement template, i.e. either the Ruby
one or the Rails one.
8. Select the corresponding section to edit the following information:
      * Meta text at very top - "RailsBridge Boston [Month] workshop registration is open!"
      * Main content - "[Month] Workshop"
      * Main content -  Dates, location, and URLs
      * Add any mentions of sponsors if necessary
      * Update what the workshop will cover - is it Ruby basics or Rails?
9. Preview and test
10. Save
11. Look over the Plain Text version [Next step.]
12. Confirm the information. Exit if you are not ready to send the campaign; send now if you are.

## OPEN REGISTRATION
1. Use the campaign you created in MailChimp to notify the Upcoming Workshops mailing list about the new workshop.
2. Announce the workshop to the rest of the world:
     * Update the front page of the RailsBridge Boston site. Work with an organizer to push to heroku if necessary.
     * Ask the Twitter organizer or the person in charge of the RailsBridgeBos account to post
     * Send a message to relevant groups (DevChix, Boston Ruby, RailsBridge. Possibly: The Girl Develop It and Womens Coding Collective.)

## MANAGE REGISTRATION
1. Plan to spend 30-60 minutes on email a day for the first few days after registration opens. The questions will tend to be "it's sold out, can I bring a guest?", "is this workshop a good fit?", "I'm on the waitlist, am I in?", and "please add this sponsor's employee to the list". It tapers off quickly. (_Note: there has been less email overhead with Eventbrite. Update this estimate if the trend continues._)
2. RBB #5 and #6 filled up within a day and a half. Eventbrite will automatically open the wait list when registration is full.
3. Post an update after registration is full using the EventBrite "News and Updates" feature. Post a description of what wait list members could expect so they can plan. The update helps in reducing the number of email questions. People will still join the wait list.
3. Read through the registrations. To export the registration info to Excel, go to Event Reports and create a Survey Question report (http://help.eventbrite.com/customer/en_us/portal/articles/428605-attendee-summary-
report).
     * There is no "and guest" - everyone must register.
     * For men participants, check that they have a female host and that she has registered.
     * Check for duplicate entries.
4. Coordinate with the childcare organizer to arrange child care service, and give them contact info for the parents.
5. To offer a sponsored ticket: [Access codes](http://help.eventbrite.com/customer/portal/articles/426116-discount-codes-access-codes) for each sponsored participant. Access codes must be unique. Create the code for 1 use and save it. At the bottom of the Edit access code screen, you'll see a link/URL with the access code embedded in it. Send an email to the participant asking him/her to complete registration using that unique URL.

## WEEK OF WORKSHOP
1. On the Monday before the workshop send a reminder to attendees.
      * Ask them to cancel if plans have changed and mention that there is a waiting list.
      * A few will cancel ahead of time; most will cancel within 24 hours of start.
      * You can pre-write these emails and schedule delivery.
2. Coordinate with other organizers.
      * On Tuesday give the venue coordinator the names of all registrants and waitlisters. The NERD center needs a list by Wednesday for their security desk. Anyone not on the list must bring a photo ID. Use EventBrite's Event Reports feature as in the Manage Registrations step to get an Excel list.
      * Sponsored participants: As a thank-you, we do our best to give sponsors' employees a spot at the
        workshop. Coordinate with the sponsorship organizer to find out if any are on the waiting list and
        manually release a sponsored ticket to them if there's room.
      * Give the sponsorship coordinator the names and emails of registrants, minus any who opted out of
        sharing.
      * Tell the food coordinator how many people to expect. Send him/her the list of food restrictions participants have.
      * Ask the TA coordinator for TA names and final numbers. If fewer than expected signed up, we can raise the number of spots available for participants and still meet the fire code limit. Release tickets to the
        waiting list.
3. Release spots to the waitlist as you get cancellations.
     * First, edit the event so the number of tickets is well below the number of attendees. This is because EventBrite doesn't automatically offer tickets from the waiting list. If you don't change the limit, there will be a ticket available on the signup page for the next person who comes along. (UPDATE 9/15/13:
       New strategy tested; listed all 80 non-sponsored spots immediately to account for last-minute churn. UPDATE 10/05/13: We could have increased the number of tickets available to more than 80 since there was significant attrition through cancellations.)
     * Second, disable the childcare question on registration.  We need some advanced notice to arrange payment with our sponsor and Parents in a Pinch. We aren't able to arrange it last-minute, so make sure the question doesn't appear on the order form.
* EventBrite allows you to set how long a waitlister has to accept their ticket. The closer we get to the workshop, the shorter we set the time limit. On Monday, set the limit to 1 day and send invites in the morning. On Friday, set the limit very low, to a few hours.
     * Go to Manage > Waitlist . Change the "# to show per page" if necessary.  Click check boxes next to the name and click the Release Tickets link.
4. Print out a list of attendees and name tags. This is best done on Wednesday; we've found Friday is too hectic. Make a tag for all attendees, all waitlist, all TAs and presenters, and all organizers. There will be some churn in attendees, but it's easier to print extras than to do multiple batches.
     * Staples carries [name
     * tags](http://www.amazon.com/Avery-Top-Loading-Badges-Inches-74549/dp/B00007LVED/ref=sr_1_1?ie=UTF8&qid=1360795418&sr=8-1&keywords=pin+style+name+badges) and clips by Avery. Keep the receipt so you can get reimbursed.
     * It's best to assemble them before the workshop.
     * The simplest option to print name tags is to use the [Avery website ](http://www.avery.com/myavery/selectproduct.do?Ns=Rank%7C0&rpp=50&N=4294967035). It is easy to use and allows adding a logo. Start in EventBrite by exporting the list of attendees as a CSV file. Go to the Avery website and follow the wizard (basically, upload the RBB logo and import the csv file for the data).
NOTE: EventBrite has a name tag feature. The free version doesn't allow logos.  <http://help.eventbrite.com/customer/portal/articles/426329-print-name-badges>
     * If you don't have time to print tags, bring **Hi My Name Is ___** stickers and sharpies. Name tags make a real difference for breaking the ice.
5. Print out and bring a hard copy of the attendees and waitlist names, as a backup for check-in.


## FRIDAY OF THE WORKSHOP
 1. Two people should be doing check-ins. People often came in groups and it's sometimes tough to process them all at once. Make sure both can log in to EventBrite and they have the EventBrite app on their device before showtime. The EventBrite phone app will sync check-in data from multiple devices.
2. Track how many people attended vs. no-shows so we can make better predictions in future.


## AFTERWARD
1. Give the final attendance count to the person writing the recap.
2. After the event, give the sponsorship coordinator the email addresses of attendees.
     * Download the attendee list
       (see http://help.eventbrite.com/customer/en_us/portal/articles/428605-attendee-summary-report)
     * Open it in Excel; Remove anyone who opted out of email sharing.

## Q&A
**How many spots can we offer?**

Ideally every seat will be filled, but it's challenging. The fire code gives us a hard limit of how many people may be at the workshop site. There are always cancellations, but we don't have a good formula to predict how many. Most cancellations come in on Friday, and many waitlisters have made other plans. We're going to track attendance better so we have more data.

**I'm on the waitlist. Should I plan to come?**

The last-minute notice is hard on waitlisters. We try to set expectations so they can decide what they want to do. See the current waitlist message.

**What if a waitlister doesn't get a ticket and they really want to learn?**

Invite them to join the [announcement list](http://eepurl.com/vwrQT) so they'll be first to hear about the next workshop. If they want to get started in the meantime, direct them to [Boston Ruby Project Nights](http://bostonrb.org/), held the first Tuesday of every month. Boston RB works hard to welcome newcomers, and they always have at least one person available to help with machine setup and questions.

**Can someone come on Saturday only?**

We tried it and it didn't work. Everyone has to come to Installfest so their machine is ready to go on Saturday. We can't catch someone up before the lecture, especially when the network is overloaded. We also cover some foundational materials on Friday, like using the command line, that they'll need for Saturday's curriculum.
