# GoogleApi
GoogleApi for Clarion

v0.98 Calendar support
- NEW: Demo app. Allows to insert/update/delete/list of Google Calendar events. Requires NET4.5.

Create "Calendar" application in Google Console, obtain client_secret.json file and place it in exe folder.
First time you run demo app, it will ask you to confirm calendar access (web browser pops up).


Turn on the Google Calendar API
* a.Use this wizard to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials.
* b.At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button. 
* c.Select the Credentials tab, click the Create credentials button and select OAuth client ID. 
* d.Select the application type Other, enter the name "Google Calendar API Quickstart", and click the Create button.
* e.Click OK to dismiss the resulting dialog. 
* f.Click the file_download (Download JSON) button to the right of the client ID.
* g.Move this file to your working directory and rename it client_secret.json. 

https://developers.google.com/google-apps/calendar/quickstart/dotnet#prerequisites