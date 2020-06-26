---
layout: page
title: Checkbox
---

# {{ page.title }}

Checkbox enables users to select more than one choice at a time from a selection of inputs, for examples all items that apply from a list.

<div class="form">
  <div class="group">
    <fieldset>
      <legend>Ask your question?</legend>
      <div class="multiple-choice">
        <input id="telephone" name="telephone" type="checkbox" value="Telephone">
        <label for="telephone">Telephone</label>
      </div>
      <div class="multiple-choice">
        <input id="email" name="email" type="checkbox" value="Email">
        <label for="email">Email</label>
      </div>
      <div class="multiple-choice">
        <input id="post" name="post" type="checkbox" value="Post">
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
            <input id="telephone" name="telephone" type="checkbox" value="Telephone">
            <label for="telephone">Telephone</label>
          </div>
          <div class="multiple-choice">
            <input id="email" name="checkemailbox" type="checkbox" value="Email">
            <label for="email">Email</label>
          </div>
          <div class="multiple-choice">
            <input id="post" name="post" type="checkbox" value="Post">
            <label for="post">Post</label>
          </div>
          <div class="panel js-hidden" id="checkbox-selection">
              This panel is shown if selecting last checkbox
          </div>
        </fieldset>
      </div>
    </div>

## When to use checkboxes

Use checkboxes to give users the ability to:

- select multiple options from a list
- toggle an option on or off

## When not to use a checkbox

If you want users to select just one option from a selection, for examples a yes or no answer, use the <a href="radio">radio</a> element.

## How to use checkboxes

Checkboxes should be grouped together in a <fieldset> to help users understand they are related with a <legend> that describes the group clearly.

### Accessibility

To ensure checkboxes are accessible it is important that the input and label are connected so assisstive technologies can recognise they are connected.  

        <input id="post" name="post" type="checkbox" value="Post">
        <label for="post">Post</label>

## Content to be published 

- Error handling with checkboxes
- Conditionally revealing content
- Checkbox hints

<!-- Checkbox is often used as part of a <a href="form">form</a>.

You can avoid having long lists of options by guiding users through with better thought out questions. 

Conditionality allows you to show users additional content or questions to particular users on what they've selected. If you're using this to show lots of content, maybe think about putting it on a separate page.  -->
