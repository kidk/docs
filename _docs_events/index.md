---
layout: page
title: Events
description: Information on the different methods you can use to push events to the CoScale platform.
---

Events are used to annotate data inside the CoScale platform, they provide you with an overview of what happened with your application and can speed up debugging. We suggest pushing marketing campaigns, software deploys and infrastructure changes to our platform.

## Pushing events to CoScale

* [Using command line interface]({{ site.baseurl }}/events/cli/index)

    Push events from command line with our easy to use [CLI]({{ site.baseurl }}/tools/cli/index).

* [Automation]({{ site.baseurl }}/events/automation/index)

    Integrations with [Salt]({{ site.baseurl }}/events/automation/salt), [Puppet]({{ site.baseurl }}/events/automation/puppet), and many other automation tools.

* [Cronjob monitoring / Cron wrappers]({{ site.baseurl}}/events/wrappers/index)

    Monitor cronjobs by pushing events with time spent and exitcode parameters.

* [Manually through the dashboard]({{ site.baseurl }}/dashboard/events/)

    You can manually create an event in our dashboard through the event page and graphs widgets.

## Forensic events

* [Forensics]({{ site.baseurl }}/events/forensics)

	Forensics are special events inserted by our agent to give more information when something might be going on on your server.

## Advanced

* [Custom Attributes]({{ site.baseurl }}/events/custom-attributes)

    CoScale allows you to push custom attributes together with your events, which you can then use to visualize the performance and success of your events.
