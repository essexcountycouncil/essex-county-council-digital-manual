---
layout: page
title: What are the most popular pages on my website?
---
# {{page.title}}

The last and final thing you will want to see, when understanding Google Analytics, is which pages on your website are the most popular. To get a quick glimpse, go to ‘Behaviour’ – ‘Overview’. On this screen you will see:

*   The number of pages visited in total for the period (known as Page Views)
*   The number of pages visited by the same visitor during the same visit (known as Unique Page Views)
*   The average time people are spending on your pages
*   The percentage of single page visits, where the visitor has left your website without browsing any further pages (known as Bounce Rate)
*   The percentage of visits that resulted in the visitor leaving your website after browsing previous pages on your website (known as Exit Rate)
*   A table of your website pages in ascending order by the number of times someone has visited that page (Page Views). Page Title, Search Term and Events Category (if Event Tracking has been setup on your website) can then break down this table.

![](/public/images/what-are-the-most-popular-pages.jpg?width=500&height=375)

You can find the “Behavior” reports under “Behavior” in the left-hand navigation. It’s important to understand how Google Analytics calculates behavior data. If you recall, Analytics uses a small piece of Javascript code on your website to collect data. Every time a user loads a page on your website, this tracking code creates a “pageview” that is reported in Google Analytics. Analytics uses this to calculate many of the metrics in the Behavior reports. For example, the “Total Pageviews” metric is simply the sum of each time a user loaded a page on your website.

Let’s begin by looking at the “All Pages” report located under “Site Content” and scroll down to the data table.

![](/public/images/behaviour-reports-2.jpg?width=500&height=250)

*   The “Pageviews” metric shows how frequently each page on your site was viewed. By default, this report will show data by the page URI. The URI is the part of the URL after the domain name in the location bar of the browser. If you switch the primary dimension of the report to “Page Title,” you can view this report by the title listed in the web page’s HTML.
*   Other metrics in the “All Pages” report like “Average Time on Page” and “Bounce Rate” indicate how engaged users were on each page of your site. You can sort the report by these metrics to quickly find low-performing pages that need improvement or high-performing content to guide future content decisions.

The “Content Drilldown” report under “Site Content” groups pages according to your website’s directory structure. You can click on a directory to see the pages of your site within that directory. This is especially useful if you’re trying to understand the performance of content in a particular section of your website. If you switch to the pie chart view, you can quickly see which sections of your site are most popular with your users.

The “Landing Pages” report under “Site Content” lists the pages of your website where users first arrived. These are the first pages viewed in a session. You can use this report to monitor the number of bounces and the bounce rate for each landing page. A high bounce rate usually indicates that the landing page content is not relevant or engaging for those users.

The “Exit Pages” report under “Site Content” shows the pages where users left your site. Because you don’t want users exiting from important pages like a shopping cart checkout, it’s a good idea to periodically review this report to minimize unwanted exits.

The “Events” report tracks how users interact with specific elements of your website. For example, you can use this report to track when users click on a video player or a download link. Event tracking requires additional implementation beyond the Analytics tracking code snippet.

<nav class="pagination" aria-label="pagination">
  <ul>
    <li class="prev">
      <a href="Where-are-my-visits-coming-from">
        <span class="pagination-item">
          <span class="fas fa-arrow-left"></span>Previous
        </span>
        <span>Where are my visits coming from?</span>
      </a>
    </li>
    <li class="next">
      <a href="Ecc-web-analytics-framework">
        <span class="pagination-item">
          <span class="fas fa-arrow-right"></span>Next
        </span>
        <span>Essex County Council Web Analytics Framework</span>
      </a>
    </li>
  </ul>
</nav>