# GBIF.org feedback
This repository collects feedback sent via the [GBIF.org](https://www.gbif.org) website as Github issues.

From here issues might be moved to their relevant projects (e.g. [checklistbank](https://github.com/gbif/checklistbank)), but most remain here until resolved.

Content, data content and question issues stay in this repository until addressed.

_It is our goal that issues in this repository are addressed and closed and no issues remain open._

## Flow

The user creates an issue and classifies it as well as they can with either: bug, content, question or idea.

The issue is automatically labeled `Under review`. The `Under review` is added to avoid spam being exposed on the website and to make sure issues are addressed.

When removing `Under review` the issue should be labelled according to the area responsible.
The current broad responsibility areas are:

* `portal`: issues that have to do with presentation and bugs in the website.
* `api`: issues related to GBIF's APIs (image cache, registry, occurrence, directory etc.), ingestion (crawling, interpreting, indexing) or downloads.
* `data-content`: issues with data provided to us by publishers; typically requiring the publisher to resolve them.
* `content`: issues with CMS data: text, images, articles, help and so on
* `question`: helpdesk questions

So the procedure is:

* validate the issue.
* add appropriate labels.
* if the issue is a complete duplicate, close it with reference to the earlier issue.
* (some issues are moved, this is more useful for ideas or requests for major changes.)

## Public labels
content issues that are labelled `public relevance` are public.

## Other labels
The label `blocked` is used when awaiting a response from the issue reporter, or data publisher.

## Data content, content and questions
Since these issues reside in the repo they will probably need more labels. Data content issues can be tagged with a country/region code.

## Notifications
You can change how and how often to be notified of activity here:
https://github.com/settings/notifications

See all notifications here:
https://github.com/notifications

and ask to be notified by using the eye in the top here:
https://github.com/gbif/portal-feedback

[see screenshot](https://gbif.box.com/s/wn685mdaxul687qo9d7x8gh4oiz4f78u)

## What will show on the site
Issues that are labeled `content` and do not have a `Under review` label will be visible on the site on the page the issue was created. The fbitem[hash] refers to the url. 

This isn't an ideal solution, but it works for now and seems to be robust when using the Github search API.
