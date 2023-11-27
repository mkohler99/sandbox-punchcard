# sandbox-punchcard
Instructions for operating the Sandbox Punchcard Project

# Hello Sandbox
Happy holidays; If you're reading this you are one of the lucky few to receive a Sandbox Digital Punchcard! Your Sandbox Digital Punchcard will help immerse you in the exciting world of UTF-8 encoding, one of the many innovations that makes the modern internet possible; as well as Punched Cards, one of the many innovations that preceded the invention of the digital computer! This seamless blend of past and present allows us to paradoxically experience what it might've been like to encode modern day messages onto a physical card used to program a loom or other early computer system. This is some documentation for how to use your very own Sandbox Digital Punchcard.

More information about UTF-8 can be found [here.](https://en.wikipedia.org/wiki/UTF-8)

<img width="600" alt="Screenshot 2023-11-26 at 10 21 36 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/36a735e2-4cb9-46b3-a671-0a08429e5c72">




# How to Connect
When the device boots, it attempts to connect to its last known wifi network. In most cases, when you first power up your board, it will not connect automatically. In this case, the board will create its own hotspot with the SSID **HELLO-SANDBOX** 

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/c7bd34d3-6f11-4f0e-8fcc-0bd07a2ab6e8" width="300">

Once you've connected to the board's wifi hotspot, you should be directed to the wifi manager page. This page will allow you to enter your wifi information, or scan for networks and interactively join them.

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/339a90ec-ba78-4b85-8ca6-3f622f2fd50c" width="300">


Next, Choose whatever network you want to connect to out of the list

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/11c18404-8079-48d0-a3a5-5da6bb4bc8eb" width="300">

Then enter the password for the network you've chosen.

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/b428a58b-c331-434a-b059-688aa0ae4c37" width="300">


After this, the device will reboot and attempt to connect to that network. If it ever fails to join that network on first boot, the device will once again broadcast its own internal hotspot to prevent the device from being locked to a non-existant wifi network. You can now reconnect your device to the Wifi network that the device has now rejoined.

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/08da4baa-c4a8-4f8e-a559-3400b0f99f7a" width="300">

To find the device on your network, you have a few options. Firstly, you can check the device list in your router's user interface for the IP of the Sandbox device within your local network. Alternatively, the device should advertise itself with mDNS as **sandbox.local** so in theory, just enter that in your address bar and it should take you straight to the GUI.

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/08e141cf-2b08-485f-b421-87072c07159d" width="300">

# Sandbox Digital Punch Card Operation
Use the input boxes at the top of the UI to enter a word to translate into UTF-8. 

<img width="300" alt="Screenshot 2023-11-26 at 9 14 20 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/54727a67-3180-46ea-b29b-cfaa6643eb75">

For instance, if you enter the character "H" into the first box....

<img src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/4348185a-63d3-41d1-b893-4758c826b6b9" width="300">

The device will display the UTF-8 Representation of "H" on the first column of its display, which in this case is "01001000"

<img width="400" alt="Screenshot 2023-11-26 at 10 11 41 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/7f2e7988-3242-4678-8490-9ccf9c6cc710">

Use the Brightness and Color controls to modify the Brightness and Color of the LEDs. The brightness ranges from 'barely visible' to 'retina searing' 

<img width="300" alt="Screenshot 2023-11-26 at 9 14 29 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/daf14b43-418f-49b4-851c-bc5a6e27bd87">

For instance, you can make the LED's blue like 90's stereo equipment. 

<img width="400" alt="Screenshot 2023-11-26 at 10 11 56 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/5a5f1fa2-2484-428f-bfcc-54efe895598a">

Finally, you can use the 'Save Defaults' button to save the currently displayed message, brightness, and color such that the next time the device boots up, it restores those parameters from the device's onboard flash storage.

<img width="300" alt="Screenshot 2023-11-26 at 9 14 35 PM" src="https://github.com/mkohler99/sandbox-punchcard/assets/7109569/dbd1dfbe-4b2b-402f-aaef-b0fc28116aa6">





# Miscellaneous Safety Warnings
* Warning: Quantum Temporal Flux Instabilities

Avoid exposing The Device to moisture, as water can interact with electronic components, leading to unpredictable time-travel-like distortions. Keep The Device dry to prevent inadvertent journeys to historical epochs or dystopian futures. Always maintain temporal sanity when using The Device.
* Notice: Electro-Chrono Compatibility Quandaries

Limit The Device to USB Type-C ports within the recommended voltage specifications. Excessive electrical input may cause electro-chrono compatibility quandaries, leading to temporal anomalies. The Device should never be permitted to draw more than 2.5 Amps at 5 volts, despite what The Device may tell you.
* Caution: Avoid Quantum Wifi Entanglement Paradoxes

Always approach reprogramming The Device with precision to avoid quantum entanglement paradoxes. Incorrect WiFi configuration parameters may trap The Device in alternative realities, creating interdimensional situations or worse, support phone calls. Exercise care to prevent unintended user input and consult this manual for accurate WiFi configuration advice.
* DANGER of Temporal Photonic Dilation

Prolonged usage of The Device may induce temporal photonic dilation, altering the perception of time. Take regular breaks, avoid excessive time-travel, and do not stare directly into the aperture of The Device. Additionally, refrain from inserting The Device into actual punch card readers, as this use case is untested and may lead to unexpected outcomes. 

* Thank you for your purchase of this Kohler Industries product. At Kohler Industries, safety is not just a feature; it's our guiding principle. Your trust in us is the cornerstone of our commitment to providing you with a secure and reliable experience.
