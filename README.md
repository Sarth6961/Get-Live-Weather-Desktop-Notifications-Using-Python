# Get-Live-Weather-Desktop-Notifications-Using-Python
We know weather updates are how much important in our day-to-day life. So, We are introducing the logic and script with some easiest way to understand for everyone. Let’s see a simple Python script to show the live update for Weather information. 

## Modules Needed
In this script, we are using some libraries

## bs4: Beautiful Soup(bs4) is a Python library for pulling data out of HTML and XML files. To install this module type the below command in the terminal.
pip install bs4
## win10toast: This library helps in creating desktop notifications. To install this module type the below command in the terminal.
pip install win10toast
## requests: This library allows you to send HTTP/1.1 requests extremely easily. To install this module type the below command in the terminal.
pip install requests

## Approach :

Extract data form given URL.
Scrape the data with the help of requests and Beautiful Soup.
Convert that data into html code.
Find the required details and filter them.
Save the result in the String.
Pass the result in Notification object.
