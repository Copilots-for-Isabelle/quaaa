---
layout: default
---

## About

Generative AI agents combined with proof assistants now produce mechanized
results, in mathematics, computer science, and beyond, at a scale the
theorem-proving community struggles to absorb and of widely varying quality.
This informal workshop aims to distill best practices for improving the
mechanizations’ quality and their alignment with the human formalizer’s goals.

By *quality* we mean reusability, maintainability, readability, idiomatic
style, and good use of existing libraries. By *alignment* we mean ensuring that
formal statements faithfully capture their informal counterparts, such as
theorems or specifications, and understanding what alignment should mean when
no such counterpart exists.

## Call for Submissions

We invite submissions presenting:

- exemplary (or instructively flawed) autoformalizations,
- techniques and tools for steering agents, or
- metrics and benchmarks for assessing quality and alignment.

{% if site.submission_url -%}
Submission site: <{{ site.submission_url }}>
{%- else -%}
Submission site: <span class="tbd">to be announced</span>
{%- endif %}

{% include dates.html %}

{% include program.html %}

{% include papers.html %}

{% include people.html id="organizers" title="Organizers" people=site.data.organizers %}

{% include people.html id="pc" title="Program Committee" people=site.data.pc %}
