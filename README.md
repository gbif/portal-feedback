# Portal feedback
This repository is used by the portal project to log user generated issues via the portal.
From here issues will be moved to their relevant projects or otherwise closed.
Content issues and helpdesk questions can stay in the repo for now.

## Flow

The user creates an issue and classify it as well as they can with either: bug, content, question or idea.

The issue is automatically labeled "Needs validation". The "Needs validation" is added to avoid spam being exposed on the website and to make sure issues are addressed.

When removing "Needs validation" the issue should be assigned to a responsibility area or closed with a resolution label.
The current responsibility areas are: portal, api, content, question.

* portal: issues that have to do with the presentation and bugs in behaviour.
* api: the portal is driven of our APIs. image cache, registry, occurrence, directory etc. issues related to the apis should be labeled as such.
* content: this is issues that are not about have we process the data, but about the data provided. either by publishers or what we write in our CMS (Drupal).
* question: helpdesk questions

Resolution labels are:

* done - ideally reference to commit
* duplicate (refer to the duplicate)
* invalid (cannot reproduce, incomplete info etc)
* wontfix

So the procedure is:

* validate the issue.
* add appropriate labels
* (for portal and api) move to relevant repo and resolve

## Notifications
You can change how and how often to be notified of activity here:
https://github.com/settings/notifications

See all notifications here:
https://github.com/notifications

and ask to be notified by using the eye in the top here:
https://github.com/gbif/portal-feedback

[see screenshot](https://gbif.box.com/s/wn685mdaxul687qo9d7x8gh4oiz4f78u)

## What will show on the site
Issues that are labeled "content" and do not have a "Needs validation" label will be visible on the site on the page the issue was created.
The fbitem[hash] refers to the url. 
This isn't an ideal solution, but it works for now and seems to be robust when using hte Github search API.
