# Intro to Omeka


## Backgrounds
_Explain the basics of how database-driven web publishing systems work_

* Open Source software
	* Understanding Web Applications
	* How database content becomes screen content
	* Modularity – plugins and themes


## What is Omeka?

* NOT an archive
* NOT a DAMS
* IS web publishing
	* Omeka self-hosted vs Omeka.net

## Omeka vs WordPress vs Drupal
_Compare the strengths and weaknesses of some web publishing systems_

* WP
	* Up and running quickly. Individual reverse-chronological posts and pages
* Drupal
	* Longer setup and planning time
	* Structured connections between custom content types
* Omeka
	* Metadata-centric on items and custom item types
	* With Exhibit Builder, narratives around items

## Omeka Example Sites
_Examples of what can be done with Omeka_

* [Florida Memory](http://www.floridamemory.com)
	* Exhibits and Collections
	* Heavily custom-themed
* [Lincoln at 200](http://lincolnat200.org)
	* Exhibits and Collections
	* Heavily custom-themed
* [Wiki Loves Art Nouveau (Europeana)](http://exhibitions.europeana.eu/exhibits/show/wiki-loves-art-nouveau/)
	* Collections
	* Heavily custom-themed
* [Gothic Past](http://gothicpast.com)
	* Exhibits and Collections
	* Mapped items
* [Fredericksburg: City of Hospitals](http://projects.umwhistory.org/cwh)
	* Teaching site -- built by undergraduate students
	* Exhibits and Collections
* [Hurricane Digital Memory Bank](http://hurricanearchive.org)
	* Contributions
* Exhibit-based vs Collection-based sites

## Items, Files, and Dublin Core Metadata
_Explain the basic steps of creating content in Omeka._

### Activities
_Walk through the process of adding an item and a file_

Sample files if people didn't bring them are in sample_files folder

* Create some Items
	* Add Files to Item (Add Files in order, absent other plugins)
	* Add DC metadata
* Add DC metadata to a file

### Changes coming in Omeka 2.0 (Fall 2012)

* Completely new admin interface

## Item Types and Custom Item Types
_Explain that "item" is to be taken very generically, and can refer to many types of content, with different sets of metadata._

### Activities

* Change some of the created items into appropriate Item Types (pdf => Document, mark-sample => Person) with appropriate metadata
* Edit an Item Type to add or remove fields (e.g., add Transcriber to Document?)
* Create a "Dataset" item type (.csv or .xls file)
	* Possible discussion of when and why to diverge from Dublin Core



## Elements and Element Sets
_Explain the system of Element Sets and Elements (metadata fields) in Omeka_

* Dublin Core
* The Item Type Element Set

## Site Building
_Explain how to use tags, exhibits, collections, and pages to build a site_

* Tags
* Exhibits
* Collections
* Simple Pages


## Pages and Collections
_Explain how to use pages and collections to build a site_

* "About" and other pages
* Managing Collections
	* Items belong to only one collection (absent other plugins)

### Activities

* Edit the About page
* Add child pages to the About page
* Add a collection, and add item(s) to it


## Exhibits
_Explain the details of how to use exhibits to build a site_

* Exhibits provide a narrative and interpretation around items
* Exhibit-Section-Page structure
	* Choose a page layout
	* Add items to pages
	* Add narrative

### Activities

* Create an exhibit, a section, and a page
* Add item(s) to a page
* Create some text about the item(s)

### Changes coming in Omeka 2.0 (Fall 2012)

* Exhibit Builder pre-2.0 requires a section level between exhibits and pages. That goes away in 2.0. Instead, exhibits can have three levels of child pages. Existing sections will be converted to parent pages containing only the text of the section's description.

* Exhibit Builder 2.0 will allow you to either choose a predefined layout, or create a customized one by choosing 1-3 rows and columns, and defining content for the "panes" generated by that grid (tentative plan as of mid-May 2012)



## Settings Page
_Explain where to look to change theme, activate plugins, manage users_ 

* General Settings
	* Derivative images sizes
	* Items per page
* Activate plugins
* Change Themes
* Manage Users
* Security Settings

### Activities

* Create a new user
* Activate Simple Pages plugin
* Change theme to Seasons
* Change the number of items displayed per page


## Theme Configurations
_Explain how the site can be customized through theme configuration settings_

### Activities

* Remove the link to Collections from header
* Activate Simple pages, create a "Further Reading" page, and add it to the header


## Where to go for help, info and updates, and how to contribute

* [Forums](http://omeka.org/forums)
* [Documentation](http://omeka.org/codex)
* [Recipes](http://omeka.org/codex#Recipes)
* [Dev list](http://groups.google.com/group/omeka-dev)
* Issues and forks on [GitHub](http://github.com/omeka/Omeka)
* Twitter: [@omeka](http://twitter.com/omeka)

## Some Plugins

* MyOmeka
	* To be replaced Fall or Winter 2012
	* Allows public to annotate items and create simple "posters" of their favorites
* Dublin Core Extended
	* Adds Dublin Core refinements to available metadata
* Collection Tree
	* Allows you to create nested collections
* Item Order
	* Allows you to change the order of items in a collection
* Commenting
	* Allows users to comment on items, collections, and more (with some theme work)
* Dropbox
	* Allows batch importing of files
* CSV Import
	* Allows importing items from a CSV file
* OAI-PMH Harvester
	* Allows importing from an OAI-PMH repository
* OAI-PMH Repository
	* Turns your Omeka site into an OAI-PMH repository
* Simple Vocab
	* Create a controlled vocabulary on metadata fields
* Search By Metadata
	* Turns metadata field text into links -- best practice is to use in conjunction with Simple Vocab


## Changes coming in Omeka 2.0 (Fall 2012)

* Completely and awesomely redesigned admin interface

* Exhibit Builder pre-2.0 requires a section level between exhibits and pages. That goes away in 2.0. Instead, exhibits can have three levels of child pages. Existing sections will be converted to parent pages containing only the text of the section's description.

* Exhibit Builder 2.0 will allow you to either choose a predefined layout, or create a customized one by choosing 1-3 rows and columns, and defining content for the "panes" generated by that grid (tentative plan as of mid-May 2012)



