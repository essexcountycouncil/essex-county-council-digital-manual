---
layout: page
title: External link
---

# {{ page.title }}

Use external links to link to other websites or downloadable documents.

There are 3 types of external links:

- [Open webpage in a new tab](#new-tab)
- [Open webpage in current tab](#current-tab)
- [Open or download a document](#documents)

## New tab

Use this method to open a webpage from an external website in a new tab.

If clicking this link <a href="#" rel="external" class="external-link" target="_blank">a new tab<span class="visually-hidden">Opening a new tab from an external website</span></a> will open from an external website.

	<a href="#" rel="external" class="external-link" target="_blank">a new tab<span class="visually-hidden">Opening a new tab from an external website</span></a>

## Current tab

Use this method to open a webpage from an external website in the current tab.

If clicking this link <a href="https://www.google.com" rel="external" class="external-link">your browser tab is replaced<span class="visually-hidden">Replacing your browser tab with an external website</span></a> by an external website.

	<a href="#" rel="external" class="external-link">your browser tab is replaced<span class="visually-hidden">Replacing your browser tab with an external website</span></a>

## Documents

Use this method to open or download a document frok this website.

If clicking this link you will <a href="/public/images/test-pdf-file.pdf" rel="external" class="external-file-link">download or open a file (PDF)<span class="visually-hidden">Clicking this will download or open a PDF</span></a> from this website.

	<a href="/public/images/test-pdf-file.pdf" rel="external" class="external-file-link">download or open a file (PDF)<span class="visually-hidden">Clicking this will download or open a PDF</span></a>.

## Using External link

The important thing is ensuring users with screen reader and/or with cognitive disabilities are aware a new browser tab has opened or their browser tab has been replaced with an external site.

We also need to consider how this is communicated to all users through the use of icon and supportive text.

### Further thoughts

There can be some confusion and inconsistency around the use of external link <a href="#" rel="external" class="external-link">iconography</a>. In some cases websites show this when the browserr opens a new tab, others when it is replacing the current tab with an external website.

Currently we are using it for both cases, external tab and tab replacement, to show indication of the browser tab state changing.