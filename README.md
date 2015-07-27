Project Hekate
============
Project Hekate is an open source, DIY home automation project that is comprised of an android app and software running on a Raspberry Pi.

* TODO: Fill out a more beautiful descriptions

Prerequisites (User)
============
* Rasberry Pi (preferably B+ or later)<br/>
* Android 5.0 (or later)

* TODO: Be more specific about software and versions required

Setup (User)
============
1. Set up firebase account, database, and users.
  * (If this could be replaced that would be best)
2. Install the Android app and login with the user that was set up on the firebase account.
3. Install node on the Rasberry Pi.
4. Hook up the desired devices to the GPIO pins on the Pi.
  * (Tested with LED lights for now)
5. Run the login script on the Pi, use the token to observe the changes in the firebase database.

* TODO: Fill out each of the steps in more detail

Prerequisites (Developer)
============
* Android Studio (v???)
* Android 5.0 device in developer mode
* Raspberry Pi (B+ model or later)

* TODO: Be more specific about software and versions required

Setup (Developer)
============
1. Install Android Studio and get the project imported.
2. Install node on the Rasberry Pi.
3. Download the scripts for the Pi from the repo.
  * We found it easier to develop the script on a separate computer then just pull the repo on the Pi to test.
