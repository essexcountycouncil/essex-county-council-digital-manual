---
layout: page
title: Skip link
---

# {{ page.title }}

The skip link is used to help keyboard only users to skip repeated content.

## Example

To view the skip link. `tab` to ths example, or click inside this example and press `tab`.

	<div id="skiplink-container" role="region" aria-label="skiplink">
	  <div>
	    <a href="#content" class="skiplink" id="skiplink">Skip to main content</a>
	  </div>
	</div>

<div id="skiplink-container" role="region" aria-label="skiplink">
  <div>
    <a href="#content" class="skiplink" id="skiplink">Skip to main content</a>
  </div>
</div>

## When to use a Skip link

Skip links should be used on all pages to skip any repeated content.

Skip links should be used to skip elements that may cause keyboard traps.

## How Skip links work

Some people use the `tab` key on their keyboard to navigate through the links and form elements on a web page. Including a skip lnk gives users the option to bypass the top-level navigation links and jump to the main content on the page.

They can also be used to bypass infinite scrollinig embedded content such as social media feeds that can cause a keyboard trap.


## Using Skip link

The Skip link is displayed at the top of the website and intiially hidden, and only to appear when a user presses `tab` to focus links.

They are used for accessibility reasons, allowing for users to skip to the main `#content` switching across links.