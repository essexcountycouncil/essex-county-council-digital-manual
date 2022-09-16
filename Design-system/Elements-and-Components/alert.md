---
layout: page
title: Alert
---

# {{ page.title }}

Use alerts to inform or warn users of a temporary situation that may impact  them accessing council services. They should be displayed at the top of the main body of content.

We have 3 types of alert that we use on the Essex County Council website (Essex.gov.uk)

- the [information alert](#information)
- the [warning alert](#warning)
- the [error alert](#error)

## Information

### When to use the information alert

Information alerts are used to direct a user’s attention to important information. This could include:

- changes to a regular council service

<div class="alert info" id="tab-two">
  <div class="alert-icon">
    <span class="fas fa-info-circle" aria-label="information" role="img"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are updating our system</div>
    <p>We have been doing lots of research and you have helped us update this service.</p>
    <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
  </div>
</div>

    <div class="alert info" id="tab-two">
      <div class="alert-icon">
        <span class="fas fa-info-circle" aria-label="information" role="img"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">We are updating our system</div>
        <p>We have been doing lots of research and you have helped us update this service.</p>
        <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
      </div>
    </div>

## Warning

### When to use the warning alert

Warning alerts are used to prepare users for a variety of real world issues. This could include:

- adverse weather information

<div class="alert warning" id="tab-three">
  <div class="alert-icon">
    <span class="fas fa-exclamation-triangle"  aria-label="warning" role="img"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">School closures</div>
    <p>Some schools in Essex are closed due to severe weather. <a href="#">Check if your child's school is closed</a></p>
    <button class="text" type="button" onclick="toggle_visibility('tab-three');">Hide this message</button>
  </div>
</div>

    <div class="alert warning" id="tab-three">
      <div class="alert-icon">
        <span class="fas fa-exclamation-triangle" aria-label="warning" role="img"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">School closures</div>
        <p>Some schools in Essex are closed due to severe weather. <a href="#">Check if your child's school is closed</a></p>
        <button class="text" type="button" onclick="toggle_visibility('tab-three');">Hide this message</button>
      </div>
    </div>

## Error

### When to use the error alert

Error alerts are used to direct a user’s attention to important system errors. This could include:

- technical problems or maintenance on the website

<div class="alert error" id="tab-one">
  <div class="alert-icon">
    <span class="fas fa-exclamation-circle" aria-label="error" role="img"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are experiencing some issues</div>
    <p>You may experience some issues with our website. Please bare with us while we resolve the issue.</p>
    <button class="text" type="button" onclick="toggle_visibility('tab-one');">Hide this message</button>
  </div>
</div>

    <div class="alert error" id="tab-one">
      <div class="alert-icon">
        <span class="fas fa-exclamation-circle" aria-label="error" role="img"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">We are experiencing some issues</div>
        <p>You may experience some issues with our website. Please bare with us while we resolve the issue.</p>
        <button class="text" type="button" onclick="toggle_visibility('tab-one');">Hide this message</button>
      </div>
    </div>

## How to use alerts

An alert can be displayed on the homepage or on lower level pages, depending on the topic and severity. They should always:

- be clear and concise and link to another page with further information if necessary
- be located at the top of the main body of content

They shouldn't be used:

- within paragraphs of text
- more than once per page