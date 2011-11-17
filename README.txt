-----------------

Make sure you enable UNI Dandelion CSS after installing by:

	- Visit your theme settings page (/admin/appearance/settings/YOURTHEME)
	- Click "Toggle styles"
	- Check "Subtheme styles (all) - YOURTHEME-global.css"
	- Click Save configuration

-----------------

UNI Dandelion

This theme has been developed as a subtheme of UNI Base Theme (unibasetheme). For more information on unibasetheme go to: http://www.uni.edu/features/uni-base-theme

YOU MUST HAVE INSTALLED:
Omega Drupal Theme (http://www.drupal.org/project/omega)
UNI Base Theme (http://www.uni.edu/features/uni-base-theme)


/------------ SUBTHEMING UNI Dandelion -----------/

USING THE STARTERKIT (when YOURTHEME is noted, it is referenced to your theme name, without any dashes, spaces, or apostrophes)

1.) Copy the starterkit_uni_dandelion folder into sites/all/themes.

2.) Rename the copied folder to YOURTHEME.

3.) Rename the starterkit_uni_dandelion.info file to YOURTHEME.info

4.) Editing the .info file 
	- Change the following lines to suit your needs:
		name = My Custom Theme
		description = My own custom UNI Dandelion subtheme

	- Rename the css information further down the .info file:
		Replace each instance of YOURTHEME with your theme name. 
		(an easy way to do this is use a find/search/replace method to replace all instances of YOURTHEME with your theme name.

5.) Rename the appropriate responsive CSS files from /css
	- Replace each instance of YOURTHEME with your theme name.

6.) Turning on your subtheme
	- Visit /admin/appearance
	- Click "Enable and set default" on the appropriate subtheme you've created.

7.) Enable your custom CSS
	- Visit your theme settings page (/admin/appearance/settings/YOURTHEME)
	- Click "Toggle styles"
	- Check "Subtheme styles (all) - YOURTHEME-global.css"
	- Click Save configuration

(Make sure both UNI Dandelion as well as YOURTHEME stylesheets are enabled (checked) on the Toggle styles page)

*You must keep all region, zone, settings information, as this will not be inherited from the base theme.

If you need further support on subtheming please view the Drupal.org support page at: http://drupal.org/node/225125