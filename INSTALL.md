INSTALLATION
============

Prequisites
-----------

B-Label requires the following packages:

* Perl
* Perl GTK Bindings (libgtk2-perl)
* Perl GladeXML (libgtk2-gladexml-perl)
* Perl GD2 (libgd-gd2-perl)

Note that you need atleast Ubuntu 9.10 (Karmic Koala) or Debian 6.0 (Squeeze, currently testing) for this program. The earlier versions of Pango lack some of the features this program uses.

For distribution specific package installation, see the distribution specific section at the end of this document.

Printer Settings
----------------

You need to put your printer into "extended" mode. There's a switch on the back of the printer which needs to be set to "E". Connect the printer to your computer and turn it on.

CUPS Setup
----------

You need to setup your Brother Printer within CUPS. You don't need to worry about a specific driver; just pick "Generic text-only printer".

Installation complete
---------------------

Now you can run b-label and print labels using the software.





DISTRIBUTION-SPECIFIC PACKAGE INSTALLATION
==========================================

Gentoo
------

If you are a gentoo user, you can install the required packages by using:

emerge dev-perl/gtk2-perl dev-perl/gtk2-gladexml dev-perl/GD

That should pull in all builds required to run B-Label.

