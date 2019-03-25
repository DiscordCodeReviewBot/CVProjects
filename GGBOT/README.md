Selenium bots, written for educational purposes only!

## GGBOT

  Setup:
  * download ggbot.py and ggbotsmanager.py
  * download chromedriver.exe http://chromedriver.chromium.org/
  * put chromedriver.exe to the same directory as ggbot.py and ggbotsmanager.py
  * edit ggbotsmanager.py:

      * in ggbotsmanager class find __init__ method
      * find self.bots_data list
      * add tuple to list with mail and password as strings ("my_email@domain.com", "my_password")
      * save file
  * shift + right click in folder, choose "open command window here"
  * type "python ggbotsmanager.py"
  * ctrl+c to exit
 
  TODO:
  - [ ] remove known bugs
  - [ ] remove time.sleep() where it's not necessary
  - [ ] change try/except blocks for selenium functions
  
  
  Known bugs:
  
       - exiting program doesn't terminate chromedriver
