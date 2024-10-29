=== Auto Bulb Finder for WordPress ===
Contributors: mtoolstec
Tags: Automotive, Auto Bulb, Year Make Model
Donate link: https://shop.mtoolstec.com/donate
Requires at least: 6.0
Tested up to: 6.6.2
Requires PHP: 7.4
Stable tag: 2.8.0
License: GPL v2
License URI: https://auto.mtoolstec.com/license

Online bulb size database for vehicles from 1960 to 2024. Super easy to check by Year/Make/Model. Add to any page or content by a shortcode `[abf]`.

== Description ==
Auto Bulb Finder for WordPress is a plugin that allows users to search for car and all the headlights model based on the Year Make Model of the car. This plugin also supports binding products to specific headlight models and importing custom car data. The plugin makes it easy for users to find the right car headlight bulb for their vehicle, saving time and effort. 

= Features =
* Search by Year/Make/Model
* Add products to the bulb size
* Import custom vehicle data
* Export vehicle data as CSV file
* Add custom auto part data fitment
* Exclude vehicles from the search
* Support AJAX on Add To Cart Button

[Demo Website](https://shop.mtoolstec.com/auto-bulb-finder-plugin)

== Notice ==
= **Functionality Description** =
This plugin provides a Year/Make/Model search query from both the store database and an online database. 

= Store Database Features =
1. Vehicles can be imported or exported as CSV files in store.

= Online Database Features =
1. Require a network connection to the Auto Bulb Finder Server to retrieve vehicle information.
2. Require the license of Auto Bulb Finder to gain access to the online database.
3. The online database contains over 50000 vehicles from 1960 to 2024.

= Product Adaption Features =
1. Connnect product ids to the exact bulb size model.
2. Match different bulb models to accurate bulb size.

== Installation ==
Upload the Auto Bulb Finder Plugin to your site. Add vehicles and adaptions and you're able to search automotive bulb size by Year/Make/Model from your store. 
Submit the Purchase License of Auto Bulb Finder, you're able to access 50000 vehicles without any importing process.

== Frequently Asked Questions ==
How do I add the bulb finder to my website?
You can add the bulb finder to your website using the shortcode '[abf]'.

= How do I add a product to the bulb finder? =
Navigate to Auto Bulb > Adaption and add the product IDs to the exact bulb size model. The product IDs are comma separated.

= How will products show under the bulb location? =
The products will be in 5 columns on the PC, 3 on the tablet, and 2 on the mobile.

= What’s the priority of the query result between the server and store? =
The priority of vehicle query results can be set to Store only or Merge all. If choosing Store only, the query results from Auto Bulb Finder Server will not be shown.

= How to search for similar bulb sizes? =
While adding the bulb adaptions, the clients can easily search for similar bulb sizes and append them to the current bulbs. While adding a new adaption or saving existing adaptions, the duplicated bulb sizes will be removed automatically.

= Does it support AJAX on Add To Cart Button? =
Yes, the AJAX add-to-cart function is available after the 2.2.0 Version of Auto Bulb Finder.

= How do I add a vehicle to the bulb finder? =
Navigate to Auto Bulb > Vehicles and add the vehicle year, make, model, submodel, bodytype, and qualifier. The Bulb Size field is in the format like Low Beam Headlight: H11; Front Fog Light: 9005; Brack Light: 194;.

= How do I exclude vehicles from the bulb finder? =
Navigate to Auto Bulb > Vehicles and change the vehicle status to Exclude.

== Screenshots ==
1. Search vehicle by Year/Make/Model. All devices are supported.
2. Add adaptions to show products below the bulb size. 
3. Add custom vehicle data. The vehicles can be included or excluded from the online database. Import or export the vehicle data as CSV file.

== Changelog ==
1. Online bulb size database update vehicles till 2024.
2. Store vehicle database fix the issue of the vehicle not showing if empty submodel.