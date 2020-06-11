---
layout: page
title: Dropdown
---

1. [Home](/essex-service-transformation-playbook/)
2. [Design System](/essex-service-transformation-playbook/Design-system)
3. [Elements and Components](/essex-service-transformation-playbook/Design-system/Elements-and-Components)
4. {{ page.title }}

# {{ page.title }}

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

## Using dropdown

Dropdown should only be used if there is no other alternative as some users can struggle with the functionality.

Try using the <a href="radio">radio</a> or <a href="checkbox">checkbox</a> elements instead.

It's often used when there is a long list that can't presented in another way, such as a list of countries or languages.

*Note: Be sure to update all label and input attributes with the correct details i.e.*
    
    <label for=""></label>
    <select id="">
    <select naming="">