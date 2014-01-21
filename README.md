A Textmate Bundle for Laravel Blade Templates

Disclaimer
==========

This is my first stab at creating a bundle and I'm still fairly new with PHPStorm. Feedback is encouraged!

This bundle is based heavily on the Laravel Blade Highlighter by Eric Percifield found [here](https://sublime.wbond.net/packages/Laravel%20Blade%20Highlighter here). I simply cleaned up the tmbundle and created a new syntactically correct version in TextMate. 

Requirements
============
In order to have both Blade template syntax highlighting and HTML highlighting work together, you will need the html.tmbundle from [here](https://github.com/textmate/html.tmbundle).

Installation
============
Download [this repository](https://github.com/outofcontrol/Blade.tmbundle/archive/master.zip) to your machine, unzip and place the Blade.tmbundle in a happy place where it won't get deleted. I've placed mine in ~/Library/Application Support/Textmate/Bundles.

Next, follow the tutorial [here](http://confluence.jetbrains.com/display/PhpStorm/TextMate+Bundles+in+PhpStorm) to register the Blade and html bundles with PHPStorm. 

When you activate the Blade.tmbundle, you will see a warning in PHPStorm and the Apply button will not become active. 

`Some extensions declared in attached bundles are already used by native file types.`

We are trying to register a file type (*.blade.php) which is already registered through PHP (*.php). Click on Okay, and then restart PHPStorm. If all went well, you should now have Syntax highlighting in your Blade templates.
