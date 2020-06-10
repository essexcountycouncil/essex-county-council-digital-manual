---
layout: home
title: Elements and Components
---

1. [Home](../)
2. [Design System](../Design-system)
3. {{ page.title }}

# Elements and Components

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Elements

### Back

<a href="/" class="link-back">Back</a>

    <a href="/" class="link-back">Back</a>

#### Using the back link

The back link takes users back to the previous page. It should be used for transactional pages, such as an online form.

The back link shouldn't be used instead of <a href="/">breadcrumbs</a>

### Buttons

<a class="button button-start" href="financial-assessment-eligibility" role="button">Start now</a>

    <a class="button button-start" href="financial-assessment-eligibility" role="button">Start now</a>

<input type="submit" class="button" value="Continue">

    <input type="submit" class="button" value="Continue">

#### Using buttons

Buttons should be used to help users carry out a task, like starting an application.

Button text should be written in sentence case and clearly tell the user what the action is. For example, ‘Start now’, ‘Continue’, ‘Subscribe’.

Buttons can be used to:
<ul>
  <li>Start a form</li>
  <li>Continue to the next question of a form</li>
  <li>Subscribe to something, such as email notifications</li>
</ul>

Buttons shouldn’t be used to replace links within the body of a page.
 
### Checkbox

<div class="form">
  <div class="group">
    <fieldset>
      <legend>Ask your question?</legend>
      <div class="multiple-choice">
        <input id="telephone" name="checkbox" type="checkbox" value="Telephone">
        <label for="telephone">Telephone</label>
      </div>
      <div class="multiple-choice">
        <input id="email" name="checkbox" type="checkbox" value="Email">
        <label for="email">Email</label>
      </div>
      <div class="multiple-choice">
        <input id="post" name="checkbox" type="checkbox" value="Post">
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
            <input id="telephone" name="checkbox" type="checkbox" value="Telephone">
            <label for="telephone">Telephone</label>
          </div>
          <div class="multiple-choice">
            <input id="email" name="checkbox" type="checkbox" value="Email">
            <label for="email">Email</label>
          </div>
          <div class="multiple-choice">
            <input id="post" name="checkbox" type="checkbox" value="Post">
            <label for="post">Post</label>
          </div>
          <div class="panel js-hidden" id="checkbox-selection">
              This panel is shown if selecting last checkbox
          </div>
        </fieldset>
      </div>
    </div>

#### Using checkbox

Checkbox enables users to select more than one choice at a time from a selection of inputs, for examples all items that apply from a list.

If you want users to select just one input at a time, for examples a yes or no answer, use the <a href="radio">radio element</a>

Checkbox is often used as part of a <a href="form">form</a>.

You can avoid having long lists of options by guiding users through with better thought out questions. 

Conditionality allows you to show users additional content or questions to particular users on what they've selected. If you're using this to show lots of content, maybe think about putting it on a separate page. 

### Content break

<div class="content-break-large"></div>

    <div class="content-break-large"></div>

<div class="content-break-small"></div>

    <div class="content-break-small"></div>

#### Using content breaks

Content breaks are visual elements used to separate sections of content.

They should be used to:
<ul>
  <li>thematically divide up sections of content, such as services, news and legislation</li>
  <li>show a divide between a list of clickable items, such as news articles, service links or guidance documents</li>
</ul>

They shouldn't be used to divide paragraphs within the body of content.

### Dropdown

<div class="form">
  <div class="group">
    <label for="sorting" class="form-hint">Sort by</label>
    <select class="form-control" id="sorting" name="sorting">
      <option>Recently published</option>
      <option selected>Recently updated</option>
      <option>Most views</option>
      <option>Most comments</option>
    </select>
  </div>
</div>

    <div class="form">
      <div class="group">
        <label for="sorting" class="form-hint">Sort by</label>
        <select class="form-control" id="sorting" name="sorting">
          <option>Recently published</option>
          <option selected>Recently updated</option>
          <option>Most views</option>
          <option>Most comments</option>
        </select>
      </div>
    </div>

