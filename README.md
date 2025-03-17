# Motion-Detection-Alarm
This is an IOT based motion detection alarm which have multiple use cases in different scenarios. It generates a remote alert if it is connected to internet via Telegram and It alerts the nearby people with the help of siren.

**Steps prior to coding part:**

Please connect all the wired according to the following Circuit Diagram and then proceed with the coding part:  
 
 ![unnamed](https://github.com/user-attachments/assets/9a1624a7-0a07-44eb-bafb-ff09ca2f4eb7)
**Figure 1: Circuit Diagram for Motion Detection Alarm. **

![unnamed (1)](https://github.com/user-attachments/assets/a8e67056-1fa6-4218-8c19-9e2641c1aad1)
**Figure 2: Architecture of motion detecion alarm **  

![unnamed](https://github.com/user-attachments/assets/a3c69387-4cf2-4fc0-811a-d0c2f605b57e)
**Figure 3: System Off**

![unnamed (1)](https://github.com/user-attachments/assets/f9b0ca2b-ef1b-421b-87b8-5cf8ab6c7481)
**Figure 4: System On**

![unnamed (2)](https://github.com/user-attachments/assets/19794651-76bc-43c2-a737-02fef9949ebb)
**Figure 5: Motion Detected**

![Untitled design](https://github.com/user-attachments/assets/e43a944d-3dc6-4bf0-8a6b-f17e132e8c88)
**Figure 6: Message alert, Incoming Call, Motion detection call log**

**Steps Required to run the Project:**

**STEP 1 : DOWNLOAD ARDUINO IDE**   
	Download and install the Arduino IDE from the official website.

**STEP 2 : INSTALL ESP8266 BOARD PACKAGE**

* Open Arduino IDE.  
* Go to **File \> Preferences**.  
* In the "Additional Board Manager URLs" field, add the following link:  
  1. http://arduino.esp8266.com/stable/package\_esp8266com\_index.json  
* Go to **Tools \> Board \> Boards Manager**.  
* Search for **ESP8266** and install the package.

**STEP 3 : INSTALL TELEGRAM APP**

* Go to the official Telegram website: https://telegram.org/  
* Download and install Telegram for your platform (Windows, macOS, Linux, iOS, or Android)  
* Login to your Telegram Id as used in the prior code.


**STEP 4 : CREATE A TELEGRAM BOT**  
Open your browser and search for the **CallMeBot API**.

* Visit the site: [https://www.callmebot.com/](https://www.callmebot.com/).  
* Navigate to the Telegram section and enable the calling option.  
* Log in using your Telegram ID on the website.

**STEP 5 : ADD LIBRARY DEPENDENCIES**  
Install the following libraries in Arduino IDE:

* **Callmebot ESP8266** by Hafidhh.  
* **UniversalTelegramBot** by Brain Lough.

**STEP 6 : WRITE THE CODE**

* Open a new sketch in Arduino IDE.  
* Use the sample code in `main.ino` and replace placeholders with your Wi-Fi credentials and Telegram User ID.

**STEP 6: UPLOAD THE CODE**

* Connect the NodeMCU to your computer via USB.  
* Install the required drivers from:  
  https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads  
* In Arduino IDE, select the correct board and port:  
  * Board: **NodeMCU 1.0 (ESP-12E Module)**.  
  * Port: The detected COM port (e.g., COM3).  
* Upload the code to the ESP8266.  
