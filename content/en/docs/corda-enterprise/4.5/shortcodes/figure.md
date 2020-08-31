---
date: '2020-04-07T12:00:00Z'
menu:
  corda-enterprise-4-5:
    identifier: "figure-shortcode-test"
    name: "figure test"
    parent: shortcode-tests
title: figure shortcode test 
weight: 20
---

# `figure` shortcode test

{{% 
   figure 
	src="images/richard.jpg"
	zoom="images/richard_big.jpg"
	caption="Richard the cat, lying on the bed. © John McFarland Campbell"
	alt="cat on bed" 
%}}

## Main as standard Markdown

![richard the cat](images/richard.jpg)

## Zoom image as standard Markdown

![richard the cat](images/richard_big.jpg)

## `figure` - with `src`, `zoom`, and `caption`

{{% 
   figure 
	src="images/richard.jpg"
	zoom="images/richard_big.jpg"
	caption="Richard the cat, lying on the bed. © John McFarland Campbell"
	alt="cat on bed" 
%}}

## `figure` - with `zoom`, and `caption`

{{< 
   figure 
	zoom="images/richard_big.jpg"
	caption="Richard the cat, lying on the bed. © John McFarland Campbell"
	alt="cat on bed" 
>}}

## `figure` - with `src`, and `caption`

{{% 
   figure 
	src="images/richard.jpg"
	caption="Richard the cat, lying on the bed. © John McFarland Campbell"
	alt="cat on bed" 
%}}

## `figure` - with `src`, and `zoom`

{{% 
   figure 
	src="images/richard.jpg"
	zoom="images/richard_big.jpg"
	alt="cat on bed" 
%}}

## `figure` - with `zoom`

{{% 
   figure 
	zoom="images/richard_big.jpg"
	alt="cat on bed" 
%}}

## `figure` - with `src`

{{% 
   figure 
	src="images/richard.jpg"
	alt="cat on bed" 
%}}

## `figure` - without named params

Please don't ever do this in production.

{{% 
   figure 
	"images/richard.jpg"
	"cat on bed" 
%}}