#### Using dropdown

Dropdown should only be used if there is no other alternative as some users can struggle with the functionality.

Try using the <a href="radio">radio</a> or <a href="checkbox">checkbox</a> elements instead.

It's often used when there is a long list that can't presented in another way, such as a list of countries or languages.

*Note: Be sure to update all label and input attributes with the correct details i.e.*
    
    <label for=""></label>
    <select id="">
    <select naming="">

### Embed

#### Embed responsively
<div class="embed-container">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/U9nnRicMHOk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" title="School admissions not preferred school"></iframe>
</div>

	<div class="embed-container">
		<iframe width="560" height="315" src="https://www.youtube.com/embed/U9nnRicMHOk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" title="School admissions not preferred school"></iframe>
	</div>

### External link

If clicking this link <a href="#" rel="external" class="external-link" target="_blank">a new tab<span class="visually-hidden">Opening a new tab from an external website</span></a> will open from an external website.

	<a href="#" rel="external" class="external-link" target="_blank">a new tab<span class="visually-hidden">Opening a new tab from an external website</span></a>

If clicking this link <a href="https://www.google.com" rel="external" class="external-link">your browser tab is replaced<span class="visually-hidden">Replacing your browser tab with an external website</span></a> by an external website.

	<a href="#" rel="external" class="external-link">your browser tab is replaced<span class="visually-hidden">Replacing your browser tab with an external website</span></a>

If clicking this link you will <a href="/public/images/test-pdf-file.pdf" rel="external" class="external-file-link">download or open a file (PDF)<span class="visually-hidden">Clicking this will download or open a PDF</span></a> from this website.

	<a href="/public/images/test-pdf-file.pdf" rel="external" class="external-file-link">download or open a file (PDF)<span class="visually-hidden">Clicking this will download or open a PDF</span></a>.


#### Using External link

The important thing is ensuring users with screen reader and/or with cognitive disabilities are aware a new browser tab has opened or their browser tab has been replaced with an external site.

We also need to consider how this is communicated to all users through the use of icon and supportive text.

##### Further thoughts

There can be some confusion and inconsistency around the use of external link <a href="#" rel="external" class="external-link">iconography</a>. In some cases websites show this when the browserr opens a new tab, others when it is replacing the current tab with an external website.

Currently we are using it for both cases, external tab and tab replacement, to show indication of the browser tab state changing.

### Headings

<h1 class="page-heading">Page heading</h1>

    <h1 class="page-heading">Page heading</h1>

<h2 class="content-heading">Content heading</h2>

    <h2 class="content-heading">Content heading</h2>

<h3 class="section-heading">Section heading</h3>

    <h3 class="section-heading">Section heading</h3>

<h4 class="sub-section-heading">Sub-section heading</h4>

    <h4 class="sub-section-heading">Sub-section heading</h4>


#### Using headings

Headings should be written in sentence case and follow correct semantic structure, for example h1 before h2.

Page heading is styled as h1 and should only be used to display the title of the page. Every page should have a unique page heading but it shouldn’t appear more than once on a page.

* Page heading is used at the top of each page.
* Content heading is used for each new and unlreated piece of content within a page.
* Section heading is used for each section within content on a page.
* Sub-section-heading is used for those occasional cases of additional breaking down within a section is required or additionally certain preview sections.

## Components

### Alert

#### Error

<div class="alert error" id="tab-one">
  <div class="alert-icon">
    <span class="fas fa-exclamation-circle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are experiencing some issues</div>
    <p>You may experience some issues with our website. Please bare with us while we resolve the issue.</p>
    <button class="text" type="button" onclick="toggle_visibility('tab-one');">Hide this message</button>
  </div>
</div>

    <div class="alert error" id="tab-one">
      <div class="alert-icon">
        <span class="fas fa-exclamation-circle"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">We are experiencing some issues</div>
        <p>You may experience some issues with our website. Please bare with us while we resolve the issue.</p>
        <button class="text" type="button" onclick="toggle_visibility('tab-one');">Hide this message</button>
      </div>
    </div>

