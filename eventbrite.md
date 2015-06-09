## Create an Eventbrite event

1. This can be done well in advance; EventBrite keeps drafts private until you
   make them live.

2. Check the [private repo][credentials] for the RailsBridge Eventbrite account
   login information.

3. Copy the event page from the last workshop
   (http://help.eventbrite.com/customer/portal/articles/426069-copy-an-event-page)

4. Update the relevant information for the new workshop: *dates*, *location*,
   *number of tickets* available.

  Note that the event dates appear in several places, including the confirmation
  email text. The format for the custom URL is: railsbridgeboston[month and year
  of event].eventbrite.com.  For the Ruby workshop, be super-explicit that it's a
  mostly self-paced tutorial and that it doesn't include Rails.

5. Update the Order Confirmation page with the same info.

6. Re-evaluate the number of tickets available.

    The fire code limits us to 120 people (participants and TAs both) at the NERD
    center.  We aim for 1 TA per 3 participants, so that's about 90 participants and
    30 TAs.  For workshop 7 (January) we started with 110 tickets, which was about
    perfect - 89 participants after cancellations, 82 showed up.  For workshops 5
    and 6 we kept 90 available, churned through the waitlist, and had about 50
    attendees.  We've been raising the initial number of tickets.

    Eventbrite will automatically trigger the waitlist when all tickets are sold,
    but will NOT offer tickets to people on the wait list if tickets become
    available through cancellation.

7. Make sure the childcare question is re-enabled or re-added.

  It should be a radio button question that says, "Thanks to thoughtbot, we're
  offering free in-home childcare through Parents in a Pinch. Do you need backup
  childcare to attend the workshop?"

  Add a secondary text field question for "Yes" answers that says, "Please provide
  us with your phone #.  The child care coordinator will contact you to make
  arrangements."

[credentials]: https://github.com/railsbridge-boston/private/blob/master/credentials.md
