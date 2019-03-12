# Riak Community Website
This repo contains the files needed to create the Riak Community website on a clean WordPress base.

Initial version will require [Wordpress 5.1](https://wordpress.org/download/) with the latest security patches applied.

# File structure

## Content
This [folder](./content/) will contain the docs, guides, static pages, etc... The files will be Markdown format, and all images

### Docs
This [folder](./content/docs/) will contain the docs in easily editable Markdown format (as they are currently formatted in riak-docs). The idea is not to change the historical docs, but make the importer sort them out for us.

### Guides
This [folder](./content/guides/) will contain the gudies and technical blog posts from the old Basho website in Markdown format.

### Downloads
This [folder](./content/downloads/) will contain a central location to provide downloads for all projects. To be in Markdown format. 

## Wordpress Theme
This [folder](./wordpress-theme/) will contain the WordPress theme (PHP files, CSS, JavaScript, other reosurces) used for the look-and-feel for the site.

## Wordpress Plugins
This [folder](./wordpress-plugins/) will contain any customised plugins used for the site to work.

### Content Importer
This [folder](./wordpress-plugins/content-importer/) will contain a plugin to import content held in GitHub in Markdown format to Wordpress Pages in HTML stored in the WordPress database. This will take the contents of the /content folder and process it to add new pages, update existing pages and archive dead pages.

## Discourse Theme
This [folder](./discoruse-theme/) will contain the Discourse theme used for the look-and-feel of the Discourse server used as a forum.

## Helper Scripts
This [folder](./helper-scripts/) will contain any additional scripts/programs used.
