v2.4.0
==================
* Adding disable-search and disable-sort properties for hiding search and sort

v2.3.5
==================
* reduce icon-set imports

v2.3.4
==================
* fixing up versions
* remove unneeded demo-style import

v2.3.3
==================
* properly scope localize (#13)

v2.3.2
==================
* add unit test for date objects

v2.3.1
==================
* accept dates as objects or strings

v2.3.0
==================
* Upgrades component to be Polymer 1.x/2.x hybrid compatible
* Adds new property selectedItemRef that notifies out the selected item object.
  This makes it more convenient to bind the selected item and get information
  about it rather than looping over the listItems to find the one that matches
  the ID in selectedItem.
* Refactor to remove moment.js dependency in favor of a small fromNow method,
  adds localization strings to match

v2.2.7
==================
* remove old css variables from documentation

v2.2.6
==================
* allow severity of undefined in sort order

v2.2.5
==================
* fix hover state (#11)

v2.2.4
==================
* add device flags

v2.2.3
==================
* fix alignment in IE/S9

v2.2.2
==================
* fix infinite resize loop

v2.2.1
==================
* tweak spacing again

v2.2.0
==================
* add support for localization

v2.1.1
==================
* tweak spacing

v2.1.0
==================
* add iron-resize and responsive behavior

v2.0.3
==================
* pickup latest forms css

v2.0.2
==================
* runtime theming for demo

v2.0.1
==================
* fix search icon and header layout

v2.0.0
==================
* update dependencies and colors for design refresh
* removed unused code: px-input-group-design
* component redesign
* removed default styling
* added requested enhancements #6 and #7
* code review feedback

v1.0.1
==================
* fixed #5

v1.0.0
==================
* fix issues #3 & #4, uprev for semver reasons

v0.2.30
==================
* fix other typo

v0.2.29
==================
* fix typo

v0.2.28
==================
* replace getElementsByClassName

v0.2.27
==================
* updated px-vis-dropdown to 3.X

v0.2.26
==================
* change foreach loops to for loops

v0.2.25
==================
* forced default selection, updated demo per design feedback

v0.2.24
==================
* update style variables for dropdown

v0.2.23
==================
* Update demo page using px-demo

v0.2.22
==================
* Updating so px-demo-snippet and px-api-viewer get new grays

v0.2.21
==================
* small display issue in Safari (desktop/mobile) and Chrome (mobile)

v0.2.20
==================
* Update colors design to pick up new colors

v0.2.19
==================
* changing ghp.sh to account for Alpha releases

v0.2.18
==================
* update style of sort/search to closer match spec

v0.2.17
==================
* Update dependencies

v0.2.16
==================
* added word-wrap and word-break for long strings

v0.2.15
==================
* changing browser in wct testing from safari 8 to safari 10 on elcapitan

v0.2.14
==================
* fixed icon spacing issues

v0.2.13
==================
* changing all devDeps to ^

v0.2.12
==================
* Update px-theme to 2.0.1 and update test fixtures

v0.2.11
==================
* update dependencies for dropdown

v0.2.10
==================
* separated predix and sketch styles

v0.2.9
==================
* bower updating px-demo-snippet

v0.2.8
==================
* added style variables for theming

v0.2.7
==================
* fixed svg sizing
* added grey background to list items
* added cursor 'pointer' for list items
* hid detail on initial load
* added picture to readme
* updated demo

v0.2.6
==================
* fixed sauce credentials

v0.2.1
==================
* update dependencies

v0.2.0
==================
* change height from style variable to property
* update demo

v0.1.0
==================
* bump version out of alpha

v0.0.2
==================
* added auto-ghp
* fixed actionable text dependency

v0.0.1
==================
* Initial release
