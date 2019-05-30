
NAME
    RT-Extension-QuickUpdateExtended - Adds an update box to ticket display 
    extended by Comment and Reply Box

DESCRIPTION
    This adds an update box to the ticket display page allowing one to
    quickly change: 
    1. status
    2. owner
    3. priority
    4. queue
    5. Comment
    6. Reply
    instead of needing to browse between tabs in order to do so.

RT VERSION
    Works with all releases of RT 4.

INSTALLATION
    perl Makefile.PL
    make
    make install
        May need root permissions

    Edit your /opt/rt4/etc/RT_SiteConfig.pm
        If you are using RT 4.2 or greater, add this line:

            Plugin('RT::Extension::QuickUpdate');

        For RT 4.0, add this line:

            Set(@Plugins, qw(RT::Extension::QuickUpdate));

        or add RT::Extension::QuickUpdate to your existing @Plugins line.

    Clear your mason cache
            rm -rf /opt/rt4/var/mason_data/obj

    Restart your webserver

AUTHOR
  Torsten Brumm 
  Based on Best Practical Solutions, LLC <modules@bestpractical.com> Extensions

LICENSE AND COPYRIGHT
    This software is Copyright (c) 2010-2016 by Best Practical Solutions

    This is free software, licensed under:

      The GNU General Public License, Version 2, June 1991

