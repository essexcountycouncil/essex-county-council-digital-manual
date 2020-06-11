1.  [Contents](/docs/core/design/overview)
2.  [Form Validation](#)

# Form Validation

<div class="error-summary" role="alert" aria-label="error-summary-heading-example-1" tabindex="-1">
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

    <div class="error-summary" role="alert" aria-label="error-summary-heading-example-1" tabindex="-1">
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
    
 
## Descriptive error and validation messages
    
Use an error message to explain why what’s been entered isn’t right, and how to fix it. 

These should only be shown if a user tries to move on to the next stage of the form, not when they select a field, are typing or move away from the field. 

A good error message is concise, positive and specific. Avoid things like, ‘An error occurred’ or ‘invalid information entered’. The message should make sense out of context and sound like something you’d say to a user. 

### Examples of good error messages include:

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

### When not to use validation or error messages

These messages should only be used to resolve validation issues, they shouldn’t be used to tell users they’re not eligible for a service. This should be done on a separate screen that gives a way for the user to end or continue their journey. 
