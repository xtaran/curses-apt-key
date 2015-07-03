curses-apt-key
==============

curses-apt-key is a (still very hackish) text-mode interface to
Debian's APT key management tool apt-key.

It is written from scratch in Perl and basically a text-mode clone of
[Joey Schulze's Perl/GTK based gui-apt-key][gak]. It also reuses some
of gui-apt-key's internal Perl modules.

[gak]: http://www.infodrom.org/projects/gui-apt-key/

Dependencies
------------

curses-apt-key depends on:

* libcurses-ui-perl
* gui-apt-key (needs its GAK::Backend)

Download
--------

For now, the most recent code should always be
[available on Github](https://github.com/xtaran/curses-apt-key).

Copyright and License
---------------------

curses-apt-key is Copyright 2012-2015 Axel Beckert <abe@deuxchevaux.org>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

On Debian systems, the complete text of the GNU General Public
License version 2 can be found in /usr/share/common-licenses/GPL-2.
