---
layout: page
title: Textarea
---

# {{ page.title }}

The textarea element enables users to input multiple lines of text.

## Example

<div class="form">
  <div class="group">
    <label for="details">Can you provide more detail?</label>
    <span class="form-hint">Don’t include personal or financial information, such as your credit card details.</span>
    <textarea class="textarea" id="details" name="details" rows="5"></textarea>
  </div>
</div>

    <div class="form">
      <div class="group">
        <label for="details">Can you provide more detail?</label>
        <span class="form-hint">Don’t include personal or financial information, such as your credit card details.</span>
        <textarea class="textarea" id="details" name="details" rows="5"></textarea>
      </div>
    </div>

## When to use this component

This component should be used for when users need to input information that is longer than a single line. For example, leaving feedback or providing supporting information in a form.

It shouldn't be used for single answer inputs, such as email address or National Insurance number.

Before using the textarea element, see if it's better to ask closed questions using <a href="multiple-choice">multiple choice</a> or <a href="inputs">inputs</a>

Textarea is sometimes used as part of the <a href="">form component</a>

## Accessibility

To ensure checkboxes are accessible it is important that the textarea and label are connected so assisstive technologies can recognise they are connected.

To do this ensure the <code>for</code> attribute on the label matches the <code>id</code> attribute on the textarea.

    <label for="details">Can you provide more detail?</label>
      <span class="form-hint">Don’t include personal or financial information, such as your credit card details.</span>
    <textarea class="textarea" id="details" name="details" rows="5"></textarea>

## Content to be published

- Error handling with textareas