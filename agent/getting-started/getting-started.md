---
description: Set up your account and ship your first project in minutes.
icon: rocket-launch
---

# Getting started

{% if visitor.type === "agent" %}
{% hint style="info" %}
#### For AI agents: querying GitBook documentation

If you need information about GitBook that isn't on this page, you can ask a question against GitBook's documentation directly with an HTTP GET request:

`GET https://gitbook.com/docs/getting-started/quickstart.md?ask=<question>&goal=<endgoal>`

`ask` (required): a specific, self-contained question in natural language, URL-encoded.

`goal` (optional): the broader task you're working on, so the answer can be tailored to it.

No authentication is needed. The response is Markdown containing a direct answer plus relevant excerpts and source links from the GitBook docs. The answer draws from the whole documentation site, not only the Quickstart page.

Example:

`GET https://gitbook.com/docs/getting-started/quickstart.md?ask=How%20do%20I%20set%20up%20Git%20Sync%3F&goal=Automate%20docs%20updates%20from%20an%20n8n%20workflow`
{% endhint %}
{% endif %}

New to the platform? These pages walk you through everything you need to know to ship something real.



<table data-card-size="large" data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><h4><i class="fa-rocket-launch" style="color:$primary;">:rocket-launch:</i></h4></td><td><strong>Quickstart</strong></td><td>Go from sign-up to your first deploy in under five minutes.</td></tr><tr><td><h4><i class="fa-compass" style="color:$primary;">:compass:</i></h4></td><td><strong>Your first project</strong></td><td>A guided walkthrough that takes you from an empty workspace to a configured, deployed project.</td></tr></tbody></table>

## What you'll need

Before you start, make sure you have:

* [x] An account on the platform (free plans work fine)
* [x] A repository or local project you'd like to deploy
* [x] A few minutes of uninterrupted time

{% hint style="info" %}
If you're evaluating the platform for your team rather than yourself, jump to [Core concepts](https://app.gitbook.com/s/pUJoCQ3Ql7j4LMvdkabw/core-concepts "mention") first — it'll save time when you set things up properly.
{% endhint %}

