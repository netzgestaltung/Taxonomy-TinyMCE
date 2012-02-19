﻿Taxonomy TinyMCE
=============

## Description

This Wordpress plugin replaces a taxonomy term description textarea with the buildin TinyMCE WYSIWYG.  

**Contributors**:

* Jaime Martinez ( [@jmslbam](http://twitter.com/jmslbam ) / [jaimemartinez.nl](http://www.jaimemartinez.nl/) )

## Notes

- This plugin needs at least WordPress 3.3 to work as it uses the new wp_editor call introduced in WP 3.3.
- This plugin is a inspired by [CategoryTinyMCE](http://wordpress.org/extend/plugins/categorytinymce/).

## Installation

1. Upload Taxonomy-TinyMCE folder to the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to your custom taxonomy edit pages and start to write!

## Frequently Asked Questions

### Why not use Category TincyMCE

I want to, but had to make to much changes to still call it CategoryTinyMCE. Hope we can combine powers.  
Also a category is build in [custom taxonomy](http://codex.wordpress.org/Taxonomies).

## Changelog

= 1.0 =
* Migrated from Category TinyMCE to Taxonomy TinyMCE

## To Do
- Check for minimal Wordpress version 3.3.
- Show tiny_mce on overview page 'edit-tag', but it needs some change in the core or Wordpress.
inline-edit-tags.js needs to have .live() to work with TinyMCE.
I was thinking about so submiting a request to add this, but I first have to learn my way in to WP svn / ideas / trac etc. Any help?
- Implement options page.