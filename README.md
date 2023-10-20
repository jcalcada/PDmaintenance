# PDmaintenance


This utility will allow you to select one of your PagerDuty technical services and put it into maintenance mode
You will then be sent an incident to your "Maintenance Monitor" technical service indicating the service that went into maintenance and when
Don't forget to take your service OUT of maintenance at some point.
Certain security aspects to consider: token, where to put it?  i run it locally on my machine so i just hard code it.
replace the "from" header to be your own from

