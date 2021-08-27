<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Mar Reguant"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/", "franklin", "franklin.pub"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Electricity Markets Course"
website_descr = "A 5-day course on the economincs of electricity markets taught by Mar Reguant."
website_url   = "https://mreguant.github.io/em-course/"
prepath = "em-course"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
