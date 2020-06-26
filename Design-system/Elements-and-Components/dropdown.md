---
layout: page
title: Dropdown
---

# {{ page.title }}

Use select to let users select from a long list. As some users can struggle this functionality, only use as a last resort.

<div class="form">
  <div class="group">
    <label for="sorting" class="form-hint">Sort by</label>
    <select class="form-control" id="sorting" name="sorting">
      <option>Recently published</option>
      <option selected>Recently updated</option>
      <option>Most views</option>
      <option>Most comments</option>
    </select>
  </div>
</div>

    <div class="form">
      <div class="group">
        <label for="sorting" class="form-hint">Sort by</label>
        <select class="form-control" id="sorting" name="sorting">
          <option>Recently published</option>
          <option selected>Recently updated</option>
          <option>Most views</option>
          <option>Most comments</option>
        </select>
      </div>
    </div>

## How to use select

Try using the <a href="/essex-service-transformation-playbook/Design-system/Elements-and-Components/radio">radio</a> or <a href="/essex-service-transformation-playbook/Design-system/Elements-and-Components/checkbox">checkbox</a> elements instead.

It's often used when there is a long list that can't presented in another way, such as a list of countries or languages.

## Content to be published 

- Error handling with select
- Conditionally revealing content
- Select hints
- Accessibility information

<!-- *Note: Be sure to update all label and input attributes with the correct details i.e.*
    
    <label for=""></label>
    <select id="">
    <select naming=""> -->