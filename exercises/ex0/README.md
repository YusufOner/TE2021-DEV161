# Preparation

Here we start the excercise and see whether everything is ready to go.
Please make sure you have all the necessary prerequsistes listed below. If not, please raise your voice during the meeting so that we can assist you early in the session.


## Prerequisites
Please keep the following links and resources available:

1. You need a browser, preferably Google Chrome
1. Logon to the Development Lobby  
https://lcapteched2021-applicationdevelopment.lcnc.cfapps.eu10.hana.ondemand.com/
1. Your username  
TecEdLCAP001+0XX@gmail.com 
1. Your password follows a similar pattern  
TechEdLCAP0XX@XYZ where XYT are the three letters you got earlier
1. For the mobile preview app you should install  
iOS: https://apps.apple.com/us/app/sap-appgyver-preview/id1585856868  
Android: https://play.google.com/store/apps/details?id=com.sap.appgyver.preview.release  
You can also just search "AppGvyer Preview" in your app store and install it.


## General troubleshooting

1. If you encounter an issue with the Low-Code perspective in the Business Application Studio (BAS) you can check the logs under: File > Open > /home/user/lcap.home.2021-11-17.log (if you encounter the issue at any other day, you need to update the file name with the date of that day)

1. If something does not work in the editor, but it should, you can try restarting the whole workspace. To do so, open this URL: https://lcapteched2021.eu10cf.applicationstudio.cloud.sap/index.html.  
Here you see the so-called Dev Spaces of the Business application studio. Click on the "Stop" button. Once the Dev Space stopped, you can simply restart it. In order to go back to your Low-Code perspective you must go through the lobby - located here:  
https://lcapteched2021-applicationdevelopment.lcnc.cfapps.eu10.hana.ondemand.com/

1. If the "Deploy" process throws an 404 error message (can be seen in the log file mentioned above), you can execute:
```bash 
npm install --global @ui5/cli
```
