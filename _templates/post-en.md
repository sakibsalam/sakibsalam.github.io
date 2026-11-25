---
layout: post
title: "Title goes here"
date: 2026-12-01 20:00:00-0600
description: "One sentence that appears under the title on the blog page."
tags: [math]
ref: my-post-slug
---

Start writing here. Regular Markdown works: *italics*, **bold**, [links](https://example.com), lists, and quotes.

Inline math sits inside a sentence like this: $$ \hat{\beta} = (X^\top X)^{-1} X^\top y $$.

Display math goes in its own paragraph:

$$
p(\gamma \mid y) \propto p(y \mid \gamma)\, p(\gamma)
$$

> A quote, if you want one.

An image (put the file in assets/img/blog/ first):

![What the picture shows]({{ '/assets/img/blog/example.png' | relative_url }})
