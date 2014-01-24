A Textmate Bundle for PHPStorm to give Laravel Blade Templates Syntax highlighting.

Disclaimer
==========

This is my first stab at creating a bundle and I'm still fairly new with PHPStorm. Blade.tmbundle is based on the Laravel Blade Highlighter by Eric Percifield [here](https://sublime.wbond.net/packages/Laravel%20Blade%20Highlighter here).

Results may vary. Feedback is welcome and encouraged!

Installation
============
* Download and unzip [Blade.tmbundle](https://github.com/outofcontrol/Blade.tmbundle/archive/master.zip). Rename Blade.tmbundle-master to Blade.tmbundle, and place the bundle in a safe place (On OS X ideally in ~/Library/Application Support/TextMate/Bundles so it is also available to TextMate 2).

* Follow the [tutorial](http://confluence.jetbrains.com/display/PhpStorm/TextMate+Bundles+in+PhpStorm) to register Blade.tmbundle in PHPStorm. TextMate bundles require the TextMate bundles support Plugin is active in `Settings->Plugins`. The follow warning can safely be ignored when you activate Blade.tmbundle:

  `Some extensions declared in attached bundles are already used by native file types.`

* Check `Settings->File Types->Files supported via TextMate bundles` to ensure that only *.blade.php is listed. If it is not listed, click on the + button and add it. If you get a warning something to the effect that something will be reassigned, do it. Reassign the extension to this bundle. 

  **Note:** I've found that *.blade.php will appear twice. If you can't get the bundle to work, add *.blade.php a second time.

* You will also need to associate TextMate bundles to your theme in `Settings->TextMate Bundles`, or you may get a horribly ugly looking Blade template. Thanks to [@laravelnews](http://laravel-news.com) and [kennonb](https://github.com/kennonb) for pointing this out.

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