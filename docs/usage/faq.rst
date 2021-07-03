FAQ
===

.. dropdown:: The recording icon is greyed out
   :animate: fade-in

   Check in the information screen between which times the track can be recorded. No recordings are possible before or after these times.

.. dropdown:: The finish/exit icon is greyed out
   :animate: fade-in

   Check in the information screen between which times the track can be recorded. The finish/exit icon button can only be clicked in the recording window.

.. dropdown:: Track is not recorded if the screen is switched off
   :animate: fade-in

   Check if all the needed permissions are enabled. See `Permission overview <../getting-started/overview.html#permission-overview>`_.
   Double check if the location permission is set to ``Always`` for IOS or ``Allow all the time`` for Android.

.. dropdown:: How accurate is the distance in the Map screen
   :animate: fade-in

    .. panels::
       :container: container-lg
       :column: col-lg-6 col-md-12 col-sm-12

       .. figure:: ../_static/images/usage/Cut-corner.png
          :alt: Cutting a corner

          Cutting a corner
       ---
       It depends on the length of the route, whether there are many sharp bends in the route and most importantly, the distance filter defined by the event organisation.
       The App is optimized for battery-efficiency. It samples the accelerometer periodically while tracking in order to power-down the GPS as soon as the device is determined to be stationary.
       It uses the distance filter to query for the GPS location. But the filter itself is elastic; the faster you go, the larger the distance filter becomes. And ofcourse the other way around.
       Usually, the organisation sets this filter to at least 10 metres for a walking route and at least 20 metres for bicycles, for example.
       So yes, the distance measured may be slightly shorter than the real distance due to cutting corners.