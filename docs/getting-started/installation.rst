Installation
============
The *FE Tracking* App is available for Android 7.0 and later and IOS 10.0 and later.

.. list-table::

    * - .. image:: ../_static/images/getting-started/Tracking-Android.png
           :scale: 50%
           :target: https://play.google.com/store/apps/details?id=nl.fe_data.tracking
      - .. image:: ../_static/images/getting-started/Tracking-IOS.png
           :scale: 50%
           :target: https://apps.apple.com/app/fe-tracking/id1574304676

Battery optimization
--------------------
Unfortunately, some **Android device manufacturers** have made it a "sport" to optimize battery usage in such a way that Apps running in the
background (such as *FE Tracking* when it is recording) are forcefully shut down.
Alarm Apps, Health Apps and Location Apps are then the victims of this policy, while the standard Android version usually handles this well.
Also if battery optimisation Apps are used (Android and IOS) it can have a negative impact on *FE Tracking*. If such Apps are used make sure that *FE Tracking* is excluded from optimization, if possible.

If this happens to you, remember this is not an App problem, but it is a Device manufacturer problem.

Check `this site <https://dontkillmyapp.com>`_ to find out if your phone uses device-specific optimisations.
The general rule is to exclude the *FE Tracking* App from battery optimisation rules, if possible. Often these settings are deeply "hidden" in the phone's settings.

Further optimizations
---------------------
*FE Tracking* is very battery-conscious. When track recording is enabled it will automatically start recording a location according to the configured distanceFilter (meters).
When the device is detected to be stationary, *FE Tracking* will automatically turn off location-services to conserve energy.

Nevertheless, further optimisations are certainly possible in order to use the battery as efficiently as possible.

#. As mentioned earlier, make sure *FE Tracking* is excluded from battery optimisations.
#. Do not run other Apps in the background. Make sure *FE Tracking* is the only App running in the background.
#. Avoid using social media Apps and streaming Apps. They are known as notorious battery abusers.
   Search on the Internet for ``social media App battery usage`` and you will find good suggestions.
#. If you pause for more than 5 minutes while walking, cycling, ... temporarily turn track recording off and turn it on again when you continue.
#. The amount of data that *FE Tracking* uses for checkpoints and optional news and route updates is very limited and in most situations is
   not more than a few 10-kilobytes. For very long routes it might be a few megabytes.
   This data will almost always be sent via the mobile data network.
   Check your mobile operator's coverage map to see which type of network (``3G, 4G or 5G``) has the best coverage.
   Most phones constantly scan all networks for the best possible coverage, which of course drains battery power.
   By locking the phone to one type of network (where coverage is good for the entire route) in the phone's settings, you can prevent this scanning.
#. If you are walking, cycling, ... with a group of colleagues or friends, it is also possible to create a personal WiFi hotspot on one of the devices.
   Turn off mobile data on all other devices and connect to the hotspot via WiFI. These devices will save quite a bit on battery power.
#. Of course, you can also buy a small power bank and connect it to your phone. This way you will always have enough power available.
   Especially for long tracks or tracks that take all day, this is highly recommended.
#. While recording the route, you can use the App to check where you are on the route and see how far you are from the next checkpoint, first aid post, etc...
   At that moment, map data will be downloaded, which of course happens via the mobile data network and will drain the battery and possibly your mobile data bundle.
   The App uses a map cache, so once a map segment has been downloaded, the next time it is used, the segment is retrieved from the cache. This saves time and money.
   So if you are at home and have a WiFi connection, you can already explore the route and scroll through it with different zoom levels to fill the map cache.
   A great time and cost saver for your mobile data bundle and your battery.

Languages
---------
*FE Tracking* supports standard two languages: English and Dutch. You can add your own language by following the next steps:

#. Make sure you have a `Github <https://github.com>`_ account.
#. Check the ``languages`` folder of `https://github.com/fe-data/fe-tracking-languages <https://github.com/fe-data/fe-tracking-languages>`_ if your language is supported.
#. If not, login with the Github account at `https://gitlocalize.com/repo/6402 <https://gitlocalize.com/repo/6402>`_.
#. Create a new issue in `https://github.com/fe-data/fe-tracking-languages/issues <https://github.com/fe-data/fe-tracking-languages/issues>`_ requesting the new language code.
   We will give you the role of moderator for the new language. Use the two letter codes from `this source <http://www.loc.gov/standards/iso639-2/php/code_list.php>`_. Only LTR-languages are supported.

As moderator you may receive review requests from other translators. Process them and when you are happy with the update create a pull request. Mind you:

#. We will only process pull request which origin from Gitlocalize and no pull requests from private forks.
#. For initial translations we only accept a full translation of the whole file. Partial translations will be rejected.
#. Once we have processed the pull request, the translation will be available for the App within 15 minutes if you re-install the App.
   If you don't re-install the App it may take up to 12 hours before the App is aware of the new language.
#. There is only 1 moderator per language.