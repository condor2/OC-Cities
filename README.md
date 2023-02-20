Select City
===========

Opencart extension to change the "city" input column to a drop-down list.

Requirements
------------

* Opencart v2.3.0.2 ([link] (http://www.opencart.com/index.php?route=download/download))

Installation
------------

1. Extract zip file
2. Upload folder `admin`, `catalog` into the Opencart directory (usually` / public_html / `)
3. From `Extensions-->Extensions Installer` install ocmod extension by selecting `select_city_v23.ocmod.xml`
5. Give permission for `localization / city` (see the following link: http://forum.opencart.com/viewtopic.php?f=144&t=30720)
5. Go to Admin> System> Localization> Cities
6. The `DB_PREFIX + city` table should appear in the database, which means the installation process was successful
