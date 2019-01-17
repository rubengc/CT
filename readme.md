# About Custom Tables #
Custom Tables (CT) is a WordPress developers toolkit to handle custom database table workflow similar to WordPress CPT.

Check [example.php](./example.php) file included on this project to see a few examples to get it working.

Important: CT is in development phase, this means current version is unstable and much of the current features will change. To use this library on live project be sure you know you are doing!

Contributions are really appreciated! Looking for help to standarize functions and hooks as well as for documentation.

## Features (work in progress) ##

Custom table registration:

- [x] Custom table registration (like registering a WordPress post type)
- [x] Automatic table creation if not exists
- [x] Easy field definition
- [x] Schema parser
- [x] Automatic schema updater (yay!)
- [x] Ability to show or hide from admin (aka disable UI for a desired table)
- [x] Custom Capabilities (with support for administrators)
- [x] Meta data functionality
- [x] Query class to handled cached queries (like WP_Query but for custom tables)
- [x] WP rest API support (custom table and meta data)

List view with support similar to WP tables:

- [x] Pagination
- [x] Search
- [ ] Sortable Columns
- [x] Bulk actions
- [ ] List view views
- [ ] Trash functionality
- [x] Delete Permanently action

Edit View similar to WP edit screen:

- [x] Meta boxes
- [x] Screen options
- [x] Show hide Meta boxes
- [x] Allow user to toggle view columns
- [x] Allow define edit view columns (to force to 1 column)
- [x] Delete Permanently action

Other features

- [x] CMB2 support
- [ ] Documentation (help wanted!)
- [ ] Add WP Lib Loader to always load the newest version (http://jtsternberg.github.io/wp-lib-loader/)
