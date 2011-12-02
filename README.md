nightglow theme for awesome
===========================

Developed by Richard Moe <rm@stuffandjunk.org> based of the solarized theme developed by Gwenhael Le Moine <gwenhael.le.moine@gmail.com> 
and on the work of Ethan Schoonover <es@ethanschoonover.com>

Installation
------------
(This assume you're using the default configuration directory)

    $ cd ~/.config/awesome
    $ mkdir -p themes
    $ cd themes
    $ git clone git://github.com/drahcir2/nightglow

Then edit your rc.lua

    $ $EDITOR ~/.config/awesome/rc.lua

to have the line starting with `beautiful.init` look like this:

    beautiful.init( awful.util.getdir("config") .. "/themes/nightglow/theme.lua" )

