---
layout: page
title: Where are my visits coming from?
---
# {{page.title}}

Once you understand everything about the visits that are coming to your site, it is time to find out where those visits originated. This is one of the most important things you should be looking at on a regular basis, especially if you are investing in any form of online marketing.

To get a quick glimpse, go to ‘Acquisition’ – ‘Overview’. On this screen you will see:

*   A graph showing the number of visits
*   A pie chart showing the top places where those visits came from (known as Top Channels)
*   A graph showing the number of Conversions (this requires Goal Tracking to be setup, which I will cover in another article)
*   A table showing Acquisition, Behaviour and Conversions for each channel

![](/public/images/where-are-my-visitors-coming-from.jpg?width=500&height=375)

Now let's take a deeper look.

![](/public/images/acquisition-reports.jpg?width=500&height=230)

You can think of the medium as the mechanism that delivered users to your site. Some common examples of mediums are “organic,” “cpc,” “referral,” “email,” and “none.” Let’s look at these different types of mediums:

*   “Organic” is used to identify traffic that arrived on your site through unpaid search like a non-paid Google Search result.
*   “CPC” indicates traffic that arrived through a paid search campaign like Google AdWords text ads.
*   “Referral” is used for traffic that arrived on your site after the user clicked on a website other than a search engine.
*   “Email” represents traffic that came from an email marketing campaign.
*   “(none)” is applied for users that come directly to your site by typing your URL directly into a browser. In your reports, you will see these users have a source of “direct” with a medium of “(none)”.

“Source” provides more information about the medium. For example, if the medium is “referral,” then the source will be the URL of the website that referred the user to the site. If the medium is “organic,” then the source will be the name of the search engine such as “google.”

Under “All Traffic” let’s look at the “Source/Medium” report in The Google Store Analytics account using the dates August 1, 2015 through August 31, 2015. This shows the sources and their respective mediums sending referrals, search engine traffic, and direct traffic to the site. Notice that the default sort is users.

![](/public/images/acquisition-reports-2.jpg?width=500&height=250)

To identify effective traffic sources, we can look at the source/medium combinations with the most users, but that doesn’t necessarily mean this was the best traffic. Ideally, traffic should be “high quality,” meaning that users who arrive from a source engage with the website or complete a conversion. A good indicator of traffic quality can be bounce rate.

Our top traffic source is Google organic search, which has a relatively low bounce rate compared to other sources. Our second most popular traffic source is direct traffic. YouTube referrals were the third highest traffic source, but had one of the highest bounce rates. Let’s do a bit more analysis to understand if this is a problem.

We can click into the comparison view and select the metric “bounce rate” to compare bounce rate for each source/medium combination to the site average. Sure enough, we can see that our YouTube traffic is bouncing at a much higher rate than the site average. The Google Store may want to investigate to make sure that YouTube traffic is landing on a page that’s valuable to those users.

![](/public/images/acquisition-reports-3.jpg?width=500&height=250)

If we want to see only the “organic” sources sending traffic to the site, we could type “organic” into the filter. You can see that Google referred more traffic than any other non-paid source and had a relatively low bounce rate compared to other sources. This means that users arriving from Google Organic search are landing on highly relevant pages.

Now let’s compare the performance for all of our various Google marketing activities that generated traffic by changing the filter to “google.” We can now see that organic traffic was our biggest traffic source, followed by google/cpc, which represents paid search traffic using Google AdWords. This is a great way to add context to your analysis and understand which marketing activities are generating success for your business.

## Channels Report

There are other ways to view which traffic sources bring the most engaged users to the site. Using the “Channels” report, we could view traffic by channel, which bundles the sources together under each medium. Traffic sources are automatically grouped into basic categories (or channels) like Organic, Social, Direct, Referral, Display, etc.

Clicking into each channel will break out the individual sources for that channel. If you want to group your sources differently, you can create your own channel groupings in Google Analytics.

## Referrals Report

If you want to view your traffic organized by which sites have linked to yours, you can look at the “Referrals” report.

You can even click into individual referrals to see which specific web pages link back to your site. If you want to understand which specific pages of your site are being linked to, you can add a secondary dimension of “landing page” to the report. This will show you which external sites are sending traffic to each of your specific pages, and potentially offer you a source of new advertising partnerships with those referring websites.

<nav class="pagination" aria-label="pagination">
  <ul>
    <li class="prev">
      <a href="How-many-visits-am-i-getting">
        <span class="pagination-item">
          <span class="fas fa-arrow-left"></span>Previous
        </span>
        <span>How many visits am i getting?</span>
      </a>
    </li>
    <li class="next">
      <a href="What-are-the-most-popular-pages-on-my-website">
        <span class="pagination-item">
          <span class="fas fa-arrow-right"></span>Next
        </span>
        <span>What are the most popular pages on my website?</span>
      </a>
    </li>
  </ul>
</nav>