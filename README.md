# Steps to reproduce:
- clone the repository
- cd expo37notificationBug
- npm install | yarn
- expo start
- start the app on the phone
- close expo AND the app
- copy the expo push token from the terminal 
- open https://expo.io/notifications
- send a notification to this push token
- click on the notification on the phone

There should be not data visible
