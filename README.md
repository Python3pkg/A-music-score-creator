===================
Music Score Creator
===================

Description
-----------

It is "A music score creator", a program that, starting from a audio recorded or loaded, will generate the sheet music for that sounds. It's limited to a single instrument-voice and still as development.

Installation
------------
You'll need to install the following packages:

python-wxgtk2.8
python-pyaudio
python-numpy
python-matplotlib
python-scipy
python-pygame
lilypond

In Debian systems, you can install it like this:

sudo apt-get install python-wxgtk2.8 python-pyaudio python-numpy python-matplotlib python-scipy lilypond python-pygame

To Do
-----

For now, it's limited to a single voice. And the results can vary depending on the time when you start recording. Since the audio is divided into pieces and for now is sensitive to when you start recording. In future versions I will try to fix it by adding a preprocessing. So, the missing features, for now, are:

- Add Windows/Mac support.
- Add possibility of change the instrument.

How it looks
------------
.. image:: http://i.imgur.com/oXB194n.png

Example of use
--------------

If you want to see a working example, in this link_ you have a video.

.. _link: https://www.youtube.com/watch?v=O8YsIVSQ1JU

Changelog 0.9.1
---------------

- Added method to change the minimum note duration.
- Fixed some typos. 

Contact
-------

You can contact me on Twitter: @Montagon
