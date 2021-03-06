---
layout: post
title: How to Use Advanced Options to Add or Filter Specific URLs
category: manual
tags: "help-manual manage-content domains advanced supplemental-feed supplemental-urls filter-urls"
published: true
---

[DigitalGov Search](/index.html) > [Admin Center](https://search.usa.gov/sites/) > YourSite > Manage Content > [Domains](/manual/domains.html) > Advanced

## Add a URL

Are specific web pages missing from your Bing web results? Tell us about these URLs and we'll append them to your web results. We offer two ways for you to tell us about the web pages that you want us to fetch and include in our web index, via an RSS feed (Supplemental Feed) or manually (Supplemental URLs).

### Supplemental Feed

You can use an [RSS feed](/manual/rss.html) to add URLs. The feed is useful if you'd like to automate the process, add multiple URLs, or both.

Enter the URL of your RSS feed. Click submit. We'll fetch each URL in your feed and index the title, description, *and the full text of the document* for the items you provide. We'll display the title and description you provide in the feed (not the page's title or a snippet based on the page's content), as well as a results count. Please be sure to [follow our schema](/manual/rss.html).

We'll update any items that include a publication date.

Delete a URL added via RSS feed by deleting the item from your RSS feed. We'll remove the URL from our index the next time we fetch your RSS feed. If you need to remove it from our index immediately, you do so manually within the list of URLs on the Supplemental URLs page. Search for the URL and hit `Delete`. Note that you *must also* delete the URL from your RSS feed. Otherwise, the URL will reappear the next time we fetch your RSS feed.

You can also delete *all* of the URLs added via the RSS feed by deleting the RSS feed itself.

We can't restore URLs that don't exist within your *current* feed. Please don't remove items from the feed unless you want them to be removed from the index. It's ok if the feed is long.

### Supplemental URLs

You can also manually add a a specific URL on the Supplemental URLs page. We'll fetch each URL you add manually and we'll index the title, description, *and the full text of the document* for the link you provide. We'll display the title and description you provide (not the page's title or a snippet based on the page's content).

Delete a manually added URL by selecting Delete within the list of supplemental URLs.

The source column in the crawl report shows how you added the URL, via an RSS feed or manually.

## Filter a URL

You can filter *a single URL* from the results on your site. Use it for emergency reasons only (such as spillage of classified information or unintentional publication of a page). Note that this option should be used only if the [other options](/manual/domains.html#filter) aren't feasible as it can have an undesired effect on other features such as the display of spelling suggestions and relevance ranking.

It is not meant to fix the results for entire site, such as for launch or redesign problems. For tips on how to fix these more systemic problems, read our [Checklist for a Successful Website Redesign](/blog/redesign.html).

Entire the full path of the URL, e.g. use https://www.usa.gov/Citizen/Topics/Benefits.shtml, not usa.gov/citizen/topics.

You can later use the delete option to remove the filter.

---

***Troubleshooting tip:*** We support RSS 2.0 and Atom feeds. Learn more and validate your feeds at:

* [W3C Feed Validation Service](http://validator.w3.org/feed/){% external_link %} (Atom & RSS)
* RSS 2.0 [specification](http://www.rssboard.org/rss-specification){% external_link %} and [validator](http://www.rssboard.org/rss-validator/){% external_link %}
* [Atom syndication format](http://atomenabled.org/developers/syndication/){% external_link %}

***Troubleshooting tip:*** Are you seeing an error message in the crawled URLs report for your PDF that says, "No content found in document"? Your PDF is likely an image-only, non-searchable file that was created from a paper document using a scanner. See the resources below for more information on how to create searchable PDF files.

* [Is that PDF Searchable?](http://blogs.adobe.com/acrolaw/2007/02/is_that_pdf_sea/){% external_link %} (blog post)
* [How to Create Searchable PDF File](https://acrobatusers.com/tutorials/how-to-create-a-searchable-pdf-file){% external_link %} (video)

***Troubleshooting tip:*** Are you seeing an error message in the crawled URLs report that says your page is taking too long to load? Use [Pingdom Tools Full Page Test](http://tools.pingdom.com/fpt/){% external_link %} to test the load time of your page, analyze it, and find the bottlenecks.

***Did you know?*** To help the public find your web pages when they search on Bing.com, we notify Bing about any URLs you add. While this helps with search engine optimization (SEO), it is not a cure-all. You should also register for and use commercial search engines' webmaster tools.

* [Bing Webmaster Tools](http://www.bing.com/toolbox/webmaster){% external_link %}
* [Google Webmaster Central](https://www.google.com/webmasters/tools/home?hl=en){% external_link %}
