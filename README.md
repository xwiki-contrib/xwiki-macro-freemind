Introduction
============

This is a macro for displaying Freemind mindmaps in a wiki page. It is published on [http://extensions.xwiki.org/xwiki/bin/view/Extension/Freemind+Macro](http://extensions.xwiki.org/xwiki/bin/view/Extension/Freemind+Macro)

Installation
------------

* Build the XAR with `mvn install`

* Log in the wiki with a user having Administration rights

* Go to the Administration page and select the Import category

* Follow the on-screen instructions to upload the Freemind Macro XAR. You'll find it in the `target` directory.

* Click on the uploaded XAR and follow the instructions.

Usage
-----

Once the XAR is imported you can display a Freemind mindmap in a page by using the `{{freemind map="mapname"/}}` macro, where `mapname` is the name of the attachment containing the mindmap.

The macro supports the following parameters:

* **map**: the name of the attachment containing the mindmap. This parameter is mandatory.

* **width**: the width of the mindmap visor. This parameter is optional and has a default value of 100%

* **height**: the width of the mindmap visor. This parameter is optional and has a default value of 100%


