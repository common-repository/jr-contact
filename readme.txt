=== Plugin Name ===
Contributors: Jake Ruston
Donate link: http://www.jakeruston.co.uk
Tags: contact, form, user, email
Requires at least: 2.0.2
Tested up to: 3.0.0
Stable tag: 1.9.5

This Contact Form plugin allows you to create a simple feedback submission form.

== Description ==

This Contact Form plugin allows you to create a simple feedback submission form, which let's the user send a message to you, securely, quickly and easily.

It generates multiple text fields, which can be edited from the Admin Panel. This let's you add extra fields, such as a phone number and a message subject.

This plugin is very simple to use - Simply enable the plugin, enter your e-mail address and you'll have a simple contact form to be used on your blog!

New in version 1.2.0 is a secure CAPTCHA system, so you can enable a CAPTCHA field on your form, to prevent spam comments.

Also, in version 1.3.0, the plugin now has Akismet support. This will make sure you don't get any spam messages through this plugin. It works well in conjunction with the CAPTCHA field.


== Installation ==

1. Upload `/jr-contact/` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Edit the JR Contact Settings in your Administration Panel
4. Add the tag [jr_contact] to your desired page, in HTML view.

== Frequently Asked Questions =

=

= Can I insert this form into somewhere else, eg. in the footer of my blog?

Yes, you can do this pretty easily, although it will require a simple edit of your template files. Open the template file in question, find the area where you want your form to show and then enter this code into the HTML:



<?php do_shortcode('[jr_contact]'); ?>



Your form should now display in this area.

= Does this work?

Yes.

== Changelog ==

= 1.7.0 =
* Contact form widget addition!

=

 1.6.4 =
* Bug fixes

=

 1.6.2 =
* Improved feedback form

=

 1.6.1 =
* Fixed CAPTCHA Bug

=

 1.6.0 =
* Show messages before the form

=

 1.5.0 =
* ReCAPTCHA Support

=

 1.4.0 =
* Address Fields support
* Improved E-Mail Notification

=

 1.3.0 =
* Akismet Support

* Security Fixes



= 1.2.1 =
* Important Bug Fix



= 1.2.0 =
* CAPTCHA Implementation

* E-Mail Address Validation

* Bug fixes



= 1.0.1 =
* Important Bug Fix

= 1.0 =
* Initial Release
