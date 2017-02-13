### aws-iot-tweet
Send customizable tweets using the AWS IOT button

### Setup
- Install AWS IOT Button app on you iOS or Android phone.
- Lauch the app and login with your AWS/Amazon credentials.
- Click the "+" symbol on the top left to add your IOT button.
- This launches the "Setup your button" process.
- Select "Agree & get started".
- With your phone, scan the barcode on the box the IOT button came in by choosing "Tap here to scan barcode". You can also manually enter the serial number (DSN) listed on the box or the back of the IOT button.
- You can give it a friendly name at the point (say, "Tweet_Button"), then select "Register Button".
- This creates the necessary resources in AWS IOT.
- Next, configure the button by pressing it for 6 seconds until the blue light flashes.
- After that go to your phone's settings and connect to the button's wi-fi network using the provided credentials (you can copy the wi-fi password to your clipboard)
- Once connected, pick the wi-fi network that your button should use.
- Next, set the bitton action i.e. choose what to do when your button is pressed.
- For now, choose "Send SMS (nodejs)" to test that the button is functioning correctly, and provide the phone number 1-xxx-xxxx where you want to receive it.
- Click set action.
- Your button should now appear on the main screen on the AWS IOT button app, listed with its name, serial number and your selected action.
- Press the button. It will flash white for several seconds and then stop flashing.
- You should receive the sms shortly. If you receive it, your IOT Button is ready to go!
- Note that from the main screen - you can change the wireless network by selecting the wi-fi icon next to the button. You can change the button action by selecting the "lambda" symbol.


- Note that if the button flashes white for a long time and then briefly flashes red, it means it was not configured correctly.
- In that case, select the delete icon on the main screen of the app next to the button.
