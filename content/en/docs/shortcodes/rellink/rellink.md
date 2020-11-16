---
date: '2020-04-07T12:00:00Z'
menu:
  shortcode-tests:
    identifier: "shortcode-tests-includefile-relative-child"
    name: "Relative link demo (child)"
    parent: "shortcode-tests-includefile-relative"
title: Relative link demo (child)
weight: 30
---

# Relative link demo (child)

The next pargraph is an included file. It contains a relative link to the Corda Enterprise 4.0 documentation, but this link is broken.


{{% includefile file="snippets/link.md" %}}

It is broken in this page because that link is relative to this page. The link is *not* relative to the included file. This page is one level deeper than the other page.