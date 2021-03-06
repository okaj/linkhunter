# Linkhunter changelog

## 1.3.2

* Add notification message when adding a link takes too long due to a slow API.
* Clicking to remove a suggested tag now places it back in the suggestion box.

## 1.3

* Add tag autocompletion in the "Add Bookmark" screen. After entering some
  text, your most-used tag that matches will be shown in grey; press tab or the
  right-arrow key to select it.
* Add retina browser-action icon.
* Add feedback email link to the configuration panel.
* Allow updating previously-saved links in Delicious again (this was failing
  due to an undocumented API change).

## 1.2.3

* Bugfixes.

## 1.2.2

* Added retina graphics.

## 1.2.1

* Updated Chrome manifest to version 2.
* Fixed popup for Chrome's "new tab" page.
* Rate-limited calls to the last-updated API endpoint, which otherwise was
  being called each time the popup was opened.

## 1.2.0

* Switched to nine visible items at a time, to support clean scrolling on
  up/down arrow keys.
* Reduced some animation flicker.
* After much demand, added a scrollbar.

## 1.1.7

* Fixed auth for Chrome 19.

## 1.1.6

* Clarified authentication error messages.

## 1.1.5

* Set a default opacity on the iframed popup to override one set by some sites.
* Now handling 429 responses from Pinboard gracefully.

## 1.1.4

* Updated our site URL.

## 1.1.3

* Fixed handling of the last-updated timestamp.

## 1.1.2

* Added ctrl-j keyboard shortcut for Windows folks.
* Fixed some more bugs with the iframed popup.
* Now displaying sync error messages.

## 1.1.0

* Improved handling of link privacy.
* Improved favicon support.

## 1.0.2

* Updated the toolbar icon.
* Improved iframe popup animation.
* esc keyboard shortcut navigates logically up/back/out consistently.
* cmd-j shortcut now navigates from initial search view to add view.
* Close the iframed popup when clicking outside of it.
* Handle frameset pages.
* Fall back to standard Chrome popup when an iframe won't work.
* Fixed the popup size on zero results.
* Fixed the off-by-one height of the last results item.

## 1.0.1

* Added cmd-j keyboard shortcut and iframed popup.
* Added an interface for adding new bookmarks.
* Ensured newest bookmarks are displayed first.
* Improved options page and loading experience.
* Limit to ten results.
* Now testing new service credentials before accepting them.
* Improved search algorithm.
* Removed feedback text and cleaned up buttons.
* Improved arrow on "Go Hunting" button.

## 1.0.0

* Initial release.
