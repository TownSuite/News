# News

This repository contains the files for generating the news.townsuite.com content website


Repository Structure
--------------------

 - `_includes` - *special folder* contains snippets that can be included in other pages
 - `_layouts` - *special folder* contains the layouts that are shared between pages. Layouts can be inherited, the root layout is index.html.
 - `_posts` - the output of the generated site is stored here by default, this folder only exists after Jekyll built the site
 - `_drafts` -  place to store pre-published content that will not be built and displayed by the site
 - `_assets` -  contains the main stylesheet and javascript
 - `images` -  stores the images used in pages
 
* Any other folders are most likely user created content

Creating new Content
--------------------
* Find a folder that matches what you want to write
* Create a new markdown (.md) document in `_posts` or `_drafts` depending your requirements
    * please note this file is whitespace sensitive
    * please include proper title, date, description and catagories
    * default layout is post and permalink is not required
* Send a pull request with your change for review.

     ---
     layout: post
     title:  "Sample title"
     date:   2017-01-01 16:56:45
     description: Just a sample post.
     categories:
     - news
     permalink: sample-post
     ---
