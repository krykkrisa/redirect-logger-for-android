# redirect-logger-for-android
this script logs all redirections on a connected thru a cable to the pc and logs them in the terminal and the chosen folder this program helps find and exterminate adware and other kinds of malware !NOTICE! you NEED to have androi'ds SDK platform tools installed on the pc and the terminal has to come from the extraced folder
# TUTORIAL 
### **1** 
Android SDK Platform-Tools is a component for the Android SDK. It includes tools that interface with the Android platform, primarily adb and fastboot. Although adb is required for Android app development, app developers will normally just use the copy Studio installs. This download is useful if you want to use adb directly from the command-line and don't have Studio installed. (If you do have Studio installed, you might want to just use the copy it installed because Studio will automatically update it.) fastboot is needed if you want to unlock your device bootloader and flash it with a new system image. This package used to contain systrace, but that has been obsoleted in favor of Studio Profiler, gpuinspector.dev, or Perfetto.
first visit [the official android developer website](https://developer.android.com/tools/releases/platform-tools)
scroll down and you'll see download versions for windows mac and linux (i will be using windows)
<img width="2547" height="1326" alt="image" src="https://github.com/user-attachments/assets/744ace58-e360-48b0-b894-65b77d54f720" /> 
### **2** 
after downloading Platform Tools extract the zip file into a seperate folder
<img width="2005" height="931" alt="image" src="https://github.com/user-attachments/assets/7b26591b-ce0d-46a4-b996-e0d58c299a2c" />
### **3** 
after extracting the app type powershell in the directory bar
<img width="1995" height="1063" alt="image" src="https://github.com/user-attachments/assets/e2c5bc83-3c48-4c64-b1d3-e0a161ed1edb" />
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
<img width="1121" height="225" alt="image" src="https://github.com/user-attachments/assets/f85be750-c005-4659-bee8-06a1a41ce9f6" /> 
(this is how i caught adware on my phone <3)
