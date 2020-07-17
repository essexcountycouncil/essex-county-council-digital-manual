---
layout: page
title: Header
---

# {{ page.title }}

Use the header to show users they are on an Essex County Council website and to provide tools to help them find what they need.

We have 2 versions of the header

- the [deault header](#default-header)
- the [navigation header](#navigation-header)

## Default header

### When to use the default header

Use the default header for Essex County Council web pages that use the Essex.gov.uk domain.

<header class="header-background">
  <div class="header">
    <div class="nav">
      <div class="logo-wrap">
        <a href="/" class="logo-text seax">
          <img src="{{ '/assets/images/seax.png' | absolute_url }}" width="36" height="30" alt="Essex County Council logo">
          Essex.gov.uk
        </a>
      </div>
    </div>
  </div>
</header>

    <header class="header-background">
      <div class="header">
        <div class="nav">
          <div class="logo-wrap">
            <a href="/" class="logo-text seax">
              <img src="/assets/images/seax.png" width="36" height="30" alt="Essex County Council logo">
              Essex.gov.uk
            </a>
          </div>
        </div>
      </div>
    </header>

## Navigation header

### When to use the navigation header

Use the navigation header to add navigational assistance to users on Essex Councty Council websites.

<header class="header-background">
  <div class="header">
    <div class="nav">
      <div class="logo-wrap">
        <a href="/" class="logo-text seax">
          <img src="{{ '/assets/images/seax.png' | absolute_url }}" width="36" height="30" alt="Essex County Council logo">
          Essex.gov.uk
        </a>
      </div>
       <ul class="nav-links">
            <li><a href="#">Link A</a></li>
            <li><a href="#">Link B</a></li>
            <li><a href="#">Link C</a></li>
          </ul>   
    </div>                     
  </div>
</header>

    <header class="header-background">
      <div class="header">
        <div class="nav">
          <div class="logo-wrap">
            <a href="/" class="logo-text seax">
              <img src="/assets/images/seax.png" width="36" height="30" alt="Essex County Council logo">
              Essex.gov.uk
            </a>
          </div>
          <ul class="nav-links">
            <li><a href="#">Link A</a></li>
            <li><a href="#">Link B</a></li>
            <li><a href="#">Link C</a></li>
          </ul>   
        </div>                     
      </div>
    </header>

## When not to use the header

Do not use a header unless your websie is part of the Essex.gov.uk domain.

## How to use the header

The header is displayed at the top of every page and is consistent across the entire site.

It should display the site's identity and branding, making it clear to the user what website they are on.

## Content to be added

- Logo with header
- Accessibility