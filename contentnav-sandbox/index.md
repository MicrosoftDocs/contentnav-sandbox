---
title: Welcome
description: Docset overview
author: jeahyoun
ms.author: jeahyoun
ms.date: 08/20/2020
---

# Welcone to the Content Nav Sandbox.

This is a sandbox for testing all of the current Content Navigation Headers.

To see a specific header in action, visit the corresponding page in the Table of Contents.

## Testing changes to Content Nav

To test changes in development to a specific content navigation file, you can use a querystring parameter to specify a testing branch, similar to testing content. The parameter looks like this:

```
contentnav-branch=MY_DOCSROOT_BRANCH_NAME
```

...where your branch name may be the name of a pull request branch in DocsRoot.

[Follow this link to see how this looks in the address bar.](?content-nav=master)

## Updating this sandbox

When new content nav types are created in DocsRoot, simply copy one of the pages in this docset and update the `uhfHeaderID` parameter in the YAML front matter, like so:

```yaml
title: NEW_CONTENT_NAV_ID
description: Testing the NEW_CONTENT_NAV_IDheader.
author: ...
ms.author: ...
ms.date: ...
uhfHeaderId: NEW_CONTENT_NAV_ID
```