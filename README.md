Wanda The Fish
==============

If you were a heavy user of GNOME 2, then you almost certainly remember the
Wanda-The-Fish applet that you could put on your toolbar and click to get
nuggets of wisdom and encouragement.

And then... GNOME 3.  Not only did it replace everything that was good about
GNOME 2 with stuff that sucked (slowly, and using a lot of memory), but they
deep-sixed our lovable fish as well.

That was the last straw, I moved to XFCE which has an interface reminiscent of
the GNOME 2 glory days... but sadly no Wanda The Fish.

But no more!

With this simple script, Wanda is revived.  Just add a "custom launcher" to your
toolbar, copy ``wanda`` into ``/usr/local/bin``, and enjoy.  You can even add an
image of Wanda herself to the custom launcher to get closer to what we all
remember and love. [1]

Prerequisites
=============

Wanda is written in Python 2 using the Tkinter GUI toolkit. You will need to
make sure that the Tcl/Tk bindings to Python are installed. Below, I show how to
do this for a handful of popular Linux distributions (please do not feel
slighted if I left out Your Favorite Distro (TM)).


Ubuntu
------

```
sudo apt-get install python-tk
```

Fedora/CentOS/Red Hat
---------------------

```
sudo yum install tkinter
```


SUSE/OpenSUSE
-------------

```
sudo zypper install python-tk
```


Gentoo
------

Make sure you have the `tk` USE flag turned on for the Python package.


Others
------

Consult Google.
