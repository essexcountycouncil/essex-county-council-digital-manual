---
layout: page
title: Using website alerts
---

# Using website alerts

## What are they?

An alert informs or warns users of a temporary situation that may have an impact on them accessing a council service (either online or offline).

They are displayed at the top of web pages, above the main body of content.

## When to use an alert

Alerts should be used for:

- a temporary period - usually for a few hours or days
- critical information that prevents or alters users accessing a council service

Examples of alerts include:

- school closures
- severe weather resulting in road closures
- a technical error with a website, transaction or high-volume phone line
- scheduled system downtime for online application portals like the [Education Portal](https://emsonline.essexcc.gov.uk/CitizenPortal_LIVE/Account/Login?ReturnUrl=/CitizenPortal_LIVE/) or the PARIS payment service

### Using alerts in the main body of content

There may be instances where you need an alert for a longer period of time, for example, a school consultation is closed for comment. On [essex.gov.uk](https://www.essex.gov.uk/) you can use inline alert within an information or section page for this. You can remove the alert when the final outcome is available.  

## When not to use an alert

Alerts should not be used for:

- news and events
- promoting new services or features
- information that doesn't impact council services
- content that is better provided by another organisation

Examples of things that wouldn't be an alert:

- weather warnings - these are provided by the Met Office 
- internal messages such as IT outage, payroll deadlines and building issues – these can be communicated by other means like emails or online newsletters 
- reminders for online applications like school admissions – a news story or a social media post is more suitable

## Writing alerts

Keep the alerts short. No more than 2 sentences. Any more will push the content further down the page.

Include links to internal pages where you have to, for example, a school closures alert will link to the school closures page.

## What alerts look like

This is specific to essex.gov.uk. Other websites or microsites will have their own way of adding alerts but the same principles of when and when not to use them apply.

This is an example of an error alert.

<div class="alert error" id="tab-one">
  <div class="alert-icon">
    <span class="fas fa-exclamation-circle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are experiencing some issues</div>
    <p>You may experience some issues with our website. Please bear with us while we resolve the issue.</p>
  </div>
  <button class="text" type="button" onclick="toggle_visibility('tab-one');">Hide this message</button>
</div>

This is an example of an information alert.

<div class="alert info" id="tab-two">
  <div class="alert-icon">
    <span class="fas fa-info-circle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are updating our system</div>
    <p>We have been doing lots of research and you have helped us update this service.</a></p>
  </div>
  <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
</div>

This is an example of a warning alert.

<div class="alert warning" id="tab-three">
  <div class="alert-icon">
    <span class="fas fa-exclamation-triangle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">School closures</div>
    <p>Some schools in Essex are closed due to severe weather. <a href="#">Check if your child's school is closed</a></p>
  </div>
  <button class="text" type="button" onclick="toggle_visibility('tab-three');">Hide this message</button>
</div>

## How to implement an alert

You can find guidance on how to implement an alert on the [alert component](https://www.essex.gov.uk/essex-county-councils-design-and-patterns-library/components/alert-banner) page.
 
