<!--
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
-->
@def website_title = "Shark Fin Cove"
@def website_descr = "All the info you could ever want to know about Shark Fin Cove located in Santa Cruz / Davenport California"
@def website_url   = "https://sharkfincove.org"

@def author = "<a href='https://scholar.harvard.edu/logankilpatrick'>Logan Kilpatrick</a> & <a href='https://github.com/CA-Beaches/sharkfincove/graphs/contributors'>Contributors</a>"

@def mintoclevel = 2

<!--
Add here files or directories that should be ignored by Franklin, otherwise
these files might be copied and, if markdown, processed by Franklin which
you might not want. Indicate directories by ending the name with a `/`.
-->
@def ignore = ["node_modules/", "franklin", "franklin.pub"]

<!--
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
