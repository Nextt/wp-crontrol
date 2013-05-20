# WP-Crontrol [![Build Status](https://travis-ci.org/wp-repository/wp-crontrol.png?branch=master)](https://travis-ci.org/wp-repository/wp-crontrol)
__WP-Crontrol lets you view and control what's happening in the WP-Cron system__

## Details
[Homepage][1.1] | [WordPress.org][1.2]

| WordPress					| Version			| *		| Development				|					|
| ----:						| :----				| :---: | :----						| :----				|
| Requires at least:		| __3.1__			| *		| [GitHub-Repository][1.3]	| [Translate][1.6]	|
| Tested up to:				| __3.5.1__			| *		| [Issue-Tracker][1.4]		|					|
| Current stable release:	| __[1.2][1.5]__	| *		| Current dev version:		| [1.3-dev][1.7]	|

[1.1]: http://www.scompt.com/projects/wp-crontrol
[1.2]: http://wordpress.org/extend/plugins/wp-crontrol/
[1.3]: https://github.com/wp-repository/wp-crontrol
[1.4]: https://github.com/wp-repository/wp-crontrol/issues
[1.5]: https://github.com/wp-repository/wp-crontrol/archive/1.2.zip
[1.6]: https://translate.foe-services.de/projects/wp-crontrol
[1.7]: https://github.com/wp-repository/wp-crontrol/archive/master.zip

### Description
WP-Crontrol lets you view and control what's happening in the WP-Cron system. From the admin screen you can:

 * View all cron entries along with their arguments, recurrence and when they are next due.
 * Edit, delete, and immediately run any cron entries.
 * Add new cron entries.

The admin screen will show you a warning message if your cron system doesn't appear to be working (for example if your server can't connect to itself to fire scheduled cron entries).

From the settings screen you can also add, edit and remove cron schedues.


## Development
### Developers
| Name					| GitHub				| WordPress.org			| Web						| Status				|
| :----					| :----					| :----					| :----						| ----:					|
| Edward Dale			| [scompt][2.1.1]		| [kgraeme][2.1.2]		| http://www.scompt.com/	| Active				|
| John Blackbourn		| [johnbillion][2.2.1]	| [johnbillion][2.2.2]	| http://lud.icro.us/		| Active				|

[2.1.1]: https://github.com/scompt
[2.1.2]: http://profiles.wordpress.org/scompt/
[2.2.1]: https://github.com/johnbillion
[2.2.2]: http://profiles.wordpress.org/johnbillion/


## License
__[GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)__

WP-Crontrol is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.


## Changelog
* __1.3__ _[future plans/roadmap][4.1]_
	* added build testing via travis-ci.org
	* added custom unit tests @TODO
	* TBD
* __1.2__
	* added German translation
* __1.0__
	* Input of PHP code for cron entries
	* Non-repeating cron entries
	* Handles cron entries with arguments
* __0.3__
	* Internationalization
	* Editing/deleting/execution of cron entries
	* More text, status messages, etc.
	* Allow a user to enter a schedule entry in a human manner
	* Looks better on WordPress 2.5
* __0.2__
	* Fully documented the code.
	* Fixed the bug that the activate action wouldn't be run if the plugin wasn't in a subdirectory.
	* Now will play nicely in case any other plugins specify additional cron schedules.
	* Minor cosmetic fixes.
* __0.1__
	* Super basic, look at what's in WP-Cron functionality.

[4.1]: https://github.com/wp-repository/wp-crontrol/issues