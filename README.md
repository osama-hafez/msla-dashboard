# State of MSAs — Dashboard

A public dashboard of Muslim Student Association (MSA) event activity across
Ontario campuses, built by [MSLA](https://muslimstudentleaders.ca) (Muslim Student
Leaders & Alumni).

**Live:** https://osama-hafez.github.io/msla-dashboard/

## What it shows

1,067 events extracted from ~1 year of public Instagram posts across 8 MSAs —
event types, per-MSA activity, a monthly activity timeline, audience, and
engagement. Click an MSA to see its own page; every event links back to its
original Instagram post.

## How it's made

Public Instagram flyers/captions → structured events via an AI vision extractor →
this dashboard. It's a static, self-contained HTML file (data embedded as JSON).
Source pipeline lives in a separate repo.

_Data is derived from public Instagram posts and links back to each source. This
is a "links-only" build — flyer images are not rehosted._
