---
title: "Don't redirect HTTPS to HTTP"
---

Some websites support HTTPS URLs, but then redirect to HTTP.

Don't do this. If you have HTTPS capability, just serve the page over HTTPS.

It's even worse than not supporting HTTPS at all, because you give a false sense
of security before dropping the user to HTTP.
