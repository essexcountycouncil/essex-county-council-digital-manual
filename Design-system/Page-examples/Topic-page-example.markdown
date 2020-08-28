---
layout: example
title: Topic page example
---

# {{page.title}}

<div class="alert info" id="tab-two">
  <div class="alert-icon">
    <span class="fas fa-info-circle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">Alert heading</div>
    <p>Alert information with <a href="#">alert link</a></p>
    <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
  </div>
</div>

<ul class="link-boxes">
  <li class="link-box">
    <div class="link-content">
      <a href="#" class="sub-section-heading">Link box</a>
        <p>Link box copy explaining what content it contains</p>
    </div>
  </li>
  <li class="link-box">
    <div class="link-content">
      <a href="#" class="sub-section-heading">Link box</a>
        <p>Link box copy explaining what content it contains</p>
    </div>
  </li>
  <li class="link-box">
    <div class="link-content">
      <a href="#" class="sub-section-heading">Link box</a>
        <p>Link box copy explaining what content it contains</p>
    </div>
  </li>
</ul>

<div class="preview-list">
  <ul>
    <li>
      <a href="#">Preview</a>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p></li>
    <li>
      <a href="#">Preview</a>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p></li>
    <li>
      <a href="#">Preview</a>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p></li>
    <li>
      <a href="#">Preview</a>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p></li>
    <li>
      <a href="#">Preview</a>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p></li>
  </ul>
</div>

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