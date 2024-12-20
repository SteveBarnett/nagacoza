---
title: More accessible headings
layout: post
description: We can make our headings more accessible by checking their usage, nesting, and order.
image: /img/2022/12/mah.png
category: "how-to guide"
---

We can make our headings more accessible by checking their usage, nesting, and order.

Headings are used by:

- search engines to figure out what’s on the page;
- screen reader users to hear what’s on the page, and to jump to a section of the page;
- sighted users who are visually scanning a page.

## 1. Plan out our headings

- What’s the topic or purpose of this page? That text should be in an `h1` near the top of the page.
- What are the sections of the page? The name of each section should be in an `h2`, at the start of the section.
- What (if any) are the subsections of each section? The name of each subsection should be in an `h3`, at the start of the subsection.
- What (if any) are the sub-subsections of each subsection? The name of each sub-subsection should be in an `h4`, at the start of the sub-subsection.
- And so on.

The list of headings should read a bit like a table of contents for the page.

“Section”s here refer to logically distinct pieces of the page. If we’re using headings well, we can use `div`s or `section`s and the end result is essentially the same (in terms of accessibility). See [Scott O’Hara’s Accessibility of the section element](https://www.scottohara.me/blog/2021/07/16/section.html) for more detail.

## 2. Check our headings

### High-level checks

Headings divide the page into meaningfully named sections, increasing one level at a time.

### Detailed Page-level Acceptance Criteria

- Page should contain an `h1`.
- Page should contain only one `h1`.
- `h1` **must** describe the topic or purpose of the page.
- `h1` should be similar to the `title`.
- `h1` could be the first heading on the page.
- Headings should only increase by one level down each branch of the DOM.
- Headings **must** describe the topic or purpose of content immediately after it.
- Heading elements **must** only be used semantically, not for presentation.

Note: check text that looks like a heading but is not a heading element. Should it be a heading element? Should it look like body copy?

## Summary

People use headings to scan the page. Some people use them as additional navigation aids too.

We can make our headings more accessible by checking their usage, nesting, and order.
