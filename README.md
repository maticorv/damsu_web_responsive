==============
DAMSU Web Responsive
==============


<!-- .. |badge1| image:: https://img.shields.io/badge/maturity-Production%2FStable-green.png
    :target: https://odoo-community.org/page/development-status
    :alt: Production/Stable
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fweb-lightgray.png?logo=github
    :target: https://github.com/OCA/web/tree/14.0/web_responsive
    :alt: OCA/web
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/web-14-0/web-14-0-web_responsive
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/162/14.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5|  -->

This module adds responsiveness to web backend.

Features for all devices:

* New navigation with an app drawer

  .. image:: https://user-images.githubusercontent.com/973709/48417193-09a1e080-e74a-11e8-8a0c-e73eb689b2fb.gif

* Quick menu search from the app drawer

  .. image:: https://user-images.githubusercontent.com/973709/48417213-17576600-e74a-11e8-846a-57691e82636b.gif

Features for mobile:

* App-specific submenus are shown on full screen when toggling them from the
  "hamburger" menu

  .. image:: https://user-images.githubusercontent.com/973709/48417297-51286c80-e74a-11e8-9a47-22c810b18c43.gif

* View type picker dropdown displays confortably

  .. image:: https://user-images.githubusercontent.com/973709/50964322-e3d55580-14c6-11e9-8249-48db9539600f.gif

* Top app bar is always visible, but the control panel is hidden when
  scrolling down, to save some vaulable vertical space

  .. image:: https://user-images.githubusercontent.com/973709/50964496-5cd4ad00-14c7-11e9-9261-fd223a329d02.gif

* Form status bar action and status buttons are collapsed in dropdowns.
  Other control panel buttons use icons to save space.

  .. image:: https://user-images.githubusercontent.com/973709/50965446-e08f9900-14c9-11e9-92d6-dda472cb6557.gif

* Breadcrumbs navigation is collapsed with a "back arrow" button.

  .. image:: https://user-images.githubusercontent.com/973709/50965168-1d0ec500-14c9-11e9-82a0-dfee82ed0861.gif

* Search panel is hidden on small screens.

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/search_panel.gif

Features for computers:

* Keyboard shortcuts for easier navigation, **using ``Alt + Shift + [key]``**
  combination instead of just ``Alt + [key]``.
  See https://github.com/odoo/odoo/issues/30068 to understand why.

  .. image:: https://user-images.githubusercontent.com/973709/48417578-ff341680-e74a-11e8-8881-017709e912bc.png


* Autofocus on search menu box when opening the drawer

  .. image:: https://user-images.githubusercontent.com/973709/48417213-17576600-e74a-11e8-846a-57691e82636b.gif

* Set chatter on the side of the screen, optional per user

  .. image:: https://user-images.githubusercontent.com/973709/48417270-41108d00-e74a-11e8-9172-cba825d027ed.gif

* Full width form sheets

  .. image:: https://user-images.githubusercontent.com/973709/48417428-ac5a5f00-e74a-11e8-8839-5bc538c54c1d.png

* Sticky chatter topbar

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/chatter_topbar.gif

* AppMenu waits for action finished to show the view

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/appmenu.gif

* Sticky header & footer in list view

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/listview.gif

* Sticky statusbar in form view

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/formview.gif

* Followers and send button is displayed on mobile. Avatar is hidden.

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/chatter.gif

* When the chatter is configured on the side part, the document viewer fills that
  part for side-by-side reading instead of full screen. You can still put it on full
  width preview clicking on the new maximize button.

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/document_viewer.gif

* Bigger checkboxes in list view

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/big_checkboxes.gif

* Scrollable dropdowns

  .. image:: https://raw.githubusercontent.com/OCA/web/14.0/web_responsive/static/img/dropdown_scroll.gif

**Table of contents**

.. contents::
   :local:

Usage
=====

The following keyboard shortcuts are implemented:

* Navigate app search results - Arrow keys
* Choose app result - ``Enter``
* ``Esc`` to close app drawer

Known issues / Roadmap
======================

* To view the full experience in a device, the page must be loaded with the
  device screen size. This means that, if you change the size of your browser,
  you should reload the web client to get the full experience for that
  new size. This is Odoo's own limitation.
* App navigation with keyboard.
* Handle long titles on forms in a better way
* Standard sticky headers seems to not work properly on iOS Safari/Chrome (see #1626).
