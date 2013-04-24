# Alfred Workflows

## [Due](http://www.dueapp.com) Tools

### Version 2 Release Notes

* Rewritten with UI scripting 
  * Search bar actions are far more reliable
  * Grouped simalar actions into contained compiled scripts
Send calendar events to Due
    * BusyCal
    * OS X Calendars
* Search Panes
  * Reminders
  * Timers
  * Logbook
* Examples of how I slice my Due reminders lists
* [OmniFocus Perspective Icons by Icons & Coffee](http://iconsandcoffee.com/perspective-icons/)

### OmniFocus

**do**
:   Send Selected OmniFocus tasks to Due.app

### Quick Task Entry (Imitates the the iOS presets)

**dam**
:   Quick Task – Morning (6 AM)

**dm**
:   Quick Task – Middle Day (11:30 PM)

**ded**
:   Quick Task – End of the Day (4 PM)

**de**
:   Quick Task – Evening (6 PM)


NB: The times can be adjusted in the 'Run Scripts' Actions (middle column) echo statement.

### Defer Reminders

**dd**
:   Postpone by One Day

**dh**
:   Postpone by One Hour

**ds**
:   Postpone by 10 Minutes


NB: These trigger the defined keyboard shortcuts (I can never remember them).

### Pomodoro Timers

**dpl**
:   Pomodoro Long Break Timer (15 Min)

**dps**
:   Pomodoro Short Break Timer (5 Min)
    
**dpw**
:   Pomodoro Work Timer (25 Min)
 
#### Pomodoro Timers Notes

* These actions work by searching for the names of Specific timers
* You must create timers on the Timer Panel 
    * 5 Minutes Timer
    * 15 Minutes Timer
    * 25 Minutes Timer
* If you use different Timer names, adjust the 'Run Scripts' Actions (middle column) echo statement.

**dq**
:   Create a Sequential Task

#### Sequential Tasks Notes

* Formatting: `This is task one 6 am -- This is task two 5 pm`
* NB: The first task NEEDS TO BE COMPLETED ON AN iOS DEVICE.

### Create a Reminder for Calendar Events

**dce**
:   BusyCal Event to Due (Create a Due reminder from a selected BusyCal event)

**dcce**
:   OS X Calendar to Due (Create a Due reminder from a selected calendar event)

### Search Reminders, Timers and Logbook

**dsr**
:   Search Reminders Panel

**dsm**
:   Search Timers Panel

**dsb**
:   Search Logbook Panel

**dsu**
:   Search Reminders for URLs

### Examples of How I Slice My Due Reminders

* I shove a lot of stuff in Due–I use a defined naming convention to list the differnt reminder types
    * Any task that pops up and needs to be completed the same day
    * Deferred Toots
    * Deferred SMS
    * Consumables (Usually Triggered by Bookmarklets [which I've included](https://github.com/ChewingPencils/alfred_workflows/blob/master/due_bookmarklets.md))
* I use a unicode Trigram as a delimiter for these types of reminders
    * Thunder - "inciting movement"
* These actions should be deleted / modified to fit your needs
* Any actions which are not triggered by bookmarklets have matching Drafts actions.

**dt**
:   Create a Today Reminder

**dj**
:   Create s Journal Reminder

**dst*
:   List Today Reminders

**dso**
:   List Deferred Toot Reminders

**dss**
:   List Deferred SMS Reminders

**dsr**
: List Items to Read

**dsc**
: List Items to Check Out (Apps, Websites, Etc.)

**dsl**
: List Items to Listen to (Random Podcasts)

**dsw**
: List Items to Watch

**dsj**
: List Items to Journal

## NerdQuery

Search [NerdQuery](http://nerdquery.com) and displays results in Alfred's item pane.


## OneLook.com

A workflow for (OneLook)[http://onelook.com].

### OneLook Quick Definition ###

Returns the Quick Definitions.

* Enter:		Open OpenLink results page.
* CMD+Enter: 	Display definition as Large Text
* CMD+Enter:	Copy definition to clipboard



### OneLook Reverse Look Up ###

Returns results from the the reverse lookup

* Enter:     	Open in Safari
* CMD+Enter:	Copy selected term to clipboard



### OneLook Bits ###

Returns results from OneLooks Advanced Search

Enter:   	Open in Safari
CMD+Enter:	Copy selected term to clipboard

#### Search Examples

* bluebird		- Find definitions of bluebird  
* blue*			- Find words and phrases that start with blue  
* *bird			- Find words and phrases that end with bird  
* bl????rd		- Find words that start with bl, end with rd, and have 4 letters in between  
* bl*:snow		- Find words that start with bl and have a meaning related to snow  
* *:snow or :snow		- Find any words related to snow  
* *:winter sport		- Find words related to the concept winter sport  
* *winter**		- Find phrases that contain the word winter  
* expand:nasa		- Find phrases that spell out n.a.s.a.  

## An Alfred Workflow For PathFinder

* pfd   - Toggle dual pane
* pfcr  - Copy selection to right pane
* pfcl  - Copy selection to left pane
* pfmr  - Move selection to right pane
* pfcl  - Move selection to left pane 
* pftw  - Trigger my Work Path Finder tab set [^1]
* pftc  - Trigger my Code Path Finder tab set [^2]
* pftn  - Trigger my Notes Path Finder tab set [^3]
* pfyx  - Trigger my OS X Path Finder tab set [^4]
* pftp  - Toggle preview pane
* pfbr  - Batch rename files
* pfnt  - Create a new text file
* pfdi  - Create new disk image
* pfhe  - Hex editor
* pfcs  - Checksum (MD5)
* pflw  - Label directory 'Working' (orange)
* pflc  - Clear label
* pfla  - Label - 'Pay Attention' (red)
* pfad  - Add selection to Drop Stack
* pfgi  - Toggle invisible files
* pfsp  - Swap panes
* pfgp  - Toggle package contents
* pfwf  - Find window
* pfwg  - Git window
* pfwt  - Tags and Rating window

Not Shown: 

* familypic - Opens a specific directory in a new tab
* familyvid - Opens a specific directory in a new tab
* pstream   - Opens iCloud photostream

NB: I use the very helpful Applescript: `menu_click`, by Jacob Rus

[^1]: Directories: inbox, projects, core, Dropbox, outlines, mind_maps.

[^2]: Directories: scripts, code, bin.

[^3]: Directories: ~, Library, Applications, Mobile Documents, usr; All of my external drives.

[^4]: Saved searches for new or modified files (today, yesterday, week, and month)
