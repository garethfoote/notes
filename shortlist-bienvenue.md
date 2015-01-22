
## Widget - Banner/Link or Sign-up form

* **Banner** 
Just an image + link  to other part of site or other brand site.

* **Sign-up**
JS form submission to dotmailer end point with brand and user. 

## Content
* Banner or Sign-up (Is this a simple link or sign-up form?) (*)
* Brand / theme (*)
* Category / channel (*)
* Start and end date
* Main sell
* Button sell
* Large background image (*)
* Small background image
* Sign-up - Button Sell
* Sign-up - Dotmailer dropdown
* Banner - URL


## Notes

* Dotmailer wrapper
http://dm-wrapper.herokuapp.com/  (https://bitbucket.org/ShortlistMedia/dotmailer-wrapper)
/save/{[brandName](https://bitbucket.org/ShortlistMedia/dotmailer-wrapper/src/67bae07f72615703aa75c8a4d71aee6496005212/lib/brand-config.js?at=master)} (brand name is camel case, e.g. mrHyde, emeraldStreet)
email=g@g.com

* grunt deployments
	* `grunt rsync:uploads` - Pull uploads from live
	* `grunt db_pull --target=production` - Pull prod database



## Amends (post meeting with Els and JShez)

* Focus on sign up (banner is of secondary importance)
* Additional custom field - multiple select ('Choose brand that display widget') 
* Optional background image
* Background image now a header image
*  Layout change so that header precedes other content
* Brand themes
	* Emerald St & Mr Hyde - Use existing sign up forms, font and layout 
	* Shortlist and Stylist - Use style guides (to be provided)
* >>>>>>>> Other bits <<<<<<<<   
* Typekit whitelist
* Add bnv to dm-wrapper whitelist


