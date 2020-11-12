---
date: '2020-04-07T12:00:00Z'
menu:
  shortcode-tests:
    identifier: "shortcode-test-codesample"
    name: "codesample shortcode test"
title: codesample shortcode test 
weight: 10
---

# `codesample` shortcode test

## `codesample` - `.bash` file outside `content`

{{% codesample file="codesamples/helloworld.bash" %}}

## `codesample` - `.bash` file

{{% codesample file="content/codesamples/helloworld.bash" %}}

## `codesample` - `.c` file

{{% codesample file="content/codesamples/helloworld.c" %}}

## `codesample` - `.java` file

{{% codesample file="content/codesamples/helloworld.java" %}}

## `codesample` - `.html` file

{{% codesample file="content/codesamples/helloworld.html" %}}

## `codesample` - `.txt` file

{{% codesample file="content/codesamples/helloworld.txt" %}}

## `codesample` in `tabs`

{{% tabs name="tabstest" %}}

{{< tab name="bash" >}}
{{< codesample file="content/codesamples/helloworld.bash" >}}
{{< / tab >}}

{{< tab name="c" >}}
{{< codesample file="content/codesamples/helloworld.c" >}}
{{< / tab >}}

{{< tab name="java" >}}
{{< codesample file="content/codesamples/helloworld.java" >}}
{{< / tab >}}

{{< tab name="html" >}}
{{% codesample file="content/codesamples/helloworld.html" %}}
{{< / tab >}}

{{< tab name="txt" >}}
{{% codesample file="content/codesamples/helloworld.txt" %}}
{{< / tab >}}

{{% /tabs %}}