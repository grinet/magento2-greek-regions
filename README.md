# [MageVision](https://www.magevision.com/) Greek Regions Extension for Magento 2

## Overview
The Greek Regions extension adds the Greek regions in English and Greek language. Useful for localization, shipping and tax calculation.

## Key Features
	* List of Greek Regions
        * In English and Greek language
	
## Other Features
	* Developed by a Magento Certified Developer
	* Meets Magento standard development practices
	* Simple installation
	* 100% open source

## Compatibility
Magento Community Edition 2.1

## Installing the Extension
	* Backup your web directory and store database
	* Download the extension
		1. Sign in to your account
		2. Navigate to menu My Account → My Downloads
		3. Find the extension and click to download it
	* Extract the downloaded ZIP file in a temporary directory
	* Upload the extracted folders and files of the extension to base (root) Magento directory. Do not replace the whole folders, but merge them.
        * Connect via SSH to your Magento server as, or switch to, the Magento file system owner and run the following commands from the (root) Magento directory:
            1. cd path_to_the_magento_root_directory 
            2. php -f bin/magento module:enable MageVision_GreekRegions
            3. php -f bin/magento setup:upgrade
            4. php -f bin/magento cache:flush
        * Log out from Magento admin and log in again
		
## Support
If you need support or have any questions directly related to a [MageVision](https://www.magevision.com/) extension, please contact us at [support@magevision.com](mailto:support@magevision.com)


## PHP and Mage-OS compatibility

This Grinet fork retains the original PHP 5.5/5.6/7.0 and Magento framework 100.x constraints and additionally allows PHP 8.1-8.5 with framework 103.x. Isolated setup checks preserve 51 regions and 102 translated names. Mage-OS keywords indicate compatibility evidence from its Magento namespaces and Composer replacement metadata, not full integration certification. The upstream package identity is preserved; this GitHub release does not publish a new version of the upstream Packagist package.
