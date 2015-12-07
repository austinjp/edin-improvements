# Edin improvements

I love the free [Edin theme](https://theme.wordpress.com/themes/edin/) for [Wordpress](https://wordpress.com). However I have found I need to make the same tweaks to it every time I use it. This repository keeps that all in one place, mainly for my convenience.

## Remove front-page URL from sub-page URLs

Edin's grid layout is a good choice for a front page. Create a page, call it "front page" or similar, and change it to type "Grid". Go to "Settings > Reading" and use that page as a static front page. Create new pages with the front page as a parent. They should now appear as items in a grid on the front page.

However the grid layout requires making sub-pages, which Wordpress gives URLs like `http://www.example.com/front-page/sub-page` whereas I prefer `http://www.example.com/sub-page`. Fortunately this is simple to fix by installing the [Custom Permalinks plugin](https://wordpress.org/plugins/custom-permalinks/). After installing check "Settings > Permalinks" are set to "Post name" and ensure `.htaccess` is writable.

## Remove page titles

Install the [Toggle the Title](https://wordpress.org/plugins/toggle-the-title/) plugin. This removes titles from pages, but not posts. It actually removes the HTML rather than just hiding it with CSS. In "Settings > Title Toggler" set it to remove all titles from all pages.

## Retain HTML in front page grid items

## Align images

## Alter text in footer
