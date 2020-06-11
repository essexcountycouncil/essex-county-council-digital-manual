---
layout: page
title: Checkbox
---

1. [Home](/essex-service-transformation-playbook/)
2. [Design System](/essex-service-transformation-playbook/Design-system)
3. [Elements and Components](/essex-service-transformation-playbook/Design-system/Elements-and-Components)
4. {{ page.title }}

# {{ page.title }}

<div class="form">
  <div class="group">
    <fieldset>
      <legend>Ask your question?</legend>
      <div class="multiple-choice">
        <input id="telephone" name="checkbox" type="checkbox" value="Telephone">
        <label for="telephone">Telephone</label>
      </div>
      <div class="multiple-choice">
        <input id="email" name="checkbox" type="checkbox" value="Email">
        <label for="email">Email</label>
      </div>
      <div class="multiple-choice">
        <input id="post" name="checkbox" type="checkbox" value="Post">
        <label for="post">Post</label>
      </div>
      <div class="panel js-hidden" id="checkbox-selection">
          This panel is shown if selecting last checkbox
      </div>
    </fieldset>
  </div>
</div>

    <div class="form">
      <div class="group">
        <fieldset>
          <legend>Ask your question?</legend>
          <div class="multiple-choice">
            <input id="telephone" name="checkbox" type="checkbox" value="Telephone">
            <label for="telephone">Telephone</label>
          </div>
          <div class="multiple-choice">
            <input id="email" name="checkbox" type="checkbox" value="Email">
            <label for="email">Email</label>
          </div>
          <div class="multiple-choice">
            <input id="post" name="checkbox" type="checkbox" value="Post">
            <label for="post">Post</label>
          </div>
          <div class="panel js-hidden" id="checkbox-selection">
              This panel is shown if selecting last checkbox
          </div>
        </fieldset>
      </div>
    </div>

## Using checkbox

Checkbox enables users to select more than one choice at a time from a selection of inputs, for examples all items that apply from a list.

If you want users to select just one input at a time, for examples a yes or no answer, use the <a href="radio">radio element</a>

Checkbox is often used as part of a <a href="form">form</a>.

You can avoid having long lists of options by guiding users through with better thought out questions. 

Conditionality allows you to show users additional content or questions to particular users on what they've selected. If you're using this to show lots of content, maybe think about putting it on a separate page. 
