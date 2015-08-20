=== GF Upload to Email Attachment ===
Contributors: billiardgreg
Donate link: http://wpcms.ninja/
Tags: 
Requires at least: 3.8.3
Tested up to: 4.3
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This allows you to create a notification in gravity forms of an email that would send with the files being uploaded by that form as an attachment. Use GFEAU and GFEAUNZ in the notification title you can add files to outbound email.

== Description ==

Gravity Forms was built to be able to store all uploaded files to the server and email you a link.  There are times that you need to have that file get attached to the notification email.  By creating a notification in the form with GFUEA added to the end of it tells Gravity Forms to also attach any files to the outbound email as well as save it with the entry in the back-end.  

Works with both single and multiple upload boxes as well as multiiple notifiations.  As this notification name isn't really used in any other place I thought it would be the easiest way to add this functionality.  If multiple files are attached it attempts to create a zip file to send and after confirmation message is sent it removes the zip file.  Adding NZ so the end of the notification reads GFUEANZ tells the plugin to not zip up the files when attaching.

Utilizes code example from Gravity Forms gforms_notification page modified to attach the files getting uploaded to the notification email based upon last 5 characters of the notification name.    

== Frequently Asked Questions ==

= Where can I get answers to questions? =

You can email greg@wpcms.ninja to receive answers or go to http://wpcms.ninja

== Installation ==

Install plugin and activate.

Add GFUEA or GFUEANZ for No Zipping to the Gravity Forms email notification name and all files uploaded will be attached to outbound email.

== Screenshots ==

1. No Screenshot

== Changelog ==

= 1.4 =
* Created 1.4 beta version with delete all files from server but leave entry in gravity forms for other information tracking.  It will have a broken link for the image right now.

= 1.3 =
* Updated readme.

= 1.2 =
* Added no zip addition to multifile upload.

= 1.1 =
* Added zip functionality to multifile upload.

= 1.0 =
* Updated description and changed to stable version 1.0

= .1 =
* Initial Release of Plugin

== Upgrade Notice ==

= 1.3 =
* Updated readme.

= 1.2 =
* Added no zip addition to multifile upload.

= 1.1 =
* Added zip functionality to multifile upload.

= .1 =
* Initial Release of Plugin