=== Postmark Approved Wordpress Plugin ===
Contributors: andy7629, alexknowshtml
Tags: postmark, email, smtp, notifications, wp_mail, wildbit
Requires at least: 3.2
Tested up to: 3.2
Stable tag: trunk

This Postmark Approved Wordpress Plugin enables Wordpress blogs of any size to deliver and track Wordpress notification emails reliably, with minimal setup time and zero maintenance.

== Description ==

This Postmark Approved Wordpress Plugin enables Wordpress blogs of any size to deliver and track Wordpress notification emails reliably, with minimal setup time and zero maintenance. No more SMTP errors or delivery problems with Postmark!

If you don't already have a free Postmark account, you can get one in minutes. Every account comes with 1000 free sends.

== Installation ==

1. Upload postmark directory to your /wp-content/plugins directory
2. Activate plugin in WordPress admin
3. In WordPress admin, go to Settings then Postmark. You will then want to insert your Postmark details. If you don't already have a Postmark account, get one at http://postmarkapp.com
4. Verify sending by entering a recipient email address you have access to and pressing the "Send Test Email" button.
5. Once verified, then check "Enable" to override wp_mail and send using Postmark instead.

== Frequently Asked Questions ==

= What is Postmark? =

Postmark is a hosted service that expertly handles all delivery of transactional webapp and web site email. This includes welcome emails, password resets, comment notifications, and more. If you've ever installed Wordpress and had issues with PHP's mail() function not working right, or your Wordpress install sends comment notifications or password resets to spam, Postmark makes all of these problems vanish in seconds.

= Will this plugin work with my Wordpress site? =

The Postmark Approved Wordpress plugin overrides any usage of the wp_mail() function. Because of this, if any 3rd party code or plugins send mail directly using the PHP mail function, or any other method, we cannot override it. Please contact the makers of any offending plugins and let them know that they should use wp_mail() instead of unsupported mailing funcitons.

= Does this cost me money? =

This Postmark plugin is 100% free. All new Postmark accounts include 1000 free email sends. Beyond your first 1000 email sends, they will cost only $1.50 per 1000 sends with no monthly commitments and no expirations.

We will send you multiple warnings as you approach running out of send credits, so you don't need to worry about paying for credits until you absolutely need them.

Sign up for your free Postmark account at http://postmarkapp.com and get started now.

= My emails are still not sending, or they are going to spam! HELP!? =

No worries, our expert team can help. Just send an email to support@postmarkapp.com or tweet @postmarkapp for help. Be sure to include as much detail as possible.

= Why should I trust you with my email sending? =

Because we've been in this business for many years. We’ve been running an email marketing service, Newsberry, for five years. Through trial and error we already know what it takes to manage a large volume of email. We handle things like whitelisting, ISP throttling, reverse DNS, feedback loops, content scanning, and delivery monitoring to ensure your emails get to the inbox.

We're hosted at Rackspace, where we’re able to offer both the physical (SAS70 data center) and environment security through a completely dedicated cluster of servers. Our servers utilize virtualization and high availability failover protection to properly handle outages and keep your data safe.

Most importantly, a great product requires great support and even better education. Our team is spread out across six time zones to offer fast support on everything from using Postmark to best practices on content and user engagement. A solid infrastructure only goes so far, that’s why improving our customer’s sending practices helps achieve incredible results

== Screenshots ==

1. Postmark WP Plugin Settings screen.

== Changelog ==

= v1.0 =
First Public release.