#### Information

<div class="alert info" id="tab-two">
  <div class="alert-icon">
    <span class="fas fa-info-circle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">We are updating our system</div>
    <p>We have been doing lots of research and you have helped us update this service.</p>
    <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
  </div>
</div>

    <div class="alert info" id="tab-two">
      <div class="alert-icon">
        <span class="fas fa-info-circle"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">We are updating our system</div>
        <p>We have been doing lots of research and you have helped us update this service.</p>
        <button class="text" type="button" onclick="toggle_visibility('tab-two');">Hide this message</button>
      </div>
    </div>

#### Warning

<div class="alert warning" id="tab-three">
  <div class="alert-icon">
    <span class="fas fa-exclamation-triangle"></span>
  </div>
  <div class="alert-text">
    <div class="section-heading">School closures</div>
    <p>Some schools in Essex are closed due to severe weather. <a href="#">Check if your child's school is closed</a></p>
    <button class="text" type="button" onclick="toggle_visibility('tab-three');">Hide this message</button>
  </div>
</div>

    <div class="alert warning" id="tab-three">
      <div class="alert-icon">
        <span class="fas fa-exclamation-triangle"></span>
      </div>
      <div class="alert-text">
        <div class="section-heading">School closures</div>
        <p>Some schools in Essex are closed due to severe weather. <a href="#">Check if your child's school is closed</a></p>
        <button class="text" type="button" onclick="toggle_visibility('tab-three');">Hide this message</button>
      </div>
    </div>


#### When to use Error alerts

Error alerts are used to direct a user's attention to important system errors. This could include:
<ul>
  <li>technical problems or maintenance on the website</li>
</ul>


#### When to use Information alerts

Information alerts are used to direct a user's attention to important information. This could include:
<ul>
  <li>changes to regular council services</li>
</ul>


#### When to use Warning alerts

Warning alerts are used to prepare users for a variety of real life issues. This could include:
<ul>
  <li>adverse weather information</li>
</ul>

#### Where to use alerts

An alert can be displayed on the homepage or on lower level pages, depending on the topic and severity. They should always be clear and concise and link to another page with further information if necessary.

They shouldn't be used within paragraphs of text.

### Breadcrumbs

<nav class="breadcrumbs" aria-label="breadcrumbs">
  <ol>
    <li><a href="/">Home</a></li>
    <li><a href="adult-social-care">Adult Social Care</a></li>
  </ol>
</nav>

    <nav class="breadcrumbs" aria-label="breadcrumbs">
      <ol>
        <li><a href="/">Home</a></li>
        <li><a href="adult-social-care">Adult Social Care</a></li>
      </ol>
    </nav>


#### Breadcrumbs

Breadcrumbs show users where they are in the website hierarchy and they provide a way to navigate through previous levels of content.

They should always be displayed at the top of the page.

We also remove hyperlink styles for the last-child in the breadcrumbs.

### Browser check

<div id="browser-check" class="browser-check-background" role="region" aria-label="browsercheck">
  <div class="browser-check">
    <p class="browser-content">You’re currently using an old browser. <a href="/browsers" title="Learn about the latest browsers">Find out how to update your browser</a> to get the best experience on this website.</a></p>
  </div>
</div>


    <div id="browser-check" class="browser-check-background" role="region" aria-label="browsercheck">
      <div class="browser-check">
        <p class="browser-content">You’re currently using an old browser. <a href="/browsers" title="Learn about the latest browsers">Find out how to update your browser</a> to get the best experience on this website.</a></p>
      </div>
    </div>


    <!--[if lte IE 8]>
      <div id="browser-check" class="browser-check-background" role="region" aria-label="browsercheck">
        <div class="browser-check">
          <p class="browser-content">You’re currently using an old browser. <a href="/browsers" title="Learn about the latest browsers">Find out how to update your browser</a> to get the best experience on this website.</a></p>
        </div>
      </div>
    <![endif]-->

### Contents

