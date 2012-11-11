steam-overlay
=============

Gentoo overlay for Valve's Steam client and Steam-based games

Using the overlay
-----------------

To use this overlay follow the instructions at http://samuelololol.blogspot.de/2010/10/layman-with-custom-git-repo-ie-github.html .
You can use the steam-overlay.xml for convenience.

Troubleshooting Steam
---------------------

If you have problems, please take a look at http://wiki.gentoo.org/wiki/Steam and https://forums.gentoo.org/viewtopic-t-930354-postdays-0-postorder-asc-start-75.html .

The correspondig bugzilla entry is here: https://bugs.gentoo.org/show_bug.cgi?id=442176

Contribute to this overlay
--------------------------

If you want to suggest changes, like new dependencies or game-related stuff, please send a github pull request with explanation/proof why this is necessary, so we can discuss it. Determine correct behavior and dependencies can be tricky, therefore we'd like to discuss and wait for confirmation of others before adding modifications or new ebuilds.

Branches
--------

* master: current stable versions, should equal the one in http://dev.gentoo.org/~mrpouet/pub/gamerlay/main_page.xml
* testing: testing new modifications
* meta-pkgs: split installer ebuild in installer-only ebuild and meta ebuild for client dependencies
