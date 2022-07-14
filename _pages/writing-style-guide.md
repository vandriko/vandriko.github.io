---
layout: archive
title: "Writing Style Guide"
permalink: /writing-style-guide/
author_profile: true
date: 2019-06-21
---

This is a short writing style guide I put together after spotting a number of issues repeating across many reports on all levels (BSc, MSc, PhD). Do keep in mind that this guide is not definite, and definitely biased towards my preferences. 

The points are not LaTeX-specific, except when identified as such. Remember folks, the [Latex Wikibook](https://en.wikibooks.org/wiki/LaTeX) is your friend! 
Check out also Diomidis Spinellis' excellent [Advice for writing LaTeX documents](https://github.com/dspinellis/latex-advice) but do keep in mind that some of this advice is better for paper-writing than thesis-writing.

# Labels and Floats

* Labels must Capitalize their initial letter if numbered (e.g. Chapter 1, Section 2.1, Table 3.2, Figure 4.5, etc.) but not when used without it (e.g. in the previous chapter, in the section that follows, in the table below, etc.)
* Labels and their numbers (e.g. Figure 4.3) must not be allowed to break; in Latex always use ~ (e.g. `in~\ref{fig:Fig1})`, and/or `\mbox{}` if necessary
* Section headers (of any level) must not be allowed to page break from their content
* Sections with single subsections (e.g. Section 2.2 has only one subsection e.g. 2.2.1) must be avoided by merging the subsection into the section, removing the numbering from the subsection level, or spinning the subsection into its own section if possible
* Section numbering should finish at sub-section level; everything after that should appear as unnumbered except if the template used explicitly requests it (subsubsection at worst)
* Figures and other floats must not be orphans (i.e. alone in a page) except if absolutely necessary e.g. due to their size
* LaTeX works best if you let it decide where to place floats for optimizing space. A manuscript is not a web page: trying to create a flow of text and floats by using `[h]` or `[H]` is simply not recommended; there is a reason why most publishers' templates allow only top placement for floats
* As above but even more so for enforcing placement with e.g. `[h!]`. Only deploy if you know exactly what you are doing and why you are doing it
* Make sure that the font in any figure is at least as big as the caption size
* Captions must be self-descriptive and -contained

# Fonts and Special Characters

* German-style quotation marks must be used for consistency in latex: `` `quote' `` for single, and ``` ``quote'' ``` for double

# Language and Structure

* Contractions (it's, we'll, they won't, etc.) are not allowed; the possessive apostroph (as in, look up the word's meaning) is not a contraction and it is therefore exempted
* There is no I in academic writing, at least not one after the 1960s. Use either the royal "we" or an indirect construction to indicate who did this task/experiment/etc.
* The use of 2nd person ('you') is strictly forbidden, except if you want to address the reader directly, for whatever reason. 
* Avoid the excessive use of passive voice except if necessary --- it has been overused to avoid claiming responsibility for the outcomes.
* Avoid multiple nested sentences. Keep it simple
* Sentences in academic writing do not start with And, But, or Or. Probably because we want to sound sophisticated
* The use of signposting sentences (the previous chapter discussed X, this chapter discusses Y) is strongly recommended for chapter openings, comes in handy at section openings when the previous section was too long or when the section being opened deviates the narrative flow; any use of it below this level is probably excessive and patronizing to the reader

# Common Mistakes
* extend is the verb, extent is the noun


