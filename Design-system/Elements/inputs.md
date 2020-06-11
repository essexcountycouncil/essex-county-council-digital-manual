1.  [Contents](/docs/core/design/overview)
2.  [Inputs](#)

# Inputs

<form class="form">
  <div class="group">
    <label for="name">Full name</label>
    <span class="form-hint">As shown on your birth certificate or passport</span>
    <input class="form-control" id="name" name="name" type="text">
  </div>
</form>

    <form class="form">
      <div class="group">
        <label for="name">Full name</label>
        <span class="form-hint">As shown on your birth certificate or passport</span>
        <input class="form-control" id="name" name="name" type="text">
      </div>
    </form>

<form class="form">
  <div class="group">
    <fieldset>
      <legend>
        <span class="form-hint">
          What is your date of birth?
        </span>
        <span class="form-hint">
          For example, 31 3 1980
        </span>
      </legend>
      <div class="group day">
        <label for="day">Day</label>
        <input class="form-control" id="day" name="day" type="number">
      </div>
      <div class="group month">
        <label for="month">Month</label>
        <input class="form-control" id="month" name="month" type="number">
      </div>
      <div class="group year">
        <label for="year">Year</label>
        <input class="form-control" id="year" name="year" type="number">
      </div>
    </fieldset>
  </div>
</form>

    <form class="form">
      <div class="group">
        <fieldset>
          <legend>
            <span class="form-hint">
              What is your date of birth?
            </span>
            <span class="form-hint">
              For example, 31 3 1980
            </span>
          </legend>
          <div class="group day">
            <label for="day">Day</label>
            <input class="form-control" id="day" name="day" type="number">
          </div>
          <div class="group month">
            <label for="month">Month</label>
            <input class="form-control" id="month" name="month" type="number">
          </div>
          <div class="group year">
            <label for="year">Year</label>
            <input class="form-control" id="year" name="year" type="number">
          </div>
        </fieldset>
      </div>
    </form>

## Using inputs

A text input allows users to add a single line of text, such as their name, email address or telephone number.

A fieldset input lets users add a date, such as their date of birth or a memorable date.

Inputs should be used as part of the <a href="form">form component</a>

Don't use inputs when users need to enter a longer string of text - in this case you should use the <a href="textarea">textarea element</a>

## Form

<form class="form">
  <div class="group">
    <label for="name">Full name</label>
    <span class="form-hint">As shown on your birth certificate or passport</span>
    <input class="form-control" id="name" name="name" type="text">
  </div>
  <div class="group">
    <fieldset>
      <legend>
        <span class="form-hint">
          What is your date of birth?
        </span>
        <span class="form-hint">
          For example, 31 3 1980
        </span>
      </legend>
      <div class="group day">
        <label for="day">Day</label>
        <input class="form-control" id="day" name="day" type="number">
      </div>
      <div class="group month">
        <label for="month">Month</label>
        <input class="form-control" id="month" name="month" type="number">
      </div>
      <div class="group year">
        <label for="year">Year</label>
        <input class="form-control" id="year" name="year" type="number">
      </div>
    </fieldset>
  </div>
  <input type="submit" class="button" value="Continue">
</form>

    <form class="form">
      <div class="group">
        <label for="name">Full name</label>
        <span class="form-hint">As shown on your birth certificate or passport</span>
        <input class="form-control" id="name" name="name" type="text">
      </div>
      <div class="group">
        <fieldset>
          <legend>
            <span class="form-hint">
              What is your date of birth?
            </span>
            <span class="form-hint">
              For example, 31 3 1980
            </span>
          </legend>
          <div class="group day">
            <label for="day">Day</label>
            <input class="form-control" id="day" name="day" type="number">
          </div>
          <div class="group month">
            <label for="month">Month</label>
            <input class="form-control" id="month" name="month" type="number">
          </div>
          <div class="group year">
            <label for="year">Year</label>
            <input class="form-control" id="year" name="year" type="number">
          </div>
        </fieldset>
      </div>
      <input type="submit" class="button" value="Continue">
    </form>

*Note: Be sure to update all label and input attributes with the correct details i.e.*
    
    <label for=""></label>
    <input id="">
    <input type="">
    <input name="">