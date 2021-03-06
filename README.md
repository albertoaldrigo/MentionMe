MentionMe 2.0
============

A plugin for MyBB 1.6.x that allows Twitter-style tagging and integration with MyAlerts (https://github.com/euantor/MyAlerts).

While this plugin works with MyAlerts, it is not necessary for the tagging features to work. When MyAlerts is installed integration is enabled by default (in Admin CP).

MyBB Release Thread: http://community.mybb.com/thread-131448.html

Change log
=========
05-18-2013 2.0 released! Added much better name caching so that for the average page view little or no queries will be required. Added a task to build the name cache and reconstructed mention alerts routines to use the name cache as well. Changed some logic and structure but (other than one nice side effect that user names with spaces in them [under certain circumstances] will be matched without quotes [if that name is already stored in the cache and is either on the end of a line or is postfixed with punctuation such as a comma or period) normal operation is unchanged-- just much less expensive.

03-30-2013 1.6.1 releasd with a better script to enable alerts for all users (thanks to Shade) and thread titles in mention alerts (thanks to counterkarma)-- also cleaned up a little and added some comments.

03-17-2013 1.6 released to update for compatibility with MyAlerts 1.04

01-08-2013 1.5.3 release to prevent alerts from being created for quoted mentions, to stream-line mention detection and to make slight internal adjustments for the better of the plugin.

01-02-2013 1.5.2 released to improve name caching and fix a bug that only surfaced when given a certain set of chracters to work with.

12-31-2012 1.5.1 released to add alerts for mentions edited into posts and to fix some small alert creation problems.

12-26-2012 1.5 released featuring optional advanced matching and a bug fix for _is_installed().

12-24-2012 Initial commit.

