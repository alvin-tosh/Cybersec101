DELAY 1000
GUI r
DELAY 500
STRING explorer http://[IP ADDRESS]
DELAY 1000
STRING [USERNAME]
DELAY 500
TAB
DELAY 500
STRING [PASSWORD]
DELAY 500
ENTER
DELAY 5000
STRING login
DELAY 500
ENTER
DELAY 1000

This script will do the following:

    Open the Run dialog (Windows key + R)
    Open a web browser and navigate to the IP address of the temperature control system
    Simulate keystrokes to enter a specific username and password into the login page
    Simulate keystrokes to search for the word "login" on the page