<nav class="contents" aria-label="pages-in-this-service">
  <div class="heading"><h2>Contents</h2></div>
  <ol class="list list-number" id="pages-in-this-service">
    <li>Paying for care and support</li>
    <li><a href="#">Financial assessment </a></li>
    <li><a href="#">Personal budget</a></li>
    <li><a href="#">Care charges</a></li>
    <li><a href="#">Ways to pay for your care</a></li>
    <li><a href="#">Paying for a residential home</a></li>
    <li><a href="#">Deferred payment scheme</a></li>
    <li><a href="#">Independent financial advice</a></li>
    <li><a href="#">Direct payments</a></li>
    <li><a href="#">Contact us</a></li>
  </ol>
</nav>

    <nav class="contents" aria-label="pages-in-this-service">
      <div class="heading"><h2>Contents</h2></div>
      <ol class="list list-number" id="pages-in-this-service">
        <li>Paying for care and support</li>
        <li><a href="#">Financial assessment </a></li>
        <li><a href="#">Personal budget</a></li>
        <li><a href="#">Care charges</a></li>
        <li><a href="#">Ways to pay for your care</a></li>
        <li><a href="#">Paying for a residential home</a></li>
        <li><a href="#">Deferred payment scheme</a></li>
        <li><a href="#">Independent financial advice</a></li>
        <li><a href="#">Direct payments</a></li>
        <li><a href="#">Contact us</a></li>
      </ol>
    </nav>

#### Using contents

Contents is an in-page navigation to guide the user through a series of pages that are linked together.

It should be used on information pages and should be positioned at the top, just below the page title.

It shouldn't be used to link to other sections of the website or pages that aren't grouped together.

### File download

<div class="file-download"><a href="/public/images/test-pdf-file.pdf" class="file-link">This is a title for the file download link</a>
	<p><span>PDF, 4.84 MB</span>This is used for any descriptions required for this downloadable file.</p>
</div>

	<div class="file-download"><a href="/public/images/test-pdf-file.pdf" class="file-link">This is a title for the file download link</a>
		<p><span>PDF, 4.84 MB</span>This is used for any descriptions required for this downloadable file.</p>
	</div>

If we need to show multiple files it is recommended to have signposting to accessibilty concerns to apply to all files so to avoid unnecessary repetition.

<div class="file-collection">
	<h4>Related information</h4>
	<p>The following files are in downloadable formats and may not be suitable for users of assistive technology.</p>
	<div class="file-download"><a href="/public/images/test-pdf-file.pdf" class="file-link">This is a title for the file download link</a>
		<p><span>PDF, 4.84 MB</span>This is used for any descriptions required for this downloadable file.</p>
	</div>
	<div class="file-download"><a href="/public/images/test-pdf-file.pdf" class="file-link">This is a title for the file download link</a>
		<p><span>PDF, 4.84 MB</span>This is used for any descriptions required for this downloadable file.</p>
	</div>
	<div class="file-download"><a href="/public/images/test-pdf-file.pdf" class="file-link">This is a title for the file download link</a>
		<p><span>PDF, 4.84 MB</span>This is used for any descriptions required for this downloadable file.</p>
	</div>
</div>

#### Using file links

We use file links for displaying to users downloadable files such as pdf.

### Footer

