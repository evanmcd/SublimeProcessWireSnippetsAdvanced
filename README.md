Sublime ProcessWire Snippets - Advanced
==================================

A collection of advanced [ProcessWire](http://www.processwire.com) Snippets for Sublime Text 2.  These are based on the [ProcessWire2+ Cheatsheet version 1.1](http://cheatsheet.processwire.com) with the Advanced setting on.

## Installation
This package contains snippets ONLY for the snippets marked Advanced in the cheatsheet.  You'll want to have the [Basic Snippet Collection](https://github.com/evanmcd/SublimeProcessWireSnippetsBasic) as a baseline before installing this set, as the Basic set provides the most commonly used API calls ($pages->find(), etc.).

If you're using Git, the best method is to clone this repository to your ST Packages folder. (on Mac, it's here: /Users/your_username/Library/Application Support/Sublime Text 2/Packages/).

You can also [download the zip file](https://github.com/evanmcd/SublimeProcessWireSnippetsAdvanced/archive/master.zip) and unzip into the Packages folder.

Either way, I would recommend creating a ProcessWire subfolder as there are more than 200 files.

I'm looking into getting it into the excellent [Package Control](https://github.com/wbond/sublime_package_control) which would let you install right from ST.

## Usage notes
The best way to trigger the snippets is to just start typing a ProcessWire object, like $pages.  You'll see a list of the matches, like $pages->find() and $pages->get().  If you know what you want, you could keep typing the specific method like this $pagesfind - selecting the snippet will present you with the proper PW syntax.

For now, entering a command like this $pages-> doesn't work. I'm still figuring out how to work with the > character in snippets.


## Coming updates
I'm looking into the best way to add important bits of documentation for the less well known commands.  For now, there isn't any documentation in the snippets.

Hope this speeds up your already speedy site development with ProcessWire.  :)

I'm [evanmcd](https://twitter.com/evanmcd) on Twitter - best way to reach me is there if you have any questions or comments.


