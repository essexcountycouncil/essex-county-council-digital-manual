1.  [Contents](/docs/core/design/overview)
2.  [Radio](#)

# Radio

<div class="form">
  <div class="group">
    <fieldset>
      <legend>Asking your question?</legend>
      <div class="multiple-choice">
        <input id="selection-one" type="radio" name="radio" value="yes">
        <label for="selection-one">Yes</label>
      </div>
      <div class="multiple-choice">
        <input id="selection-two" type="radio" name="radio" value="no">
        <label for="selection-two">No</label>
      </div>
    </fieldset>
  </div>
</div>

    <div class="form">
      <div class="group">
        <fieldset>
          <legend>Asking your question?</legend>
          <div class="multiple-choice">
            <input id="selection-one" type="radio" name="radio" value="yes">
            <label for="selection-one">Yes</label>
          </div>
          <div class="multiple-choice">
            <input id="selection-two" type="radio" name="radio" value="no">
            <label for="selection-two">No</label>
          </div>
        </fieldset>
      </div>
    </div>

<div class="form">
  <div class="group">
    <fieldset>
      <legend>Asking your question?</legend>
      <div class="multiple-choice">
        <input id="selection-three" type="radio" name="radio" value="yes">
        <label for="selection-three">Yes</label>
      </div>
      <div class="multiple-choice" data-target="radio-selection">
        <input id="selection-four" type="radio" name="radio" value="no" aria-controls="radio-selection" aria-expanded="false">
        <label for="selection-four" class="show">No show result</label>
      </div>
      <!-- show/hide this -->
      <div class="inset panel js-hidden" id="radio-selection" aria-hidden="true">
          This panel is shown if selecting last radio
      </div>
    </fieldset>
  </div>
</div>

    <div class="form">
      <div class="group">
        <fieldset>
          <legend>Asking your question?</legend>
          <div class="multiple-choice">
            <input id="selection-three" type="radio" name="radio" value="yes">
            <label for="selection-three">Yes</label>
          </div>
          <div class="multiple-choice" data-target="radio-selection">
            <input id="selection-four" type="radio" name="radio" value="no" aria-controls="radio-selection" aria-expanded="false">
            <label for="selection-four" class="show">No show result</label>
          </div>
          <!-- show/hide this -->
          <div class="inset panel js-hidden" id="radio-selection" aria-hidden="true">
              This panel is shown if selecting last radio
          </div>
        </fieldset>
      </div>
    </div>



# Using radio

Radio enables users to select just one input at a time from a selection of inputs, for examples a yes or no answer.

If you want users to select multiple inputs at a time, use the <a href="checkbox">checkbox element</a>

Radio is often used as part of a <a href="form">form</a>

*Note: Be sure to update all label and input attributes with the correct details i.e.*
    
    <label for="">
    <input id="">
    <input type="">
    <input name="">
    <input value="">
    
## How to use radios

Always position radios to the left of their labels. This makes them easier to find, especially for users of screen magnifiers.

Unlike with checkboxes, users can only select one option from a list of radios. Do not assume that users will know how many options they can select based on the visual difference between radios and checkboxes alone.

If needed, add a hint explaining this, for example, ‘Select one option’.

You should arrange options alphabetically, unless there's a clear need to arrange by use. You shouldn't pre-select an option, as users may miss the question. 

## Stacking

If there are only 2 options, it's fine to have them laid out horizontally. If there are more, they should be stacked vertically. Try to avoid having too many options. More than 5 or 6 and users could get confused or miss options. If necessary, use a series of simpler questions. 
