---
layout: page
title: Contents
---

# {{ page.title }}

Use contents to allow users to navigate between a set of related pages.

<nav class="contents" aria-label="Pages in this service">
  <div class="heading"><h2>Contents</h2></div>
  <ol class="list list-number" id="pages-in-this-service">
    <li aria-current="page">Paying for care and support</li>
    <li><a href="#">Financial assessment </a></li>
    <li><a href="#">Personal budget</a></li>
    <li><a href="#">Care charges</a></li>
    <li><a href="#">Ways to pay for your care</a></li>
    <li><a href="#">Paying for a residential home</a></li>
    <li><a href="#">Deferred payment scheme</a></li>
    <li><a href="#">Independent financial advice</a></li>
    <li><a href="#">Direct payments</a></li>
    <li><a href="#">Contact us</a></li>
  </ol>
</nav>

    <nav class="contents" aria-label="pages-in-this-service">
      <div class="heading"><h2>Contents</h2></div>
      <ol class="list list-number" id="pages-in-this-service">
        <li>Paying for care and support</li>
        <li><a href="#">Financial assessment </a></li>
        <li><a href="#">Personal budget</a></li>
        <li><a href="#">Care charges</a></li>
        <li><a href="#">Ways to pay for your care</a></li>
        <li><a href="#">Paying for a residential home</a></li>
        <li><a href="#">Deferred payment scheme</a></li>
        <li><a href="#">Independent financial advice</a></li>
        <li><a href="#">Direct payments</a></li>
        <li><a href="#">Contact us</a></li>
      </ol>
    </nav>

## When to use contents

Use a contents list to allow users to navigate between a small group of related pages to help users find related information, for example a group of pages about paying for care and support. 

## When not use contents

Do not use contents to group pages that are not related, this could confuse users. 

Do not use contents on transactional pages or forms. 

Consider using [buttons](/essex-county-council-digital-manual/Design-system/Elements-and-Components/buttons) or [back](/essex-county-council-digital-manual/Design-system/Elements-and-Components/back) links instead.

## How to use contents

Use the contents at the top of page, just below the title, along with [pagination](/essex-county-council-digital-manual/Design-system/Elements-and-Components/pagination) at the bottom of the page.

Links should be short and descriptive. Long links make the list difficult to scan.

### Accessibility

The contents list is wrapped by a <code><nav></code> element to show that these links are a form of navigation. This <code><nav></code> also has the attribute <code>aria-label</code> with the value <code>Pages in this service</code>. Screen readers will read out this label to identify what type of navigation it is.

If the list item refers to the current page the user is on it should also have the attribute <code>aria-label</code> with the value <code>page</code>. This indicates to screen readers the link represents the page the user is on.
