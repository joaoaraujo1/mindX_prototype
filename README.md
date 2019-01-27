# mindX_prototype
This README contains a short description of the first mindX app prototype that I coded for [mindreach](http://www.mindreach.org/). Overall this app allows you to monitor your brain waves and use such brain waves to play a few mini-games in your Android device. 

<img src="https://user-images.githubusercontent.com/40466329/51793745-5596ea00-21bd-11e9-8441-33a337a82ece.jpg" alt="alt text" width="250" height="416"> <img src="https://user-images.githubusercontent.com/40466329/51793856-3bf6a200-21bf-11e9-9653-49e04eb581f0.png" alt="alt text" width="250" height="416"> <img src="https://user-images.githubusercontent.com/40466329/51793854-3a2cde80-21bf-11e9-97ef-83cd81ce5561.jpg" alt="alt text" width="250" height="416">

To obtain the neural recordings, a wireless dry-EEG headset with 5 channels developed by the company is needed. The headset communicates with the smartphone using a 2.x Bluetooth protocol.

<img src="https://user-images.githubusercontent.com/40466329/51793930-38174f80-21c0-11e9-8706-c16a0608d402.png" alt="alt text" width="416" height="250"> <img src="https://user-images.githubusercontent.com/40466329/51793967-f9ce6000-21c0-11e9-81ef-1df8c6a1a0d1.gif" alt="alt text" width="416" height="125"> 
Above we have some examples of EEG data receieved by the Android device. We can see that the 4th electrode still needs to be completely adjusted to the user's head to give us cleaner data. On the right we can see how blinking affects the signal received. After the signal quality is acceptable, the user can play some mini-games:
- **Cursor**: Train to move the ball on the screen upwards, downwards or keep it in the baseline according to your own choice. Use the buttons on the right to set the training goal and get a visual reward when you reach said goal.
- **Space Portals**: Move a starship and align it with incoming rings to get the highest score possible
- **Heading**: Control a simulated aircraft navigation panel in order to adjust the heading of the plane with your own brain waves.

<img src="https://user-images.githubusercontent.com/40466329/51794147-626b0c00-21c4-11e9-8feb-3c5500efb203.png" alt="alt text" width="416" height="250"> <img src="https://user-images.githubusercontent.com/40466329/51794175-fb018c00-21c4-11e9-9cfc-10055ceefd69.gif" alt="alt text" width="416" height="125"> 
(Example of the mindX gameplay with Cursor)

It is possible (and necessary) to fine-tune some game-related parameters for the best gaming experience, namely the limits of the fixed-decoder and the level of control (higher attractor force, less control) and checking the headset connection. To do so, we have the settings menu.

<img src="https://user-images.githubusercontent.com/40466329/51794258-7a438f80-21c6-11e9-85d5-de29a03dcc3f.jpg" alt="alt text" width="416" height="250">

The app was created with Android Studio and the languages used for coding were Java, Processing and XML.
