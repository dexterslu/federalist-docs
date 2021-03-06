---
permalink: /
title: About Federalist
---

Federalist is a compliant [open source](https://github.com/18F/federalist) web publishing service for the United States federal government. It provides templates for websites, an online editor for maintaining content, and access to cloud-based infrastructure for high-scale hosting, among [other features]({{site.baseurl}}/pages/included-with-federalist/).

The team at [18F](https://18f.gsa.gov/) builds and maintains it as a service available to federal government agencies. We also use Federalist to host many of our own websites.

Federalist is currently under active development. We are working with a select list of partners to test the platform and launch new websites.

## Why static websites?

Federalist generates static websites instead of using a more complex content management system (CMS) like Drupal or Wordpress. There are several advantages to static websites:

- **Less complexity and vulnerability** Avoiding CMSs means avoiding problems like maintaining dynamic server applications (no PHP or Apache / IIS) and database scaling and redundancy. Production-level static sites generally require one simple static file server or service as opposed to dozens. This means that the whole website is easier to maintain and has fewer vulnerabilities.

- **Update content without writing code** Static websites store content in simple text files that anyone on the team can edit. The Federalist editor provides a way for basic editing of these files without needing to write code.

- **Easy to host and maintain** It’s very easy to host static website files. You can easily take advantage of scaling services like Amazon S3 where you pay only for what you use.

- **Fully customizable** Designers and developers can customize static websites into whatever form they want without having to strip away CMS-provided features and defaults. Static sites can be used to build many different types of sites, from organization homepages or intranets to pre-generated web application program interfaces that display data from a separate server.

## What can I build with Federalist?

Federalist provides [ready-to-use templates]({{site.baseurl}}/pages/using-federalist/#federalist-templates) for several common website types. You can also use custom website templates based on Jekyll. 18F maintains many Jekyll-based websites that you can fork and adopt, though some must be edited directly (not via the Federalist editor).

Possible sites include:

- A simple homepage for your government organization with information about personnel and contact information.

- Data visualization sites that pull data from a separate API server (Federalist does not provide API servers)

- A single page with information about a recently released report that may receive a lot of traffic.

Here are a few examples of Federalist websites in production:

![College Scorecard]({{site.baseurl}}/uploads/college-scorecard.png)
**[The College Scorecard](https://collegescorecard.ed.gov/)**

![SBST.gov]({{site.baseurl}}/uploads/sbst.png)
**[The Social and Behavioral Sciences Team](https://sbst.gov/)**

## Getting started

If you have a project that you think would be a good fit for Federalist, [please let us know](https://docs.google.com/forms/d/1iB8aW7c9r1QH3s8XElQCrnXRGjAiPUYpWG1CMeEqGIo/viewform).