<footer id="main-footer" class="footer-container">
  <div class="footer-top">
    <div class="footer">
      <div class="nav">
        <ul class="nav-links">
          <li><a href="https://www.essex.gov.uk/topic/about-essexgovuk">About essex.gov.uk</a></li><li>
            <a href="https://www.essex.gov.uk/accessibility">Accessibility</a></li><li>
            <a href="https://www.essex.gov.uk/cookies">Cookies</a></li><li>
            <a href="https://www.essex.gov.uk/terms-conditions">Terms and conditions</a></li><li>
            <a href="https://www.essex.gov.uk/privacy-and-data-protection">Privacy and data protection</a></li><li>
            <a href="/topic/contact-us">Contact us</a></li>
        </ul>
        <ul class="social">
          <li>
            <a href="https://www.facebook.com/essexcountycouncil"><span class="fab fa-facebook-f"></span><span>Facebook</span></a></li><li>
            <a href="https://twitter.com/essex_cc"><span class="fab fa-twitter"></span><span>Twitter</span></a></li><li>
            <a href="http://www.youtube.com/user/EssexCountyCouncil"><span class="fab fa-youtube"></span><span>Youtube</span></a></li><li>
            <a href="https://www.flickr.com/photos/essexcc/"><span class="fab fa-flickr"></span><span>Flickr</span></a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="footer-bottom">
    <div class="footer">
      <ul class="credits">
        <li class="copyright">© Essex County Council 2019</li>
        <li class="design-link"><a href="https://servicedesign.blog.essex.gov.uk/">Built by the Service Design Team</a></li>
      </ul>
    </div>
  </div>
</footer>

    <footer id="main-footer" class="footer-container">
      <div class="footer-top">
        <div class="footer">
          <div class="nav">
            <ul class="nav-links">
              <li><a href="https://www.essex.gov.uk/topic/about-essexgovuk">About essex.gov.uk</a></li><li>
                <a href="https://www.essex.gov.uk/accessibility">Accessibility</a></li><li>
                <a href="https://www.essex.gov.uk/cookies">Cookies</a></li><li>
                <a href="https://www.essex.gov.uk/terms-conditions">Terms and conditions</a></li><li>
                <a href="https://www.essex.gov.uk/privacy-and-data-protection">Privacy and data protection</a></li><li>
                <a href="/topic/contact-us">Contact us</a></li>
            </ul>
            <ul class="social">
              <li>
                <a href="https://www.facebook.com/essexcountycouncil"><span class="fab fa-facebook-f"></span><span>Facebook</span></a></li><li>
                <a href="https://twitter.com/essex_cc"><span class="fab fa-twitter"></span><span>Twitter</span></a></li><li>
                <a href="http://www.youtube.com/user/EssexCountyCouncil"><span class="fab fa-youtube"></span><span>Youtube</span></a></li><li>
                <a href="https://www.flickr.com/photos/essexcc/"><span class="fab fa-flickr"></span><span>Flickr</span></a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <div class="footer">
          <ul class="credits">
            <li class="copyright">© Essex County Council 2019</li>
            <li class="design-link"><a href="https://servicedesign.blog.essex.gov.uk/">Built by the Service Design Team</a></li>
          </ul>
        </div>
      </div>
    </footer>

#### Using the footer

The footer is displayed at the bottom of every page and is consistent across the entire site.

It should provide users with supplementary information, such as social media links, contact links and copyright information.


### Header

<header class="header-background">
  <div class="header">
    <div class="nav">
      <div class="logo-wrap">
        <a href="/" class="logo-text seax">
          <img src="/public/images/seax.png" width="36" height="30" alt="Essex County Council logo">
          Essex.gov.uk
        </a>
      </div>
    </div>
  </div>
</header>

    <header class="header-background">
      <div class="header">
        <div class="nav">
          <div class="logo-wrap">
            <a href="/" class="logo-text seax">
              <img src="/public/images/seax.png" width="36" height="30" alt="Essex County Council logo">
              Essex.gov.uk
            </a>
          </div>
        </div>
      </div>
    </header>


#### Using the header

The header is displayed at the top of every page and is consistent across the entire site.

It should display the site's identity and branding, making it clear to the user what website they are on. The header may also contain some <a href="/docs/core/elements/nav">navigation links</a>.  

### Highlight-box

<div class="highlight-box">
  <h1>
    Financial checker complete
  </h1>
  <p>
    Self funded care
  </p>
</div>

    <div class="highlight-box">
      <h1>
        Financial checker complete
      </h1>
      <p>
        Self funded care
      </p>
    </div>

#### Using the highlight box

The highlight box should display important information to a user after completing a transaction. It will usually be on the final page of a <a href="/docs/core/elements/form">form</a>.

A <code>h1</code> tag is included within Hilight-box, and so should be the page heading w