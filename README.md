# Android_ProximitySensorLocker
Android application which turns On/Off Screen and Turns On/Off Wi-Fi suing the Proximity Sensor 

Project Title - Proximity Sensor Locking

  ****************** Descirption *****************
  
I have used Proximity sensor to automatically lock and unlock the Phone.
Also the Wifi turns On/Off Automatically, when the screen goes On/off respectively.

The Operations like screen lock/unlock requires Admin rights for which the user will be asked
when using the Application for the first time.

Once the user clicks on the START SERVICE button, the service gets activated
This button serves dual functionality to Start.Stop the Service(App).

Whenever there an object near the proximity sensor(hand or keeping the phone inside the pcoket),
Phone screen gets locked and Wifi will be turned off automatically.

When there is no object within the range the defined value( I made it: 3, varies from phone to phone),
the screen gets unlocked automatically and Wifi too.

To enable the above mentioned functionalities, I have used Service, broadcastreceiver and Onclicklistener.

This works well when the phone is in Call state/Idle state too(after receiveing acll and starts talking).

Basically the proximity values differs for various Phones and Needs to be set carefully.

This can also be extended to read out Notifications, Missed calls Information as the screen gets unlocked.

I am looking to test this APP on more devices and release it to the Android Store.
