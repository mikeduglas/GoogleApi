# GoogleApi
GoogleApi for Clarion

v1.00 Calendar and Contacts

**Calendar**
- Lists upcoming events; allows to insert/update/delete events, assign a color to an event. 
- Note: the application now uses "client_secret_calendar.json" file instead of "client_secret.json".

**Contacts**
- Lists all contacts; allows to insert/update/delete contacts. You can set contact names, addresses, emails, phone numbers, day of birth, photos, 
and choose which contact groups the contact belongs to. 
- Note: the application uses "client_secret_contacts.json" file.


Requires NET4.5.

Classes and templates are available for registered users. Email me (mikeduglas@yandex.ru) for more info.
  
  
## Price
$150 for each, $250 for both.
  
## Contacts
[mikeduglas@yandex.ru](mailto: mikeduglas@yandex.ru)  
[mikeduglas66@gmail.com](mailto: mikeduglas66@gmail.com)

  
**How to obtain client_secret file**
* Create "Calendar" application in Google Console, obtain client_secret_calendar.json file and place it in exe folder.
First time you run demo app, it will ask you to confirm calendar access (web browser pops up).


[Turn on the Google Calendar API](https://developers.google.com/google-apps/calendar/quickstart/dotnet#prerequisites)
* a.Use this wizard to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials.
* b.At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button. 
* c.Select the Credentials tab, click the Create credentials button and select OAuth client ID. 
* d.Select the application type Other, enter the name "Google Calendar API Quickstart", and click the Create button.
* e.Click OK to dismiss the resulting dialog. 
* f.Click the file_download (Download JSON) button to the right of the client ID.
* g.Move this file to your working directory and rename it client_secret_calendar.json. 
