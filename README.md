# Password Cloud

Password Cloud is an Android App that helps you to keep all your important [secret] information and accounts of any kind in one place in smart and secure way. In the future there will be also a Win &amp; iPhone App neitherless a Computer/Web App.

`NOTE: This page is for Issue tracking of product in Beta testing.`

`Password Cloud is not on the Market yet!`

### Implemented so far
- Remember one password to keep all others: Web, email &amp; computer accounts; Wi-Fi passwords; PINs &amp; credit cards; Utility Companies information &amp; all general information you desire keep safe.
- Your passwords are protected with 256-bit Advanced Encryption Standard (AES).
- Advanced database utilities: Import, Export, <i>Silent Self-Erase</i> option.
- Innovative Android™ Material Design &amp; App usability
- Type of login: password

### To be done
- Multi type of login: pin, pattern &amp; digital finger reader (only for Samsung™ devices).
- Synchronize your encrypted database to your favorite cloud service and restore it in case of a device change or loss.
- Optionally you can activate the innovative <i>Only Online</i> function to never save locally your passwords.
- Reuse the database from your personal computer or different devices and keep it synchronized among them.
- Advanced database utilities: Restore, Merge &amp; Automatic Backup.
- Internal Help and FAQ.
- Show Wi-Fi registered accounts in your device.
- Autofill fields into browser.
- ... and much more!

# Change Log

### v0.28.0 beta of 19/06/2015
##### Main features
- Drawer with system labels and item list on main page
- Advanced search feature: deep search on fields, show first match
- Add/modify/remove items and templates
- Favorite items
- Manage labels
- Link/unlink labels to/from items and templates from the Editor
- Duplication not allowed for labels
- Duplication not allowed for items within same labels
- Copy values into clipboard on field tap + option with auto empty timeout
- Customizable Symbol and Color for any items, Switch dialogs to increase usability while create new items
- Customizable field titles and field types for items
- Advanced customizable Lock and Autolock when leaving App
- Database Utilities: Change primary password; Import/Export in clear; Erase; Customizable silent SelfErase at login

##### Sub features
- <i>Presentation:</i> Database creation at first execution
- <i>Presentation:</i> Import database enabled at first execution
- <i>Dialog:</i> About with thanks (libraries used) + © info + ChangeLog
- <i>Dialog:</i> Delete confirmation
- <i>Dialog:</i> MessageDialog hide kb
- <i>Dialog:</i> Select Template
- <i>Dialog ColorPicker:</i> Click on bars color enabled
- <i>Dialog ColorPicker:</i> enlarge holo center selection, enable click on it to choose the color
- <i>Dialog Symbol:</i> with ViewPager
- <i>Dialog Symbol:</i> New SVG Symbols for items
- <i>Drawer:</i> Smoothscroll on list if selected item is not visible
- <i>Editor:</i> ALL EditText with custom imeAction/imeOptions
- <i>Editor:</i> Auto add new empty field
- <i>Editor:</i> Close without save Dialog. Create new isModified function
- <i>Editor:</i> Creating new Item goes to ItemDetail not to ItemList
- <i>Editor:</i> Info icon for Empty view and Popup info style onClick. it explains how empty view works based on the Item/Template
- <i>Editor:</i> Linked labels are ordered when chosen
- <i>Editor:</i> Show vertical "accent" line for modified fields. Maintain state after rotation
- <i>Editor:</i> Undo bar
- Floating Action Button for new Templates and Items
- Floating Action Button in ItemDetail and EditItem
- <i>ItemDetail:</i> Fields: when custom title is empty, display the default from type
- <i>ItemDetail:</i> Symbol from SVG
- <i>ItemDetail:</i> Touch raise effect
- <i>ItemList:</i> Post delayed runnable for symbols
- <i>ItemList:</i> show Fav Icon with accent color
- <i>LoginActivity:</i> AppStatus
- <i>LoginActivity:</i> show changelog automatically if version in preference doesn't match with current version
- LruCache for SVG with AsyncTask
- Presentation pages with dynamic tree-structure options
- Sample templates/items &amp; enabled alfabetic fastscroll
- <i>Service:</i> Decrypt + sequentally load db / serialize into a Task for BackgroundService
- <i>Service:</i> Enables Post delay Save at each modification confirmed.  Now 15sec, not yet into settings!
- <i>Service:</i> LoadTask: check Database Inconsistency with custom exception
- <i>Service:</i> Save / deserialize + sequentially encrypt into a Task for BackgroundService
- <i>Service:</i> SaveTask: When exit App, if SaveTask is started, execute now the task don't wait delay
- <i>Settings:</i> Change Primary Password
- <i>Settings:</i> Double tap onback pressed
- <i>Settings:</i> Exit normally onback pressed; close app without close DB: add to back stack
- <i>Settings:</i> Export with Dialog
- <i>Settings:</i> Open Settings from everywhere
- <i>Settings:</i> SelfErase. If not enabled Menu button is displayed
- <i>Settings:</i> Statistics
- <i>Settings:</i> Transition effect slide in/out for left/right
- <i>Settings:</i> User learns Drawer at first execution

# Author
Davide Steduto

# Beta testers
Undisclosed

# Realease date
Undisclosed

# Licence
`Copyright © 2015 Davide Steduto. All rights reserved`
