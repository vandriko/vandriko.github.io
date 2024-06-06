---
layout: archive
title: "Writing Style Guide"
permalink: /writing-style-guide/
author_profile: true
date: 2024-06-06
---

This is a short writing style guide I put together after spotting a number of issues repeating across many reports on all levels (BSc, MSc, PhD). Do keep in mind that this guide is not definite, and definitely biased towards my preferences. 

The points are not LaTeX-specific, except when identified as such. Remember folks, the **[Latex Wikibook](https://en.wikibooks.org/wiki/LaTeX)** is your friend! 
Check out also Diomidis Spinellis' excellent **[Advice for writing LaTeX documents](https://github.com/dspinellis/latex-advice)** but do keep in mind that some of this advice is better for paper-writing than thesis-writing.

# Labels and Floats

* Labels must Capitalize their initial letter if numbered (e.g. Chapter 1, Section 2.1, Table 3.2, Figure 4.5, etc.) but not when used without it (e.g. in the previous chapter, in the section that follows, in the table below, etc.)
* Labels and their numbers (e.g. Figure 4.3) must not be allowed to line break; in Latex always use ~ (e.g. `in~\ref{fig:Fig1})`, and/or `\mbox{}` if necessary
* Section headers (of any level) must not be allowed to page break from their content
* Sections with single subsections (e.g. Section 2.2 has only one subsection e.g. 2.2.1) must be avoided by merging the subsection into the section, removing the numbering from the subsection level, or spinning the subsection into its own section if possible
* Section numbering should finish at sub-section level; everything after that should appear as unnumbered except if the template used explicitly requests it (subsubsection at worst)
* Figures and other floats must not be orphans (i.e. alone in a page) except if absolutely necessary e.g. due to their size; putting figures into an appendix is always an option
* LaTeX works best if you let it decide where to place floats for optimizing space. Keep in mind that a manuscript is not a web page: trying to create a flow of text and floats by using `[h]` or `[H]` is simply not recommended; there is a reason why most publishers' templates allow only top placement for floats
* As above but even more so for enforcing placement with e.g. `[h!]`. Only deploy if you know exactly what you are doing and why you are doing it
* Captions must be self-descriptive and -contained

# Fonts and Special Characters

* German-style quotation marks must be used for consistency in latex: `` `quote' `` for single, and ``` ``quote'' ``` for double
* The smallest font size used **including any text in figures and tables** should not be smaller than this of footnotes; there is an exception for code listings but even then there are limits --- there's a simple rule to keep in mind: the figure should be readable when the paper/thesis is printed and held at arm's length without the reader needing to put on their reading glasses to do so
* Having pointed out the above, using font size 12 and double-spacing is easy on middle-aged eyes but basically wasteful, even if the thesis/paper is not to be printed

# Language and Structure

* Contractions (it's, we'll, they won't, etc.) are simply not allowed; the possessive apostroph (as in, look up the term's meaning) is not a contraction and it is therefore exempted
* There is no I in academic writing (pun intentional), at least not one after the 1960s/outside of philosophical essays. Use either the royal "we" or an indirect construction to indicate who did this task/experiment/etc.; at the end of the day your work is a collective effort including all authors of related work and your supervisors' contributions
* The use of 2nd person ('you') is strictly forbidden, except if you want to address the reader directly; ask yourself though: why would you need to do this? 
* Avoid the excessive use of passive voice except if necessary --- it has been overused to avoid claiming responsibility for the outcomes
* Avoid multiple nested sentences. Keep it simple
* Sentences in academic writing do not start with And, But, or Or. Probably because we want to sound sophisticated
* The use of signposting sentences (the previous chapter discussed X, this chapter discusses Y) is strongly recommended for chapter openings, and comes in handy at section openings when the previous section was too long or when the section being opened deviates the narrative flow; any use of it below this level is probably excessive and patronizing to the reader
* Keep in mind that you are telling a story; at all times the reader needs to know *what* you did, *why* it might be important for them, and *how* you went about it

# Common Mistakes
* extend is the verb (eg we extend this method), extent is the noun (eg to the extent of our knowledge)
* something consists _of_ something else, something constitutes something else (without a preposition)


