Overview
========

First time use
--------------
.. panels::
   :container: container-lg
   :column: col-lg-6 col-md-12 col-sm-12

   The first time the FE Tracking App is launched, a warning is shown that the App uses location data to determine where
   the phone is in order to check whether a checkpoint has been passed. When using different parts of the App,
   you will be asked for permission to use e.g. the camera or location data.
   ---
   .. figure:: ../_static/images/getting-started/Tracking-first-time.png
      :target: ../_static/images/getting-started/Tracking-first-time.png
      :alt: Running App for the first time

      Warning screen

----

Permissions
-----------
Permissions are required to use certain parts of the App. Permission is only asked for when the respective component is used.

Camera
  If a ticket is scanned with the camera to add a track to the tracks overview, it is necessary to give permission to the App to use the camera when the App is in use.

Location
  As soon as a map of the track is shown or live recording is turned on, permission is needed for the App to use location data.
  This is done in two steps. First, permission must be given to use location data when the App is in use and, as a final step,
  permission must be given to use it all the time. This is show as ``Always`` (IOS) or ``Allow all the time`` (Android).
  So even when the App is closed or running in the background, location data will be used.

Motion & Fitness / Physical activity
  This permission is requested at the same time as the location permission. The App samples the accelerometer periodically
  while tracking in order to power-down the GPS as soon as the device is determined to be stationary, while stopped for a break, for example.

Files and media
  If a track is added to the tracks overview by scanning a PDF containing the etickets, permission is required.

Background App Refresh (IOS only)
  This permission is requested at the same time as the location permission.
  This is necessary in order for the App to continue to operate in the background.

----

Permission overview
-------------------
.. panels::
   :container: container-lg
   :column: col-lg-6 col-md-12 col-sm-12

   .. figure:: ../_static/images/getting-started/Tracking-permissions-ios.png
      :target: ../_static/images/getting-started/Tracking-permissions-ios.png
      :alt: Overview IOS permissions

      Overview IOS permissions
   ---
   .. figure:: ../_static/images/getting-started/Tracking-permissions-android.png
      :target: ../_static/images/getting-started/Tracking-permissions-android.png
      :alt: Overview IOS permissions

      Overview Android permissions

|

.. warning:: Periodically, both IOS and Android will show reminders that the App can always request location data and if the App is not used for a long time, this permission will be withdrawn.
   So if the App has not been used for a long time and it is restarted again, make sure that the location permission is set to ``Always`` for IOS or ``Allow all the time`` for Android.
