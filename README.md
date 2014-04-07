Memmber Management
================================================================================

This module adds some database-related tricks
to your silverstripe application. It
* creates a group for all members who are "ghost"
members, because they do not belong to any group


Developer
-----------------------------------------------
Nicolaas Francken [at] sunnysideup.co.nz

Requirements
-----------------------------------------------
SilverStripe 2.4.0 or greater.

Documentation
-----------------------------------------------
see:
 http://silverstripe-webdevelopment.com/membermanagement (not completed YET!)

Installation Instructions
-----------------------------------------------
1. Find out how to add modules to SS and add module as per usual.
2. copy configurations from this module's _config.php file
into mysite/_config.php file and edit settings as required.
NB. the idea is not to edit the module at all, but instead customise
it from your mysite folder, so that you can upgrade the module without redoing the settings.
3. run a dev/build/?flush=1 to action

