Tracks
======

Overview
--------
.. panels::
   :container: container-lg
   :column: col-lg-6 col-md-12 col-sm-12

   .. figure:: ../_static/images/usage/Tracks-overview.png
      :target: ../_static/images/usage/Tracks-overview.png
      :alt: Overview Tracks

      Overview tracks
   ---
   .. raw:: html

      <div style="padding:159.72% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/555701182?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

|

This is the default start screen of the App. It gives an overview of all the tracks that have been or still need to be covered.
Tapping on a track displays a context-menu.

By swiping a track from left to right, or vice versa, a track can be deleted.

Use the :fa:`plus-circle fa-fw fa-lg text-primary` button on the bottom right to add a route.

Context menu
^^^^^^^^^^^^
:fa:`map-o fa-fw fa-lg text-primary`
  Show the Map screen with the track, checkpoints and points of interest. If recording is enabled your travelled track is live updated.

:fa:`pencil fa-fw fa-lg text-primary`
  Change the :doc:`event title <track-change>` in the event overview

:fa:`commenting-o fa-fw fa-lg text-primary`
  Only visible if the event organisation supports real-time message updates.
  It can show a small badge on the top right displaying the number of unread messages.

:fa:`share-alt fa-fw fa-lg text-primary`
  Only visible if the event organisation supports track sharing and if you have enabled `Realtime sharing <../getting-started/settings.html#map-settings>`_ in the ``Settings``.
  After clicking this button you can share the link via email, Signal, WhatsApp, etc with your family, friends, ...

:fa:`qrcode fa-fw fa-lg text-muted` or :fa:`qrcode fa-fw fa-lg text-success` or :fa:`qrcode fa-fw fa-lg text-success opacity-4`
  When all checkpoints are passed **and** uploaded to the event organisation's server, the qrcode will turn green and the :doc:`Finish/exit qrcode <track-finish>` can be shown if the organisation requests it.
  This is only possible within the tracking window. See the :doc:`Information screen <track-information>`.
  Outside the tracking window, the icon is grey or transparent green when all checkpoints have been passed.

:fa:`info-circle fa-fw fa-lg text-primary`
  This icon shows the information screen with emergency numbers, event information, order data and when checkpoints are passed.
  At the top right of the icon is a badge showing the number of checkpoints passed.
  By default, this badge is red, but when all checkpoints are passed, it turns green.

:fa:`play-circle fa-fw fa-lg text-muted` or :fa:`play-circle fa-fw fa-lg text-danger` or :fa:`pause-circle fa-fw fa-lg text-danger`
  The event can only be recorded in the tracking window.
  You can find the tracking window timeslots in the :doc:`Information screen <track-information>`.
  Outside this window the icon is grey. Once recording has started, the icon changes to a pause button.

----

Add tracks
----------
.. panels::
   :container: container-lg
   :column: col-lg-6 col-md-12 col-sm-12

   .. raw:: html

      <div style="padding:159.72% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/555691581?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
   ---
   After a ticket has been purchased from the event organiser and the eticket has been downloaded, the track can easily be added by scanning the PDF file that has been downloaded for a valid eticket.

   If the PDF file contains more than 1 ticket, the App will ask which page is to be scanned. If there is only 1 ticket, this step is skipped.

   If the event offers several tracks with for example different distances, the App offers the possibility to choose a track.
   If there is only one track, this step is skipped.

|

.. warning:: Tickets can be downloaded several times. If this happens on different phones, the one who has downloaded last is the '**owner**' of the ticket.
   All actions to have the ticket scanned or passing a checkpoint uploaded to the event organisation's server will fail for the one who downloaded the ticket earlier.

   If the track supports realtime news and track updates, your ticket will be invalidated immediately as soon it is downloaded on another phone.

   **So be careful not to distribute the ticket but to keep it for yourself.**

   If you want to download the track again, you will have to delete it first.

.. note:: For example, if an event offers several tracks of different distances, they can all be downloaded one by one. However, only one track can be recorded at a time.

----

Recording
---------
.. panels::
   :container: container-lg
   :column: col-lg-6 col-md-12 col-sm-12

   A live recording of a track can only be done during the event. The tracking window can be found in the :doc:`information screen <track-information>`.
   Before and after the event, no recordings can be made. The icon is grey and inactive.

   When a live recording is started, the icon will change to a pause button and the background of the recorded track will turn transparent red,
   so that you can clearly see in the overview which track is being recorded.

   You can pause recording and restart it. For example, if you take a break on your route, it is a good idea to stop recording in order to save the battery.
   ---
   .. raw:: html

      <div style="padding:159.72% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/555769801?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

|

.. warning:: Only one track can be recorded at a time.

----

Track status
------------
If the event supports real-time news and track updates, there is an icon in the top left corner of the route overview that indicates the status.

.. image:: ../_static/images/usage/Connection-icon.png

There is an active connection with the event. As soon there is a news message or track update, it will be processed.
The connection remains active until the tracking window has expired.

.. image:: ../_static/images/usage/Connection-not-icon.png

The connection to the server is not active, usually this is temporary.
Make sure that you have an active data connection via the mobile data network.

.. image:: ../_static/images/usage/Connection-grey-icon.png

The tracking window has expired and it is no longer necessary to connect to the server.

:fa:`times fa-fw fa-lg text-danger`

The ticket has been invalidated. Either it was downloaded on another phone, or it was invalidated by the organisation.
Further actions with the event are not possible. It can only be removed from the overview.

----

Screens
-------
* :doc:`Map <track-map>`
* :doc:`Change <track-change>`
* :doc:`News <track-news>`
* :doc:`Finish <track-finish>`
* :doc:`Information <track-information>`
* :doc:`Record <track-record>`

.. toctree::
   :maxdepth: 1
   :hidden:

   track-map
   track-change
   track-news
   track-finish
   track-information
   track-record
