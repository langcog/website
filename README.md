# website
the lab website

visible at http://langcog.stanford.edu

pub browser lightly adapted (with gratitude) from https://github.com/monperrus/bibtexbrowser.

-----

Note that running locally and at Stanford are different: at Stanford, cgi-bin stuff needs to go below `WWW` (the repository root) in the directory hierarchy. This isn't easy to support within the repository. The hack is just to copy two files, `citations.bib` and `bibtexbrowser.local.php` into `../cgi-bin` if you pull.