# magento2-countdown-banners
A Magento 2 extension built to help e-commerce stores drive sales by adding custom banners with countdown timers for special offers and promotions.

## Installation with Composer
- Include the repository: `composer require softwareforsapiens/magento2-countdown-banners`
- Enable the extension: `php bin/magento --clear-static-content module:enable SFS_CountdownBanners`
- Upgrade db schema: `php bin/magento setup:upgrade`
- Clear cache

## Installation without Composer
- Download ZIP file of this extension
- Place all the files of the extension in you Magento 2 installation folder under `app/code/SFS/CountdownBanners`
- Enable the extension: `php bin/magento --clear-static-content module:enable SFS_CountdownBanners`
- Upgrade db schema: `php bin/magento setup:upgrade`
- Clear cache


## Configuration
- Create new countdown banners in the admin panel under "Marketing" > "Promotions" > "Countdown Banners"
- Use the token "{{timer}}" in your banner text to set where the countdown timer will appear (if timer is enabled for your banner)
- After creating a countdown banner, you will see its code inserts on the banner's edit form.
- Copy the code to view your banner on desired pages via CMS content, PHTML files, and/or XML layouts.
  

