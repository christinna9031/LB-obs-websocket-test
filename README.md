# LB OBS Websocket Test
 Extension for LioranBoard which lets you test connection to your OBS websocket, in case you cannot normally connect from LioranBoard. 
 1. Create a new button with a Send to Extension command and fill out the necessary fields. Leave password field empty if you did not set one up in your OBS websocket settings.
 2. Press the button. You should see three yellow notification messages in your Receiver, indicating the connection status and websocket version. If it says "Connection closed" or "Disconnected", your OBS websocket is not properly installed. If you can connect just fine, there must be something preventing LB from connecting to your websocket (old obs websocekt version, wrong settings, antivirus/firewall blocking it etc.). 
 
 ![Imgur example](https://i.imgur.com/9WEBeWY.png) 
 


**How to install an extension:**
1. Download the .lbe extension file
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above. 
