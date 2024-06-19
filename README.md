change the link of serverUrl  in the code with your google sheet link 
and aslo change the script of the google sheet accordingly 
use aurdino ide to upload to esp32 any wrover kit 




Replace your_SSID, your_PASSWORD, and http://your-server.com/upload with your actual WiFi credentials and server URL.
Ensure your server-side script at http://your-server.com/upload is set up to handle incoming POST requests and store the data appropriately.





Create a Google Apps Script:

In the Google Sheet, go to Extensions -> Apps Script.
Delete any code in the script editor and replace it with the following:
paste the given google app script 

Deploy the Script as a Web App:

Click on Deploy -> New deployment.
In the "Select type" dropdown, select "Web app".
Set Execute as to Me and Who has access to Anyone.
Click Deploy.
Authorize the script with the required permissions.
After deployment, you will get a URL for the web app. Note this URL, as it will be used in the ESP32 code.

and use this link to serverurl.
