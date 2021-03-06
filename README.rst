========================================
Openslides Presentation View
========================================

Overview
========
This plugin adds a new page to OpenSlides that can be used as a 'presenter'
view, adding control that users are likely used to from other presentation
software such as Powerpoint to OpenSlides. This page listens to mouse (not yet)
and keyboard events to change the currently shown slide.

The main use for this plugin is to provide a simple overview for presenters
to use OpenSlides, either with a mouse (soon!), keyboard or presentation remote
(which are sometimes called a 'clicker', hence the name).

Requirements
============
 - OpenSlides 2 (version 2.1 or higher)

Install
=======
I. Installation on Windows (with OpenSlides portable version)
-------------------------------------------------------------

1. Get the latest openslides-presenter plugin release from:

   https://github.com/lesteenman/openslides-presenter

2. Move the plugin directory (openslides_clicker, instead of the main
   folder/repository) to:

    '<path-to-openslides-portable>/openslides/plugins/'

3. Start openslides.exe.

II. Installation on GNU/Linux and MacOSX
----------------------------------------
1. Setup and activate a virtual environment::

    $ virtualenv .virtualenv

    $ source .virtualenv/bin/activate

2. Install OpenSlides and the openslides-presenter plugin using pip::

    $ pip install openslides git+https://github.com/lesteenman/openslides-presenter

    OpenSlides and all required python packages will be installed.

Using the plugin
================

After the plugin is installed, simply open the 'presenter' page through the menu.
Note that this only does something useful (i.e. allow controlling
the projector) if a presentable and controllable media is currently shown.

License and Author
==================
This plugin is Free/Libre Open Source Software and distributed under the
MIT License, see LICENSE file. The plugin was made by Erik Steenman
(https://github.com/lesteenman).


Contributors
============
* lesteenman (https://github.com/lesteenman)
* FinnStutzenstein (https://github.com/FinnStutzenstein)
* i3anaan (https://github.com/i3anaan)
* serge1peshcoff (https://github.com/serge1peshcoff)

Changelog
=========
Version 2.0.2 (2018-04-18)
--------------------------
* Include a preview of the current slide on the presenter page
* Add support for OpenSlides versions higher than 2.1

Version 2.0.1 (2017-05-16)
--------------------------
* Add support for OpenSlides 2.1

Version 1.1.0 (2016-05-14)
--------------------------
* First release of this plugin for OpenSlides 2.0.x

Version 1.0.0 (2016-02-26)
--------------------------
* First release of this plugin for OpenSlides 1.7.x.
