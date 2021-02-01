Note: the functionality of this module has been _partly_ merged into Backdrop
core since version 1.16.0. This module, in additiona to the core functionality:
- Allows you to customise the submitted by line _per display mode_
- Allows the submitted by pseudo-field to be ordered in each display mode

Submitted By
============

Submitted By enables you to control the format of your content's "Submitted by"
information per content type. It adds fields to your node edit form that let you
enter tokenized patterns for the text you want to display.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Enter tokenized patterns for your node or comment's Submitted By information
  at Administration > Structure > Content Types > [content_type]
  (admin/structure/types/manage/[content_type]).

Translation
-----------

Because Submitted By dynamically builds string, the only way we know to translate them is to use the "String Overrides" in settings.php per language.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-------------------

Looking for a maintainer

Credits
-------

This module was originally written for Drupal by Jeff Eaton
(https://github.com/eaton).

