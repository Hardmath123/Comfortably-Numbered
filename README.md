Comfortably-Numbered
====================

**Ok, so I'm not developing this one anymore--but I'm leaving this up because it's pretty useful for GAE reference. Go check out [Hardmath123/shock](http://www.github.com/Hardmath123/shock), which powers the new-and-improved CN at [hardmath123.github.io](hardmath123.github.io).**

My blog: http://comfortablynumbered.appspot.com

Comfortably Numbered runs on GAE, with the following awesome libraries:
- PrismJS for Syntax Highlighting
- Markdown for comments
- MathJAX for LaTeX
- PyRSS2Gen for the RSS feed

To run it yourself, `git clone` the repo and create the file `settings.py`, with the content `ADMINS = ["an_admin_email@addess"]`. Then run with the GAE SDK.

To test a post, view `/post/?test=NAME`, where `NAME-test.html` resides in the root directory.
