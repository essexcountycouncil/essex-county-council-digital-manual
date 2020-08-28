---
layout: page
title: Form validation
---

# {{ page.title }}

Use form validation to highlight to users that a question has either:

- not been answered
- not been answered correctly 

## Error summary

The error summary should always be show when there is a validation error, even if there is only one.

<div class="error-summary" role="alert" aria-label="error-summary-heading-example-1">
  <h2 class="heading-medium error-summary-heading" id="error-summary-heading-example-1">
    Message to alert the user to a problem goes here
  </h2>
  <p>
    Optional description of the errors and how to correct them
  </p>
  <ul class="error-summary-list">
    <li><a href="#">Descriptive link to the question with an error</a></li>
  </ul>
</div>

    <div class="error-summary" role="alert" aria-label="error-summary-heading-example-1">
      <h2 class="heading-medium error-summary-heading" id="error-summary-heading-example-1">
        Message to alert the user to a problem goes here
      </h2>
      <p>
        Optional description of the errors and how to correct them
      </p>
      <ul class="error-summary-list">
        <li><a href="#">Descriptive link to the question with an error</a></li>
      </ul>
    </div>

### How to use the Error summary

You must:

- move keyboard focus to the error summary
- include the heading 'There is a problem'
- link to each of the answers that have a validation errors
- make sure the error messages in the summary match the error messages by the relevant input
- make error messages clear and concise
- ensure error messages are in order

You should place the error summary directly after the <code>main</code> container. If your page contains a back link place it after this.

## Errors messages

Use an error message when there is a validation error. Explain what went wrong and how to fix it.

<form class="form">
  <div class="group form-group-error">
    <label for="name">Full name</label>
    <span class="form-hint">As shown on your birth certificate or passport</span>
    <span class="error-message">Error message goes here</span>
    <input class="form-control form-control-error" id="name" name="name" type="text">
  </div>
  <div class="group form-group-error">
    <label for="details">Label</label>
    <span class="form-hint">Form Hint message</span>
    <span class="error-message">Error message goes here</span>
    <textarea class="form-control form-control-error" id="details" name="detail" type="text"></textarea>
  </div>
  <div class="group form-group-error">
    <label for="sorting">Sort by</label>
    <span class="error-message">Error message goes here</span>
    <select class="form-control form-control-error" id="sorting" name="sorting">
      <option>Recently published</option>
      <option selected>Recently updated</option>
      <option>Most views</option>
      <option>Most comments</option>
    </select>
  </div>
  <input type="submit" class="button" value="Continue">
</form>

    <form class="form">
      <div class="group form-group-error">
        <label for="name">Full name</label>
        <span class="form-hint">As shown on your birth certificate or passport</span>
        <span class="error-message">Error message goes here</span>
        <input class="form-control form-control-error" id="name" name="name" type="text">
      </div>
      <div class="group form-group-error">
        <label for="details">Label</label>
        <span class="form-hint">Form Hint message</span>
        <span class="error-message">Error message goes here</span>
        <textarea class="form-control form-control-error" id="details" name="detail" type="text"></textarea>
      </div>
      <div class="group form-group-error">
        <label for="sorting">Sort by</label>
        <span class="error-message">Error message goes here</span>
        <select class="form-control form-control-error" id="sorting" name="sorting">
          <option>Recently published</option>
          <option selected>Recently updated</option>
          <option>Most views</option>
          <option>Most comments</option>
        </select>
      </div>
      <input type="submit" class="button" value="Continue">
    </form>    

## When to use error messages

Use the error message when there is a validation error. Such as:

- you need to tell the user to choose an option
- you need the user to correct their input

## When not to use error messages

Only display error messages when someone tries to advance to the next part of a service. Error messages should not be used when:

- when tabbing between inputs
- when users are typing

Do not use error messages to tell users they are ineligible, instead take them to a screen thats:

- explains why they are not eligible
- tell them what to do next
 
### Descriptive error and validation messages

A good error message is concise, positive and specific. Avoid things like:

- An error occurred
- invalid information entered

The message should make sense out of context and sound like something you’d say to a user. 

### Examples of good error messages

#### Addresses
‘Enter a real postcode’
#### Character count
‘X must be 350 characters or fewer’
‘You have X characters too many’
#### Check boxes
‘Select if you are X, Y or Z’
#### Dates
‘Enter a real date of birth’
‘X must be today or in the future’
‘A date of birth must include a day, a month and a year’
#### Emails
‘Enter an email address in the correct format, like name@example.com
#### File upload
‘The X file must be smaller than 2MB’
‘The selected file must be a JPG, PNG or PDF’
#### Names
‘Enter your full name’
#### National Insurance number
‘Enter a National Insurance number in the correct format’
#### Radio buttons
‘Select yes if….’
‘Select if…’
#### Telephone numbers
‘Enter a UK telephone number’
#### Text area
‘Enter…’
‘X must between Y and Z’
