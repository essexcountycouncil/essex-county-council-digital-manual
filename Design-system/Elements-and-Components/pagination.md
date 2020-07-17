---
layout: page
title: Pagination
---

# {{ page.title }}

Use pagination to allow users to navigate between a set of related pages.

<nav class="pagination" aria-label="pagination">
  <ul>
    <li class="prev">
      <a href="#">
        <span class="pagination-item">
          <span class="fas fa-arrow-left"></span>Previous
        </span>
        <span>Paying for care and support</span>
      </a>
    </li>
    <li class="next">
      <a href="#">
        <span class="pagination-item">
          <span class="fas fa-arrow-right"></span>Next
        </span>
        <span>Personal budget</span>
      </a>
    </li>
  </ul>
</nav>

    <nav class="pagination" aria-label="pagination">
      <ul>
        <li class="prev">
          <a href="#">
            <span class="pagination-item">
              <span class="fas fa-arrow-left"></span>Previous
            </span>
            <span>Paying for care and support</span>
          </a>
        </li>
        <li class="next">
          <a href="#">
            <span class="pagination-item">
              <span class="fas fa-arrow-right"></span>Next
            </span>
            <span>Personal budget</span>
          </a>
        </li>
      </ul>
    </nav>

## When to use pagination

Use paginationto allow users to navigate between a small group of related pages to help users find related information, for example a group of pages about paying for care and support. 

## When not use pagination

Do not use pagination on pages that are not related, this could confuse users. 

Do not use pagination on transactional pages or forms. 

Consider using [buttons](/essex-county-council-digital-manual/Design-system/Elements-and-Components/buttons) or [back](/essex-county-council-digital-manual/Design-system/Elements-and-Components/back) links instead.

## How to use pagination

Use pagination at the bottom of the page, along with [contents](/essex-county-council-digital-manual/Design-system/Elements-and-Components/contents) at the top of the page just below the title.

Use the [left arrow]() along with the word "Previous" and a link to the previous page. Use the [right arrow]() along with the word "Next" and a link to the next page. Use the smae page titles that are used on the contents.

## Accessibility

The pagination component incorporates the <code><nav></code> element to show that the links are a type of navigation. This <code><nav></code> also has the attribute <code>aria-label</code> with the value <code>Pagination</code>. Screen readers will read out this label to identify what type of navigation it is.
