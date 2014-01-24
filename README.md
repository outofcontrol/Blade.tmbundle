A Textmate Bundle for PHPStorm to give Laravel Blade Templates Syntax highlighting.

Disclaimer
==========

This is my first stab at creating a bundle and I'm still fairly new with PHPStorm. Blade.tmbundle is based on the Laravel Blade Highlighter by Eric Percifield [here](https://sublime.wbond.net/packages/Laravel%20Blade%20Highlighter here).

Results may vary. Feedback is welcome and encouraged!

Installation
============
* Download [this repository](https://github.com/outofcontrol/Blade.tmbundle/archive/master.zip) to your machine, unzip, remove -master from the filename, and place the Blade.tmbundle in a happy place where it won't get deleted. I've placed mine in ~/Library/Application Support/Textmate/Bundles so it is also available to TextMate 2. 

* Follow the tutorial [here](http://confluence.jetbrains.com/display/PhpStorm/TextMate+Bundles+in+PhpStorm) to register the Blade and html bundles with PHPStorm. 

* When you activate the Blade.tmbundle, you will see this warning which can be safely ignored:

  `Some extensions declared in attached bundles are already used by native file types.`

* Check Settings->File Types->Files supported via TextMate bundles and ensure that only *.blade.php is listed. If it is not listed, click on the + button and add it. If you get a warning something to the effect that something will be reassigned, do it. Reassign the extension to this bundle. 

Changes
=======
* January 24, 2014: 
  - Removed HTML Bundle requirement
  - Add improved PHP highlighting
  - Bundle works with light themes now
  - Tested on PHPStorm 7.1 with OS X and Fedora 17
  - Renamed from LaravelBlade to Blade

ToDo
====
* Add auto complete