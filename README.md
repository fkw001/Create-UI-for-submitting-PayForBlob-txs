#ALERT --disable-web-security work in Chrome

Run below commands in CMD to start a new instance of chrome browser with disabled security

Go to Chrome folder:

cd C:\Program Files (x86)\Google\Chrome\Application

Run below command:

chrome.exe --disable-web-security --user-data-dir=c:\my-chrome-data\data

#MAC OS:

Run this command in terminal:

open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_sess_1" --disable-web-security
