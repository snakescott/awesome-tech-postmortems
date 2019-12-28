A curated list of awesome tech postmortem resources, inspired by and templated on
[awesome-python](https://github.com/vinta/awesome-python).

<!-- prettier-ignore-start -->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Awesome Tech Postmortems *](#awesome-tech-postmortems-)
  - [Postmortems](#postmortems)
  - [Studies](#studies)
  - [Bulk incident analysis](#bulk-incident-analysis)
  - [How to approach postmortems](#how-to-approach-postmortems)
- [Other lists of postmortems](#other-lists-of-postmortems)
- [Contributing](#contributing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!-- prettier-ignore-end -->

---

[![Build Status](https://travis-ci.org/snakescott/awesome-tech-postmortems.svg?branch=master)](https://travis-ci.org/snakescott/awesome-tech-postmortems)

# Awesome Tech Postmortems [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

The postmortems, studies, and resources curated here are those which enable learning
from incidents.

> PSA: _Incident Analysis_ is completely different than the standard postmortem process
> that you see written about in the Google SRE book and other incident marketing
> materials. It is a whole field of study and practice on extracting valuable data from
> incidents focusing on how.

[Nora Jones](https://twitter.com/anthony_darius/status/1180136290852827136)

The postmortems linked generally do not meet the bar that Jones suggests for _incident
analysis_ -- because very few (no?) tech organizations publish them. However, many of
the studies and resources linked do line up with the incident analysis perspective.

## Postmortems

- [Incident Report: Running Dry on Memory Without Noticing](https://www.honeycomb.io/blog/incident-report-running-dry-on-memory-without-noticing/)
  (2019-11-06,
  [Honeycomb](https://www.honeycomb.io/blog/incident-report-running-dry-on-memory-without-noticing/))
  - [I sat in on a Honeycomb incident review and you won't believe what we learned next](https://reading.supply/@jhscott/i-sat-in-on-a-honeycomb-incident-review-and-you-wont-believe-what-we-learned-next-zts2NE)
    (2019-11-08, Jacob Scott)
- [The Consul outage that never happened](https://about.gitlab.com/blog/2019/11/08/the-consul-outage-that-never-happened/)
  (2019-08-07, [Gitlab](https://gitlab.com))
- [We had issues with Monzo on 29th July](https://monzo.com/blog/2019/09/08/why-monzo-wasnt-working-on-july-29th)
  (2019-07-29, [Monzo](https://monzo.com))
- [Details of the Cloudflare outage on July 2, 2019](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/)
  (2019-07-02, [Cloudflare](https://www.cloudflare.com))
- [What We Learned from the Recent Mandrill Outage](https://mailchimp.com/what-we-learned-from-the-recent-mandrill-outage/)
  (2019-03-26, [Mailchimp](https://mailchimp.com/))
- [Postmortem: Azure DevOps Service Outages in October 2018](https://devblogs.microsoft.com/devopsservice/?p=17665)
  (2018-10-16, [Azure DevOps Service](https://devblogs.microsoft.com/devopsservice/))
- [Incident review: API and Dashboard outage on 10 October 2017](https://gocardless.com/blog/incident-review-api-and-dashboard-outage-on-10th-october/)
  (2017-10-10, [GoCardless](https://gocardless.com/))
- [Postmortem of database outage of January 31](https://about.gitlab.com/2017/02/10/postmortem-of-database-outage-of-january-31/)
  (2017-01-31, [GitLab](https://gitlab.com/))

## Studies

- [Approaching Overload: Diagnosis and Response to Anomalies in Complex and Automated Production Software Systems](https://etd.ohiolink.edu/!etd.send_file?accession=osu1543495231467142&disposition=attachment)
  (2018, [Marisa Grayson](https://etd.ohiolink.edu/pg_10?::NO:10:P10_ETD_SUBID:174511))
- [Report from the SNAFUcatchers Workshop on Coping With Complexity](https://snafucatchers.github.io)
  (2017-03-16, [SNAFUcatchers](https://snafucatchers.github.io))
- [Counterfactual Thinking, Rules, and The Knight Capital Accident](https://www.kitchensoap.com/2013/10/29/counterfactuals-knight-capital/)
  (2013-10-29, [John Allspaw](https://www.kitchensoap.com))

## Bulk incident analysis

- [What bugs cause production cloud incidents](https://people.cs.uchicago.edu/~shanlu/paper/hotos19_azure.pdf)
  (2019-05-13, various)
- [Incidents — Trends from the Trenches](https://m.subbu.org/incidents-trends-from-the-trenches-e2f8497d52ed)
  (2019-02-26, [Subbu Allamaraju](https://subbu.org/)/Expedia)

## How to approach postmortems

- [Learning from Incidents in Software](https://www.learningfromincidents.io/)
- [Etsy Debriefing Facilitation Guide](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf)

# Other lists of postmortems

- [danluu/post-mortems](https://github.com/danluu/post-mortems) on GitHub
- [lorin/major-incidents](https://github.com/lorin/major-incidents) on GitHub

# Contributing

Your contributions are always welcome! Please take a look at the
[contribution guidelines](https://github.com/snakescott/awesome-tech-postmortems/blob/master/CONTRIBUTING.md)
first.

I will keep some pull requests open if I'm not sure whether those resources are truly
awesome tech postmortems, you could
[vote for them](https://github.com/snakescott/awesome-tech-postmortems/pulls) by adding
:+1: to them.

---

If you have any question about this opinionated list, do not hesitate to contact me
[@jhscott](https://twitter.com/jhscott) on Twitter or open an issue on GitHub.
