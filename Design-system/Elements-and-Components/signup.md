---
layout: page
title: Signup
---

# {{ page.title }}

Use the signup to allow users to register for notifications. The method used applies to email notifcations, but could be applied to other methoda of communications.

We have 2 types of signup that we use at Essex County Council Website (Essex.gov.uk)

- the [basic sign up](#basic-sign-up)
- the [big sign up](#big-sign-up)

## Basic sign up

## When to use sign up

<section class="signup" role="form" aria-label="Subscribe to email">
  <h2 class="section-heading">Stay up to date</h2>
  <p>Get the latest news and information about your council services</p>
  <form action="/search" method="get" class="form">
    <div class="group">
      <div class="signup-input">
        <label for="email">Enter your email address
          <input type="text" id="email" name="email" autocomplete="off">
        </label>
      </div>
      <div class="signup-button" id="submitYourEmailAddress">
        <button type="submit" class="button subscribe">Subscribe</button>
      </div>
    </div>
  </form>
</section>

    <section class="signup" role="form" aria-label="Subscribe to email">
      <h2 class="section-heading">Stay up to date</h2>
      <p>Get the latest news and information about your council services</p>
      <form action="/search" method="get" class="form">
        <div class="group">
          <div class="signup-input">
            <label for="email">Enter your email address
              <input type="text" id="email" name="email" autocomplete="off">
            </label>
          </div>
          <div class="signup-button" id="submitYourEmailAddress">
            <button type="submit" class="button subscribe">Subscribe</button>
          </div>
        </div>
      </form>
    </section>

## Big sign up

## When to use big sign up

<section class="signup-background" aria-label="Subscribe to email">
  <div class="signup">
    <h2 class="section-heading">Stay up to date</h2>
    <p>Get the latest news and information about your council services</p>
    <form action="/search" method="get" class="form">
      <div class="group">
        <div class="signup-input">
          <label for="email">Enter your email address
            <input type="text" id="email" name="email" autocomplete="off">
          </label>
        </div>
        <div class="signup-button" id="submitYourEmailAddress">
          <button type="submit" class="button subscribe">Subscribe</button>
        </div>
      </div>
    </form>
  </div>
</section>

    <section class="signup-background" aria-label="Subscribe to email">
      <div class="signup">
        <h2 class="section-heading">Stay up to date</h2>
        <p>Get the latest news and information about your council services</p>
        <form action="/search" method="get" class="form">
          <div class="group">
            <div class="signup-input">
              <label for="email">Enter your email address
                <input type="text" id="email" name="email" autocomplete="off" placeholder="Enter your email address">
              </label>
            </div>
            <div class="signup-button" id="submitYourEmailAddress">
              <button type="submit" class="button subscribe">Subscribe</button>
            </div>
          </div>
        </form>
      </div>
    </section>

## How to use sign ups

When using sign up it should include a heading that should clearly and concisely tell the user what they are signing up to.

### Accessibility

To ensure sign ups are accessible it is important that the input and label are connected so assisstive technologies can recognise they are connected.  

    <label for="email">Enter your email address
      <input type="text" id="email" name="email" autocomplete="off">
     </label>

## Content to be published 

- Error handling with inputs