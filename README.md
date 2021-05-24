
# JENNER-Real time fast updates for COVID-19 vaccine slot availability.

### For user interface snapshots, scroll down.
This application searches the COWIN database for available COVID-19 vaccine slots and notifies the user whenever slots are available based on certain criteria.
The project is written in java. You can run this application locally on your computer and get real time updates which are verified to be faster than notifications through third party messaging apps. 
#### Since this application runs on your computer and provides the results directly to you it is much faster than bulk notifications through messages and email.  Faster notifications improve your chances of booking a slot.

## Tips
1) To improve your chances of booking a slot, searching only one district for a single day is recommended. This will reduce latency and give you faster notifications. You may also search multiple districts for multiple dates if you wish.


## To download and run this project
### Automatic Install (On Windows)
1) Download this application from this website to your computer by selecting the "Code" dropdown on the project page. You may also download just the file JENNER_for_Windows.exe for this installation.
2) You can choose Download zip.
3) Extract the zip file
4) Double click on JENNER_for_Windows.exe
5) The application will ask to install on your computer.
6) Your antivirus or Windows Defender may try to block this application from installing. Kindly give the necessary permissions.
7) Once installed search for "JENNER_for_Windows" in start menu to invoke the application.
8) You can uninstall the application at any time through Control Panel. 
### Manual Install
#### Project Dependancies
1) JAVA 1.8 or higher must be installed on your system. 
To install Java visit https://java.com/en/download/help/download_options.html. To check whether Java is installed on your system type the command "java -version" in the command line and check the output. If Java is installed then you should see the version.
2) Curl must be installed on your system. Curl for Windows is also available with the project and can be installed by going to the following file and executing it.
  curl-7.76.1-win64-mingw -> bin -> curl.exe. The folder curl-7.76.1-win64-mingw will be available when you download this projeect
3) To install Curl for other operating systems it can be downloaded from https://curl.se/
4) To check whether you have curl installed on your system open a command line and type "curl -V" and check the output. If curl is installed then you should see the version of curl. Otherwise you will see an error message that the command is not recognized.
5) Download this application from this website to your computer by selecting the "Code" dropdown on the project page. 
6) You can choose Download zip.
7) Extract the zip file
8) To run the project from the command line, go to the extracted folder and type java -jar "JENNER.jar" .You may also double click on JENNER.jar to launch the application.

## Alert Mechanisms
This software will provide audio alerts on your computer once slots are open which match your criteria. It needs to run continuously on your computer/laptop. Make sure to turn on the volume of your computer/laptop.

## Warnings
1) Do not run multiple instances of this application on your computer. This may exceed the limit of API calls/min provided by COWIN. If your IP address gets blocked, then you will not recieve updates and the application will throw an error. If your IP gets blocked wait for 5 mins and restart the application.
2) Also do not run multiple instances of this application on two separate computers connected to single internet router. This will also cause the same problem mentioned in the above point.

## Snapshots

![Capture](https://user-images.githubusercontent.com/72568856/119268024-9e84cf00-bc0e-11eb-9452-45ec02ebb084.PNG)
![Capture2](https://user-images.githubusercontent.com/72568856/119273685-a00fc080-bc29-11eb-8480-a26607cbc89d.PNG)

## Bugs/Issues
To report any bug or issue kindly raise the issue in github.
You may also send mails to abhisekdash35@gmail.com with error description and screenshots (if possible)
