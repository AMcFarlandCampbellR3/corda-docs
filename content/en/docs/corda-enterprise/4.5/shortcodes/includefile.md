---
date: '2020-04-07T12:00:00Z'
menu:
  corda-enterprise-4-5:
    identifier: "includefile-test"
    name: "Includefile test"
    parent: shortcode-tests
title: Includefile test 
weight: 30
---

# `includefile` test

## Trivial `includefile`

{{% includefile file="content/codesamples/helloworld.md" %}}

## `includefile` wrapped in a `highlight`

This doesn't work - look at the quotes on line 2.

{{% highlight bash "linenos=table" %}}
{{< includefile file="content/codesamples/helloworld.bash" >}}
{{% / highlight %}}

### What I really want

{{< highlight bash "linenos=table" >}}
#! /usr/bin/bash
echo "Hello world!"
{{< / highlight >}}