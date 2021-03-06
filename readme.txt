=== WooCommerce ===
Contributors: CoenJacobs
Tags: woocommerce, payment, raiblocks, xrb, cryptocurrency
Requires at least: 4.4.0
Tested up to: 4.9.1
Stable tag: 0.1.3
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

RaiPay payment gateway for WooCommerce to allow payments in RaiBlocks (XRB).

== Description ==

RaiPay payment gateway for WooCommerce to allow payments in RaiBlocks (XRB).

== Installation ==

= Minimum Requirements =

* PHP version 5.4 or greater (PHP 5.6 or greater is recommended)
* MySQL version 5.0 or greater (MySQL 5.6 or greater is recommended)
* WordPress 4.4+

== Changelog ==

= 0.1.3 =
* Added new (many!) currencies implemented by RaiPay

= 0.1.2 =
* Fixed passing correct currency to payment request
* Optimised webhook handling to read input more reliable
* Removed redundant order note containing payment token

= 0.1.1 =
* Added check for supported currencies before enabling gateway

= 0.1.0 =
* Initial release