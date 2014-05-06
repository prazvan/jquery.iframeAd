#jquery.iframeAd

This is a plugin to allow inserting of iframe ads into placeholder dom elements. The plugin will accept a string, generate an iframe, inject that string into the new iframe and based on the options, the iframe size can be set or will auto resize once the content of the iframe is loaded.

This plugin allows for javascript/ui controlled ad placement, which means your ui can listen to events like responsive design (media query) breakpoint changes, simulated page load events or any javascript event to trigger an ad load/refresh/unload.

This plugin is currently in production use on [http://www.healthcentral.com](http://www.healthcentral.com).

##How to use:
    var strAd = '<scr'+'ipt src="http://ad.doubleclick.net/ADJ/publisher/..."></scr'+'ipt>'
    $('.AdPlaceholderClass').iframeAdLoad(strAd);

##TODO:
* add css for advertisement label (follows Suit CSS)
* listen/trigger events
* convert this to a more agnostic implementation
* add testing
* better documentation