# airship-issue-clear-top
Airship issue with in-app banners and launching activies clear-top

When you recieve an airship in-app banner message, if you send an intent to launch the currrent activity with the flags: `Intent.FLAG_ACTIVITY_NEW_TASK | Intent.FLAG_ACTIVITY_CLEAR_TOP | Intent.FLAG_ACTIVITY_SINGLE_TOP`,
you will get duplicate banners. 
