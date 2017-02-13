### aws-iot-tweet
Send customizable tweets using the AWS IOT button

### Setup
- Install AWS IOT Button app on you iOS or Android phone.
- Lauch the app and login with your AWS/Amazon credentials.
- Click the "+" symbol on the top left to add your IOT button.
    - This launches the "Setup your button" process.
    - Select "Agree & get started".
- With your phone, scan the barcode on the box the IOT button came in by choosing "Tap here to scan barcode". You can also manually enter the serial number (DSN) listed on the box or the back of the IOT button.
- Once the serial number has been entered, you can (optionallly) give your Button a friendly name to distinguish it.
- Next, select "Register Button".
    - This creates the necessary resources in AWS IOT.
- Next, configure the button by pressing it for 6 seconds until the blue light flashes.
    - Now go to your phone's settings and connect to the button's wi-fi network using the provided credentials (you can copy the wi-fi password to your clipboard)
    - Once connected, pick the wi-fi network that your button should use.
- Next, set the button action i.e. choose what to do when your button is pressed.
    - For now, choose "Send SMS (nodejs)" to test that the button is functioning correctly, and provide the phone number 1-xxx-xxxx where you want to receive it.
    - Click set action.
- Your button should now appear on the main screen on the AWS IOT button app, listed with its name, serial number and your selected action.
- Press the button. It will flash white for several seconds and then stop flashing.
- You should receive the sms shortly. Once you receive it, your IOT Button is fully configured and ready to go!

Note that from the main screen, you can change the wireless network by selecting the wi-fi icon next to the button. You can change the button action by selecting the "lambda" symbol.

Finally, note that if the button flashes white for a long time and then flashes red for 3 times before flashing stops - it means that it was not configured correctly. In that case, select the "Delete" icon on the main screen of the app next to the button. Then start the configuration process described above all over again.
