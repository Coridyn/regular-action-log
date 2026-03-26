Write me a simple, standalone web-page that lets me make a tracking log of when some regular thing has happened.

Interactions:

 - I want a prominent button that is easy to click
 - there should be a log of events that have occurred
 - when I click on the button a new entry with the current time is added to the log
 - the log should show the count of each entry (e.g. 1, 2, 3, etc.) and the local time that the event occurred (accurracy to the nearest second is fine)

Implementation:

 - the behaviour should run entirely client-side
 - the log of events should be persisted efficiently to the URL
 - I want to be able to share the full URL to someone else, when the load the page, it should restore the same state of the log
 - try to use native HTML/JavaScript/CSS - I don't want a bundling step or complex js framework involved
