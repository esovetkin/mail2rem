mail2rem script
===============

The script that in conjunction with notmuch and ical2rem programs
automatically finds and converts *.ics calendars to Remind format.

It is assumed that one stores its mails in Maildir format and uses
notmuch for indexing them. The script might me easily extended to be
used with similar mail indexers.

The script should be run regularly, e.g. by crontab. It searches only
through new mails which has not been processed yet.

Installation
------------

You need to have the following programs installed: notmuch, ripmime,
ical2rem, gawk, sed.

For Archlinux use::

  $ yaourt -S mail2rem-git

or follow the guide on `AUR guide <https://wiki.archlinux.org/index.php/Arch_User_Repository#Installing_packages>` to install the package from `AUR <https://aur.archlinux.org/packages/mail2rem-git/>`

For other systems simply copy the script to the directory included in
your PATH, having installed the dependencies beforehand.

For installing dependencies follow instructions in the following
links:
* `ripmime <http://www.pldaniels.com/ripmime/#downloads>`
* `ical2rem <http://jalcorn.net/public/ical2rem.pl>`

