# Omeka Classic Tutorial
Created by Brandon Locke and Dawson McCall

## Omeka Classic Overview
* *Omeka Classic* is the name for the single-site, self-hosted Omeka software platform. [*Omeka.net*](http://omeka.net) is a free, hosted version of the single site Omeka platform. [*Omeka-S*](http://omeka.org/s/) an Omeka platform with linked open data and the ability to develop multiple sites from the same installation.
* Omeka is a web-publishing platform for the online display and curation of visual collections and exhibitions.
* Great tool for projects utilizing visual images, physical objects, and material culture items.
* Some of the most importatn Omeka featues include: standards-based metadata and web design, data migration tools, exhibit building, curation and organization of material culture items/collections/exhibits, tagging features, and timeline and Google Maps plugins.
* Good overview video for Omeka here - [Omeka Documentation, 2.0 Overview (Video)](https://vimeo.com/55973380)

## Dublin Core & Omeka
* Dublin Core is a metadata schema (set of terms) used as a common set of descriptors for the presentation of online resources (digital and material).
* Omeka uses the Dublin Core metadata schema in order to help organize, describe, and document the content of your Omeka projects.
* Omeka provides a short description of how you can effectively work with the Dublin Core Schema - [Omeka Documentation, Working with Dublin Core](http://omeka.org/codex/Working_with_Dublin_Core)

## Omeka Organizational Schema
* The most important thing to understand about Omeka is the organizational hierarchy for content that Omeka operates from.
* There are three basic hierarchical groupings for organizing your content within Omeka - Items, Collections, and Exhibits. Each of these builds on or pulls from each other depending on your organizational criteria.
* Items are the individual pieces in your collection.
* Collections are groups of items that have some common trait (theme, time period, artist, etc) that is important for the organization of your project.
* Exhibits are essentially the entire project that you are presenting (made up of individual Items that are grouped into Collection).
* IMPORTANT NOTE - The Exhibit feature has to be added with a plugin (it is easy - just follow the steps in the documentation sheet below at #3 of this section).
* Below are some brief descriptions of these organizational groups:
  1. Items - [Omeka Documentation - Managing Items 2.0](http://omeka.org/codex/Managing_Items_2.0)
  2. Collections - [Omeka Documentation - Managing Collections 2.0](http://omeka.org/codex/Managing_Collections_2.0)
  3. Exhibits - [Omeka Documentation - Exhibits, Plugins/Exhibit Builder 2.0](http://omeka.org/codex/Plugins/ExhibitBuilder_2.0)

## Constructing a Digital Collection

### Adding Items
1. Click on *Items* at the top of the menu on the far left of the screen
2. Click *Add an Item* in the top left corner of the screen - it's a green button
3. There are four different tabs at the top:
  * **Dublin Core** is more descriptive metadata
  * **Item Type Metadata** has metadata that varies based upon the format of the item
  * **Files** allows you to upload any number of files (sound files, video files, photos, PDFs, etc)
  * **Tags** allows you to add tags that enable searching and browsing across different parts of the collections
4. Start filling out your Dublin Core metadata for the item. There is a brief description of what is expected for each field. Click on *Add Input* if you want to add more than one of any field. For example, if you want more than one 'Subject', rather than listing them all in the subject field, add multiple inputs and put one subject term in each field.
3. Add any relevant Item Type Metadata on the next tab. Once you select an item type, additional, specialized fields will appear below.
4. Upload any media files you would like associated with the item.
5. Add any tags you would like, separating multiple tags with a comma.
6. On the right side, check the *Public* box, and hit *add item*. (*Featured* is an option you can select for any items, collections, and exhibits that will allow you to highlight some of your best items/collections/exhibits.)

### Collections
Collections may be used in a variety of contexts that make the most sense for your archive. It is not necessary to follow a traditional interpretation of a collection, say by owner or donor. Items can only belong to one collection, so be sure to take that into consideration before determining your collection scheme

1. Click on the "Collections" tab on the left navigation bar.
2. Any existing collections will be listed here. Click "Add a Collection" and then fill out collection-level Dublin Core metadata.
3. You may associate an item with this collection, and all others you create, when adding or editing an item.
4. Be sure to click "Save Collection" to save your newly-created collection.

### Exhibits
#### Creating an Exhibit
1. Click on *Exhibits* on the left navigation bar.
2. Click *Add an Exhibit* — you'll be asked to give it a title, a slug (the last part of the URL), credits, a description, and any tags you may feel are relevant.
3. Select a theme - you can use a theme that's different from the rest of the Omeka site, but it's probably best to stick with "Current Public Theme"
4. An exhibit summary page displays the exhibit description and navigation options. If this box is unchecked, users navigating to the exhibit will start on the first page of the exhibit.

#### Constructing an Exhibit
Exhibits are comprised of pages (and sub-pages) that are composed of Omeka items, text, and uploaded media files. When you add a new page, you give it a title and slug, and then begin to build out content blocks to make up the page.

Each page can have an unlimited number of *content blocks* that take one of several forms:

* The **File with Text** block allows you to pair fullsize or thumbnail files of your items with a block of text. The item files will all be the same size. Text will appear either to the right or left of the item(s). You can use a single item file paired with text, or have multiple item files to the right or left of a block of text.
* The **Gallery** block creates a gallery of item files, generally large square thumbnails. You can add text to the gallery, which will display left or right of the gallery. In a gallery block, you can specify a showcase file, which will appear fullsize either to the right or left of the text. The other gallery images can be placed below the showcase image or beside it, over the text.
* The **Text** block allows you to create a section of text which spans the width of the entire page.

Once pages are created, you can click and drag the pages around to reorder them and make pages sub-pages of others.

*Other plugins may have additional content types that you can import*

## Design and Finishing Touches
### Themes
While most really good Omeka projects include heavy CSS and PHP customization, there are several things you can do to make the project look a lot better. The themes give you a number of good jumping-off points. It usually helps to have at least a few items in and an exhibit created before changing themes - otherwise it can be difficult to discern exactly what the project looks like.

To change the theme, click on 'Appearance' at the top of the screen, and you'll go directly to the theme page. You can easily test any of them out by clicking 'Use this theme' and then looking at the public view of the project. Each Omeka install will have all of the themes that are available and have been vetted by the developers of Omeka.

### Configuring a Theme
Each theme will have a 'Configure Theme' button once it is selected. Configurations let you make choices about the look of your site, including adding a logo and homepage text, managing featured elements, and adding footer text. The configuration settings you make are unique to each theme and will be saved with that theme. Not all themes have the same configuration settings.

To configure your theme, click the “Configure Theme” button below the theme graphic to customize your site. While not all themes have the same configuration settings, most will have the following two sections:

**Header and Footer configuration options are:**

* Logo file. You may upload a logo file that will replace the site title in the header of the theme. Recommended maximum width for the logo is 500px.
* Header image. Upload an image file that will display across the top of each of your public website's pages, usually below the navigation bar.
* Background image. Upload an image file that will display, tiled, in the background of each of your site's pages.
* Footer text. An HTML-enabled text box where you can enter text for a site footer to appear on every page.
* Display copyright in footer. Check this box if you wish to display your site’s copyright information in the footer. Site copyright information is found in the General Settings section.
* Use Advanced Site-wide search. Check this box to allow public-side site visitors to search the whole site, including items, collections, and files, and to use boolean methods when searching.

**Homepage configuration options:**

* Display Featured Item. Check this box if you wish to show a featured item on the homepage.
* Display Featured Collection. Check this box if you wish to show a featured collection on the homepage.
* Display Featured Exhibit. Check this box if you wish to show a featured exhibit on the homepage.
* Homepage Recent Items. Choose the number of recent items to be displayed on the homepage. These will appear in the order in which they were mostly recently added to the archive.
* Homepage Text. Add some text to be displayed on your homepage above the Featured Items. This is a good place to add a very short tagline or description of your site.

Save longer explanations for an About page.

Remember to save changes.

### Navigation
You can customize the navigation bar by clicking 'Appearance' at the top of the screen, and then clicking on the 'Navigation' tab. You can rename or remove the default links from the bar, add links to specific Collections, Exhibits, or Simple Pages, or add external links on this screen.

### Changing the default home page
You can change the default home page by clicking 'Appearance' at the top of the screen, and then clicking on the 'Navigation' tab. On the right, there is a dropdown where you can select the default home page. If the page you want to be your home page is not listed, you need to add the link to the navigation list (you can uncheck it so that it does not appear in the menu) and then select that as your home page.


## Other Useful Omeka Video Tutorials & Documentation
- [Omeka Youtube Tutorial, Digital Liberal Arts @ Mac - Items](https://www.youtube.com/watch?v=R9DlnSIYdCU)
- [Omeka Documentation - Managing Tags](http://omeka.org/codex/Managing_Tags_2.0)
- [Omeka Documentation - Managing Themes](http://omeka.org/codex/Managing_Themes_2.0)
- [Omeka Documentation - Managing Navigation](http://omeka.org/codex/Managing_Navigation_2.0)

-----
### Return to [LEADR's Resources list](https://github.com/leadr-msu/Resources)
