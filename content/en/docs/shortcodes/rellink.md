---
date: '2020-04-07T12:00:00Z'
menu:
  shortcode-tests:
    identifier: "shortcode-tests-includefile-relative"
    name: "Relative link demo"
    parent: "shortcode-tests-includefile"
title: Relative link demo
weight: 30
---

# Relative link demo

The next pargraph is an included file. It contains a relative link to the Corda Enterprise 4.0 documentation.


{{% includefile file="snippets/link.md" %}}

It works in this page because that link is relative to this page. The link is *not* relative to the included file.

[This page](rellink/rellink.md) is one directory deeper, and it includes exactly the same file, but the link is broken there.