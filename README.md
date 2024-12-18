# Google-Form-Bot-for-Radio-Input-Form-and-Submit-

This is a py script that runs on a venv enviroment 

1. Download ChromeDriver and set up the path correctly in the script:

 
 #Path to ChromeDriver
CHROMEDRIVER_PATH = r"# Adjust path as needed"  
 
FORM_URL = "# Replace with your form URL"  


Go to the official ChromeDriver download page:
https://googlechromelabs.github.io/chrome-for-testing/
Select the version that matches your Chrome browser version.
You can check your Chrome version by typing chrome://settings/help in the Chrome address bar.
Download the appropriate win64 version for Windows.


2.Install Anaconda prompt and Start a virtual env And install the selenium inside the env 

3. Install selenium in the conda terminal with the env initiated 
   * install selenium

4. cd to your python directory where the script is located

5. when cd to the correct path from the conda terminal to your project and the env active and selenium installed run :python main.py

6. the script should automatically open the googledrivetest page and run your form link and fill the radio inputs randomly 

