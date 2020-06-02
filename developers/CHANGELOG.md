## 1.0.4 @DD.MM.2020

- Added theme `/dev` directory, and moved, updated, and removed assets from theme root. 
- Relocated `/assets/sass/*` and  `/assets/sass/style.scss` to `/dev/sass/*`. 
- Removed `/css`, `/dist`, and `/languages` directories from `/assets` directory.
- Updated project `.gitignore` to ignore node_modules and vendor directories.

## 1.0.3 @17.Feb.2017

Changed the `setup_child_theme()` callback priority number to 15 to ensure that Genesis' setups run first before the child theme.

## 1.0.2 @17.Oct.2016

- Fixed path for enqueuing `/assets/js/responsive-menu.js`

## 1.0.1

Changed autoload.php to move Customizer loading into the nonadmin files.  Why?  The customizer action occurs before `admin_init`.  It wants to be loaded at the start independent of the admin area.

## 1.0.0

Initial release.