---
layout: post
title: "screening tips: red flags edition 🚩"
description: tips for quickly identifying abstracts to exclude
tags: review
giscus_comments: true
date: 2024-11-01
featured: true
published: true
---

- I usually start off with the quickest elements that will exclude an article, and that are the easiest/quickest to locate.
- Most often that is the participant criteria. I will look for “**Methods:** ” or “Participants:” or “Sample:” or sometimes in “Objectives/Aim” and look at the sample and whether or not it meets the eligibility criteria. Usually you can locate this section relatively quickly, as it is often right after the intro (1-2 sentences) and will be the first number that appears in an abstract (usually the sample size or mean age of sample)
  - This is a good place to find the diagnostic/age criteria is met if applicable (children vs. adults)
- Use highlights for search terms if available in your platform!! This will help identify key terms quickly and screen faster!

1. **Conference Proceedings:**

- If you see something like 
> [...] **60th** **Annual** National **Conference** of All India Occupational Therapists Association (AIOTA), (OTICON 2023), **February 2-5, 2023** after the main part of the title, then it is also conference proceedings
  
  - Look for keywords like “proceedings,” “conference,” “symposium,” “meeting,” “workshop,” or abbreviations like “Conf,” “Symp,” “Proc,” followed by a location and date.
  - Examples: “**Proceedings** of the **23rd** International Conference on...” or “Symposium on XYZ, held in...”
- If you see something like this before the title, then it is most often an abstract submitted for a conference presentation (exclude because not peer-reviewed): T50. Or S49 (usually 1 letter followed by a 2-digit number)
  - Indicators in titles or citations, such as “**T50**” or “**S49**” (letter followed by a number), which often denote session numbers.

1. **Dissertations and Theses:**

- Identify keywords like “dissertation,” “thesis,” “Ph.D.,” “M.A.,” or “doctoral.”
- Examples: “Master’s Thesis, University of...” or “Ph.D. Dissertation, Department of...”

1. **Books and Book Chapters:**

- Look for terms like “chapter,” “section,” “handbook,” “guide,” “edited by,” or “published by.”
- Examples: “**Chapter** 4 in...” or “**Handbook** of Cognitive Science...”
- Most books won’t have a doi, just an ISSN or ISBN number (unless it’s super recent?)
- Sometimes the title of book or chapters will be very brief and non-descriptive
  - Journal articles are often required to be as specific and descriptive as possible

1. **Non-Peer-Reviewed Sources:**

- Identify keywords like “**editorial**,” “**opinion**,” “**commentary**,” “**letter to the editor**,” “perspective,” or “review” (if not systematic).
- Examples: “Editorial: The Future of...” or “Letter to the Editor regarding...”
- Also non-peered-reviewed sources are manual, guide, list of resources, report, handbook, program

1. **News Articles and Magazine Pieces:**

- Look for publication names that are newspapers, magazines, or other media outlets.
- Examples: “Published in The New York Times,” “Article in Time Magazine...”
- Red flag: articles without a doi (unless it’s a book)

1. **Language and Accessibility:**

- Exclude abstracts in languages not covered by the review unless translation is feasible.
- Examples: “Published in Spanish” if the review only includes English-language studies.

1. **Publication Status:**

- Exclude abstracts with statuses like “in press,” “forthcoming,” or “submitted.”
- Examples: “Article in press,” “Forthcoming in Journal of...”
- If you see an abstract written in the **future-tense** like “we will recruit 50 participants”, or if the title includes “**protocol**”, then it is excluded because it has not data collection (no results published)
  - If you do not see any quantitative data in the abstract, as in results inside brackets, that is also a good indicator (unless it’s a qualitative study). For example: (_M_ = 39.9, _SD_ = 5.9)

1. **Year of Publication:**

- Filter out articles published outside the specified date range of the review.
- Examples: “Published in 1999” when the review covers 2000-2023.

1. **Non-Empirical Studies:**

- Exclude theoretical papers, narrative reviews, or non-empirical discussions.
- Examples: “A theoretical exploration of...” or “Narrative review of...”

1. **Case Studies**

- If the abstract mentions only one participant or “the story of…” or “vignette”
- Case studies are often excluded

1. **Recommended Citation**

- If you look at the recommended citation at the end of an article, this might provide more information that could exclude it if you know well citation formatting styles

# Optionally, you can add a table of contents to your post.
# NOTES:
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
#   - we may want to automate TOC generation in the future using
#     jekyll-toc plugin (https://github.com/toshimaru/jekyll-toc).
toc:
  - name: Equations
    # if a section has subsections, you can add them as follows:
    # subsections:
    #   - name: Example Child Subsection 1
    #   - name: Example Child Subsection 2
  - name: Citations
  - name: Footnotes
  - name: Code Blocks
  - name: Interactive Plots
  - name: Layouts
  - name: Other Typography?

# Below is an example of injecting additional post-specific styles.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }
---

## Details boxes

Details boxes are collapsible boxes which hide additional information from the user. They can be added with the `details` liquid tag:

{% details Click here to know more %}
Additional details, where math $$ 2x - 1 $$ and `code` is rendered correctly.
{% enddetails %}

---

## Other Typography?

Emphasis, aka italics, with _asterisks_ (`*asterisks*`) or _underscores_ (`_underscores_`).

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

1. First ordered list item
2. Another item
   ⋅⋅\* Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
   ⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

- Unordered list can use asterisks

* Or minuses

- Or pluses

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

Colons can be used to align columns.

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a _separate paragraph_.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the _same paragraph_.
