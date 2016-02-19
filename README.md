# bugzilla-bidi

This project provides Bi-directional text support for some default (English) templates of the [Bugzilla](http://www.bugzilla.org/) bug system.
It allows the correct display of right-to-left text in selected fields, like bug title, comments and description, while still using the default English user interface.

The solution provided here relies on browsers support for the HTML5
[dir="auto"](http://www.w3.org/html/wg/drafts/html/master/dom.html#the-dir-attribute) feature.
Users with old browsers will not benefit from this new feature, but it should not affect them otherwise.

## Installation

To use it as [site customization](https://bugzilla.readthedocs.org/en/5.0/integrating/index.html), follow These Steps:

1. Download the version that correspond to your Bugzilla installation (i.e. 5.0)
2. Extract the downloaded archive.
3. Copy the folder named **custom** from the extracted archive to the **template/en** folder of your Bugzilla installation, alongside the folder named **default**.
4. Run **checkconfig.pl**


## Remarks

* Tested with Budzilla 5.0.
* Older version can be found on my [Sourceforge](https://sourceforge.net/projects/bugzilla-bidi/) site.
* If your site already have custom en templates, you will have to merge the files in custom folder mannualy.
