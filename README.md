# DevNotes Hub Module 02 Final Project

## Project Description

DevNotes Hub is a multi-page tech blog built using only plain HTML—no CSS, no frameworks, and no JavaScript. I created it to share beginner-friendly notes on web basics, accessibility, and Linux workflows while practicing proper page structure, working links across folders, data tables, media, and accessible forms.

## Pages Included

`index.html`  The main home page with an intro to the blog, a workspace photo with a caption, bullet and numbered lists, a short glossary list, and jump links on the same page.
`about.html` Explains why I started the blog, the writing standards I follow, and links to the guest writer form.
`services.html`  Shows the weekly community study and review schedule inside a properly structured data table.
`blog.html` Contains sample tech posts with dates, links to MDN references, and an audio recap player pulling from the `media/` folder.
`contact.html`  Lists editorial contact emails using `mailto:` links and response times.
`pages/application.html`  A page inside a subfolder with a full guest writer application form using built-in HTML validation.

## HTML Features Used

Proper HTML5 page setup (`<!DOCTYPE html>`, `<html lang="en">`, charset, viewport, and page descriptions) on all six pages.
Page layout tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) and headings in order (`<h1>` to `<h3>`).
Text tags and lists (`<p>`, `<strong>`, `<em>`, `<code>`, `<ol>`, `<ul>`, `<dl>`, `<dt>`, `<dd>`).
Different kinds of links: links in the same folder (`about.html`), links into a subfolder (`pages/application.html`), links going back up a folder (`../index.html`), jump links (`#top`, `#latest-highlights`), external links, and email links (`mailto:`).
Images placed inside `<figure>` and `<figcaption>` with real `alt` descriptions, plus an `<audio controls>` player.
A data `<table>` with a `<caption>`, `<thead>`, `<tbody>`, and `<th scope="col">` / `<th scope="row">` headers.
A complete `<form>` grouped with `<fieldset>` and `<legend>`, `<label for="...">` connected to matching `id`s, `text`, `email`, `tel`, `select`, `radio`, `checkbox`, `textarea`, validation rules (`required`, `minlength`, `maxlength`, `pattern`), and a submit button.

## What I Learned

How to keep relative file paths working properly when linking between main pages and a nested page like `pages/application.html` using `../`.
How much structure and keyboard/screen-reader support plain HTML gives you right away without touching CSS or JavaScript.
How helpful the W3C Nu HTML Checker is for spotting small tag mistakes, missing attributes, or syntax issues before turning in work.

## Challenges Encountered

Double-checking every navigation link and image path inside `pages/application.html` so they stepped back out to the main folder (`../`) without leading to broken pages.
Testing all six files in the W3C validator and cleaning up small details until every page passed with zero errors and zero warnings.

## Resources & Media Attributions

Reference guide: [MDN Web Docs HTML & Accessibility](https://developer.mozilla.org/)
HTML checker: [W3C Nu HTML Checker](https://validator.w3.org/nu/)
Images in `images/`: Original developer workspace screenshots / free-to-use images (no private or sensitive info included).
Audio in `media/`: Short voice note recorded by me for testing the audio player.
