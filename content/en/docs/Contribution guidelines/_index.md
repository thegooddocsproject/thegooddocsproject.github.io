---
title: "Contribution Guidelines"
linkTitle: "Contribution Guidelines"
weight: 10
description: >
  How to contribute to The Good Docs Project
---
## Contributing to The Good Docs Project 


We’d love your help.

*   Have you noticed something that could be improved?
*   Want to share your tech writing expertise?
*   Do you have material you’d like to integrate into our baseline?
*   Do you know of research which should be referenced?
*   Something else?

Please do [reach out](contact) to us with your ideas.

Consider contributing financially. We have an [Open Collective](https://opencollective.com/thegooddocsproject/) account where you can make a one-off donation or provide ongoing support as a sponsor.


### About contributing

#### Licenses

By contributing to this project we expect you to agree to the [Developer Certificate of Origin](https://developercertificate.org/) (DCO). This document was created by the Linux Kernel community and is a simple statement that you, as a contributor, have the legal right to make the contribution, and agree to do so under the [open licenses](https://thegooddocsproject.dev/licences) we use.

#### Contributing

You can improve our documentation by submitting a pull request to our [Github templates repo](https://github.com/thegooddocsproject/templates). Here is [how](https://guides.github.com/activities/hello-world/).

For all but minor typos, it is s a good idea to discuss your proposed changes with us before submitting a pull request.

#### Issue tracker

We track outstanding work in our [github  tracker](https://github.com/thegooddocsproject/templates/issues). To keep our issue tracker manageable, we prefer you discuss suggestions or issues in one of our forums, typically our email list, before adding an issue to the tracker.

#### Style Guide

We use the [Google Style Guide](http://google.github.io/styleguide/) and American spelling, as per the [Merriam-Webster Online](https://www.merriam-webster.com/)  dictionary. If you’re used to working with such reference books, that’s great; if not, please contribute anyway, a tech writer will likely update your contribution later.



### Contributing to The Good Docs Project site


We use [Hugo](https://gohugo.io/) to format and generate our website, the
[Docsy](https://github.com/google/docsy) theme for styling and site structure, 
and [Netlify](https://www.netlify.com/) to manage the deployment of the site. 
Hugo is an open-source static site generator that provides us with templates, 
content organisation in a standard directory structure, and a website generation 
engine. You write the pages in Markdown (or HTML if you want), and Hugo wraps them up into a website.

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.


### Quick start with Netlify

Here's a quick guide to updating the docs. It assumes you're familiar with the
GitHub workflow and you're happy to use the automated preview of your doc
updates:

1. Fork the [site repo](https://github.com/thegooddocsproject/thegooddocsproject.github.io) on GitHub.
1. Make your changes and send a pull request (PR).
1. If you're not yet ready for a review, add "WIP" to the PR name to indicate 
  it's a work in progress. (**Don't** add the Hugo property 
  "draft = true" to the page front matter, because that prevents the 
  auto-deployment of the content preview described in the next point.)
1. Wait for the automated PR workflow to do some checks. When it's ready,
  you should see a comment like this: **deploy/netlify — Deploy preview ready!**
1. Click **Details** to the right of "Deploy preview ready" to see a preview
  of your updates.
1. Continue updating your doc and pushing your changes until you're happy with 
  the content.
1. When you're ready for a review, add a comment to the PR, and remove any
  "WIP" markers.

#### Updating a single page

If you've just spotted something you'd like to change while using the docs, Docsy has a shortcut for you:

1. Click **Edit this page** in the top right hand corner of the page.
1. If you don't already have an up to date fork of the project repo, you are prompted to get one - click **Fork this repository and propose changes** or **Update your Fork** to get an up to date version of the project to edit. The appropriate page in your fork is displayed in edit mode.
1. Follow the rest of the [Quick start with Netlify](#quick-start-with-netlify) process above to make, preview, and propose your changes.

#### Previewing your changes locally

If you want to run your own local Hugo server to preview your changes as you work:

1. Follow the instructions in [Getting started](/docs/getting-started) to install Hugo and any other tools you need. You'll need at least **Hugo version 0.45** (we recommend using the most recent available version), and it must be the **extended** version, which supports SCSS.
1. Fork the [site repo](https://github.com/thegooddocsproject/thegooddocsproject.github.io) repo into your own project, then create a local copy using `git clone`. Don’t forget to use `--recurse-submodules` or you won’t pull down some of the code you need to generate a working site.

    ```
    git clone --recurse-submodules --depth 1 https://github.com/google/docsy-example.git
    ```

1. Run `hugo server` in the site root directory. By default your site will be available at http://localhost:1313/. Now that you're serving your site locally, Hugo will watch for changes to the content and automatically refresh your site.
1. Continue with the usual GitHub workflow to edit files, commit them, push the
  changes up to your fork, and create a pull request.

#### Creating an issue

If you've found a problem in the docs, but you're not sure how to fix it yourself, please create an issue in the [site repo](https://github.com/thegooddocsproject/thegooddocsproject.github.io/issues). You can also create an issue about a specific page by clicking the **Create Issue** button in the top right hand corner of the page.

#### Useful resources

* [Docsy user guide](wherever it goes): All about Docsy, including how it manages navigation, look and feel, and multi-language support.
* [Hugo documentation](https://gohugo.io/documentation/): Comprehensive reference for Hugo.
* [Github Hello World!](https://guides.github.com/activities/hello-world/): A basic introduction to GitHub concepts and workflow.


