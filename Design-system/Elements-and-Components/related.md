---
layout: page
title: Related
---

# {{ page.title }}

The related content component is a vertical list of links, signposting users to other content that might be useful.

<aside class="related">
  <nav aria-labelledby="related-name">
  <h3 id="related-name">Related content</h3>
    <ul id="related-navigation">
      <li><a href="#">Start your financial assessment</a></li>
      <li><a href="#">Independent financial advice</a></li>
      <li><a href="#">Pay your care invoice</a></li>
    </ul>
  </nav>
</aside>

    <aside class="related">
      <nav aria-labelledby="related-name">
      <h3 id="related-name">Related content</h3>
        <ul id="related-navigation">
          <li><a href="#">Start your financial assessment</a></li>
          <li><a href="#">Independent financial advice</a></li>
          <li><a href="#">Pay your care invoice</a></li>
        </ul>
      </nav>
    </aside>

## When to use related

Use related to signpost users to content that may be related or useful.

## When not to use related

Do not use related to group sets of pages.

## How to use related

Related content links shouldn't be the same as the links used in the page <a href="contents">contents</a> or in the <a href="breadcrumbs">breadcrumbs</a>. They should signpost users to relevant content held in different sections of the website or on external websites.

Related content should be positioned on the right side of a page or at the bottom, below the main body of content.

### Accessibility

Use the <code>aria-labelledby</code> attribute to label the navigation. Ensure the attribute matches the <code>id</code> of the <code><h3></code> element. This will identify to screen readers that this heading relates to the navigition.
