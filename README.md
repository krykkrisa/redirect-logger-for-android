# redirect-logger-for-android
this script logs all redirections on a connected thru a cable to the pc and logs them in the terminal and the chosen folder this program helps find and exterminate adware and other kinds of malware !NOTICE! you NEED to have androi'ds SDK platform tools installed on the pc and the terminal has to come from the extraced folder
# TUTORIAL 
### **1** 
Android SDK Platform-Tools is a component for the Android SDK. It includes tools that interface with the Android platform, primarily adb and fastboot. Although adb is required for Android app development, app developers will normally just use the copy Studio installs. This download is useful if you want to use adb directly from the command-line and don't have Studio installed. (If you do have Studio installed, you might want to just use the copy it installed because Studio will automatically update it.) fastboot is needed if you want to unlock your device bootloader and flash it with a new system image. This package used to contain systrace, but that has been obsoleted in favor of Studio Profiler, gpuinspector.dev, or Perfetto.
first visit [the official android developer website](https://developer.android.com/tools/releases/platform-tools)
scroll down and you'll see download versions for windows mac and linux (i will be using windows)
<img width="2547" height="1326" alt="Screenshot 2026-07-18 203512" src="https://github.com/user-attachments/assets/9953bc4b-3d57-47f3-8246-ba45ec3b0027" />
attachments/assets/744ace58-e360-48b0-b894-65b77d54f720" /> 
### **2** 
after downloading Platform Tools extract the zip file into a seperate folder
<img width="2191" height="1095" alt="lala 1 (1)" src="https://github.com/user-attachments/assets/20c3aa0d-895b-4b94-a5f1-95debe9cbd73" />
<img width="2005" height="931" alt="Screenshot 2026-07-18 212646" src="https://github.com/user-attachments/assets/de03218e-436d-4235-b025-6f4216dbe850" />
### **3** 
after extracting the app type powershell in the directory bar
<img width="2187" height="1102" alt="lala 1 (3)" src="https://github.com/user-attachments/assets/9e4f7599-d86a-4f51-b067-45e962df45da" />

### **4** after this make sure your phone is connected to your pc by typing in
```
>./adb devices
```
 ### **5**
 if the random string of numbers has device next to it that means your phone is connected and is ready for the command 
 *(if not make sure the cable is connected, that you have USB debugging turned on in developer options on your android phone,
 and that you clicked allow when the RSA popup on your phone appeared)*
 after making sure your pc is authorized by the phone we can execute the following command with your directory to the text file
 ``` 
 python "YOUR_directory_to_the_redirect_logger"
 ```
the program should say >Watching for redirects... writing to {LOG_FILE} 
if it does then congratulations you have successfully installed and activate my script and now you just have to wait for the adware to redirect you to a website for you to catch the app name 
once a redirect happens the script will log the app name that initiated the redirect
<img width="1121" height="225" alt="Screenshot 2026-07-18 211309" src="https://github.com/user-attachments/assets/73a07ee7-8f76-487c-b058-975e494a7c85" />
(this is how i caught adware on my phone <3)
