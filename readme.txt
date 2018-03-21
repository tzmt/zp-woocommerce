=== ZodiacPress Sell Reports ===
Contributors: isabel104
Requires at least: 4.7
Tested up to: 5.0-alpha-42866
Requires PHP: 5.4
Stable tag: 1.1.2
License: GNU GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Sell astrology birth reports with WooCommerce.

== Description ==

ZodiacPress Sell Reports lets you sell astrology birth reports in your WooCommerce store. This plugin is an extension for [ZodiacPress](https://wordpress.org/plugins/zodiacpress/), so you must have that plugin installed in order to use this plugin.

The original ZodiacPress plugin lets your visitors get birth reports on your site for free. When you add ZP Sell Reports, you'll be able to sell the report as a product in your WooCommerce store. Your visitors will be able to view the report immediately after they pay.

### Privacy Policy and EU General Data Protection Regulation (GDPR) Compliance

ZP Sell Reports collects personal information on the birth report order form. This information includes date of birth, time of birth, and place of birth. ZP Sell Reports stores this information with the customer's order in your WooCommerce store. The information is then used to create the astrology report for the customer. 

To comply with the EU GDPR, the plugin includes a tool that lets you erase the sensitive birth data in one click. You can erase the birth data for all orders at once, or for one specified order.

### Technical Details

*   Supports PHP 5.4 and above, including PHP 7+.
*   Includes a language POT file so you can translate it.
*   Requires WordPress version 4.7 or higher.
*   Requires WooCommerce version 3.2.4 or higher.
*   Requires ZodiacPress version 1.5.5 or higher.
*   Report delivery method: There will be a link on their purchase receipt to “View Your Report.”
*   In addition, they can view their purchased reports from within their “My Account” area when logged in to your site.


== Installation ==

**Install and Activate**

1. In your WordPress dashboard, go to Plugins > Add New.
2. Click Upload Plugin.
3. Click Browse to upload the ZIP file which you purchased.
4. Click Install Now.
5. Click Activate Plugin to activate the plugin.

**Create a Report Product To Sell**

To sell an astrology report, create a report product. Creating a report product is just like creating any other product in your WooCommerce store, with a few mandatory steps:

1. Go to Products > Add New.
2. Enter your desired title for the product. For example, Natal Report.
3. Optional: Enter a description in the first description box.
4. Go to the Product data panel and select Virtual.
5. Enter a price for the report.
6. Click the Inventory tab and select Sold individually.
7. Go to the Product short description panel. This box is where you must paste the ZodiacPress shortcode for the report. To sell a regular Birth Report, paste this shortcode:
    
    `[birthreport sell="woocommerce"]`

    If you have the House Systems extensions, you can sell a House Systems report. To sell a House Systems report, paste this shortcode:
    
    `[birthreport sell="woocommerce" report="house_systems"]`

    You can sell any type of ZodiacPress report by adding sell="woocommerce" to the shortcode.

    For example, you may have a report with the Sidereal Zodiac and a custom house system, like this:

    `[birthreport sidereal="lahiri" house_system="W"]`

    You can sell that report by adding sell="woocommerce", like this:

    `[birthreport sidereal="lahiri" house_system="W" sell="woocommerce"]`

    In addition to the shortcode, you are allowed to enter other content into the Product short description box. For example, you can add a short description of the report.

8. Just like with any other product in your WooCommerce store, you can set product categories, tags, and images for this report product, if you wish to do so.
9. Click “Publish” to make your report available for sale on your site.

== Frequently Asked Questions ==

= What if I encounter a problem with this plugin? =

If you encounter problems with this plugin, first check to make sure that your site meets all the requirements for this plugin to work. The requirements are:

*	WordPress version 4.7 or higher.
*	WooCommerce version 3.2.4 or higher must be installed and activated.
*	ZodiacPress plugin version 1.5.5 or higher must be installed and activated.
*	In addition, make sure you meet the requirements for the core ZodiacPress plugin.

== Changelog ==

= 1.1.2 = 

* Fix - Enable license for easy updates.
* Tweak - On the form, update offset when hour/minute is changed. Previously, the offset was only updated if the day/month/year was changed.
* Tweak - Add version query string to scripts link to ensure the latest is used even with cache.

= 1.1 =

* Fix - On the form, remove prior hidden inputs in case of changing city. Previously, when changing city, many hidden inputs would accumulate.

= 1.0 =

* Initial public release.
