# discourse-stopforumspam

Right after a new user signs up for your forum, this plugin will check the user's email address, forum username, and/or IP address (depending on your plugin settings) against the [StopForumSpam](https://www.stopforumspam.com) database. If the user is found to be a suspected spammer, their user account will be auto silenced in Discourse.

## Installation

Follow [these instructions](https://meta.discourse.org/t/install-plugins-in-discourse/19157) to install this plugin in your Discourse installation.

**Note:** This plugin's git clone url is:
https://github.com/singerscreations/discourse-stopforumspam.git

## Configuration

After installing this plugin in Discourse, you'll be able to configure the following settings in the Plugins section of the Discourse Settings:

- **stopforumspam enabled:** Enables the plugin
- **stopforumspam check email:** Checks the user's email address against the StopForumSpam database
- **stopforumspam check username:** Checks the user's username against the StopForumSpam database 
- **stopforumspam check ip:** Checks the user's IP address against the StopForumSpam database

## Issues

If you have issues or suggestions for the plugin, please contact mike@singerscreations.com.

## Authors

This plugin was created and is maintained by Mike Singer ([https://meta.discourse.org/u/msinger](@msinger)).