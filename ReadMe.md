# Alfred Workflows

## [Due](http://www.dueapp.com) Tools

* od    - Send Selected OmniFocus tasks to Due.app
* dam   - Quick Task – Morning (6 AM)
* dm    - Quick Task – Middle Day (11:30 PM)
* ded   - Quick Task – End of the Day (4 PM)
* de    - Quick Task – Evening (6 PM)
* dd    - Postpone by One Day
* dh    - Postpone by One Hour
* ds    - Postpone by 10 Minutes
* dpl   - Pomodoro Long Break Timer
* dps   - Pomodoro Short Break Timer
* dpw   - Pomodoro Work Timer
* dq    - Create a Sequential Task

NB: The second task created by the sequential task action NEEDS TO BE COMPLETED ON AN iOS DEVICE.

## NerdQuery

Search [NerdQuery](http://nerdquery.com) and displays results in Alfred's item pane.


## OneLook.com

A workflow for (OneLook)[http://onelook.com].
## OneLook Quick Definition ##

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

bluebird			- Find definitions of bluebird
blue*			- Find words and phrases that start with blue
*bird			- Find words and phrases that end with bird
bl????rd			- Find words that start with bl, end with rd, and 
				  have 4 letters in between
bl*:snow			- Find words that start with bl and have a meaning 
				  related to snow
*:snow or :snow	- Find any words related to snow
*:winter sport	- Find words related to the concept winter sport
**winter**		- Find phrases that contain the word winter
expand:nasa		- Find phrases that spell out n.a.s.a.

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
