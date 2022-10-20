---
title: "Project Notes"
date: 2022-10-13T13:22:28-04:00
draft: false
---

October 2022

20221020

* Fixed CloudFront by following https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started-cloudfront-overview.html
* Explicitly referred to index.html for links in header.html to get around access denied (403) errors for subdirectories serverd by cloudfront and S3
* Set up my credentials file on my linux box to use awscli
* Started reading a bit about the [Bootstrap Framework](https://getbootstrap.com/docs/4.1/getting-started/introduction/) as part of Build Websites with Hugo Chapter 2 exercises
* Looked at source of [Coder Theme](https://github.com/luizdepra/hugo-coder) for Hugo as part of Build Websites with Hugo Chapter 2 exercises
* Scanned [BUILDING A STATIC WEBSITE USING HUGO & BOOTSTRAP](https://www.noorix.com.au/blog/how-to/static-website-hugo-bootstrap-serverless-1/)


20221019

* downloaded source code of Build Websites with Hugo from https://pragprog.com/titles/bhhugo/build-websites-with-hugo/
* compared to work I had done for Chapter 2, Building a Basic Theme
* corrected ProjectRoot/themes/basic/layouts/index.html
* corrected ProjectRoot/themes/basic/layouts/_default/[baseof|single].html
* Relearned binding Hugo to an IP other than localhost (127.0.0.1) at https://ytmt-stag.com/post/00005_hugo_local_server/

20221013

* Started this little log

20221012

* Set up SSL cert w/ Amazon ACM # Add a link to tutorial
* Configured a CloudFront distribution to serve SSL for the buckets # Add a link to tutorial
* Got it working for charleshbaker.com but not www.charleshbaker.com
    * Lots of farting around w/ CloudFront and Route53 to no avail

20221010

* Set up domain to use Route 53 for DNS # Add a link to tutorial
* Set up S3 buckets for static hosting # Add a link to tutorial I used
    * charleshbaker.com
    * www.charleshbaker.com
    * set up Route 53 entries for the buckets

March 2022(?)

* Purchased domain via Google domains

