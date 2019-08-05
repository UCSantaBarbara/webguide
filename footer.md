---
layout: default
title: Footer
permalink: /footer/
---

Each UCSB website must include a footer at the bottom of each webpage with the
elements described in this section.

### Copyright

Include this standard form copyright notice as recommended by the [UC Copyright Guide](http://copyright.universityofcalifornia.edu/).

```html
Copyright &copy; 2018 The Regents of the University of California, All Rights Reserved.
```
You may display the year of first publication or the current year using a server-side technology.

The notice format can be altered or omitted to fit your needs.

For more information about copyright requirements, visit
[UC Copyright FAQ: How do I put a copyright notice on my work?](http://copyright.universityofcalifornia.edu/faqs/index.html#h)

### Terms of Use

Each footer should include a link to the
[UCSB Terms of Use](http://www.policy.ucsb.edu/terms-of-use/).
Each website can either link directly to the [UCSB Terms of Use document](http://www.policy.ucsb.edu/terms-of-use/)
or include the content from that document on their own page using a server-side
technology.

If your organization needs to modify the Terms of Use document for a specific
purpose, you should submit the modified version for approval to
[policy@ucsb.edu](mailto:policy@ucsb.edu). If the Coordinator approves the
modified content, the updated version can be used and a copy will be retained
by Administrative Services.

### Privacy Notification

All UCSB websites that collect personal information from visitors should
include a link to the
[UCSB Privacy Notification](http://www.policy.ucsb.edu/privacy-notification/).
Anonymous information collected for the purpose of web analytics is *not*
considered personal information. Similar to the Terms of Use, each website can
either link directly to the [UCSB Privacy Policy](http://www.policy.ucsb.edu/privacy-notification/)
or include the content from that document on their own page using a server-side
technology.

The link to either the UCSB Privacy Policy or the page with the included
content should contain the word "privacy."

If your organization needs to modify the Privacy Policy document for a specific
purpose, you should submit the modified version for approval to
[policy@ucsb.edu](mailto:policy@ucsb.edu). If the Coordinator approves the
modified content, the updated version can be used and a copy will be retained
by Administrative Services.

It is a good practice to also include a link to the privacy policy close to
where a user is entering personal information. For example, a link to the
privacy policy could be added to the top of a form that a user is filling out
or next to where a user enters their username and password to log into a
secure application.

### Accessibility

Include a statement or link to a statement offering alternative content for
those who cannot access your page:

```html
If any of the material on this page is not accessible to you, please
<a href="mailto:webmaster@department.ucsb.edu">send us an email</a>
or <a href="/contact">contact us via our contact page</a>
and we will provide alternatives.
```

### Last Modified Date (Optional)

Each web page may contain the date the last time the page was updated.
The last modified date should appear in the following format:
May 4, 2018 (no month or year abbreviation)

### Contact Link

All websites should contain an email link or link to a contact form to contact
someone within the organization about questions or concerns with the website.

### "contentinfo" Landmark Role

The element containing the footer should be marked with the "contentinfo"
ARIA role:

```html
<div role="contentinfo">
    <!-- Footer Content -->
</div>
```

Or the HTML5 footer element should be used:

```html
<footer>
    <!-- Footer Content -->
</footer>
```

### Footer Example

The following example includes all of the guidelines described above:

```html
<footer>
    Copyright &copy; 2018 The Regents of the University of California,
    All Rights Reserved
    <br>
    <a href="http://www.policy.ucsb.edu/terms-of-use/">Terms of Use</a> /
    <a href="http://www.policy.ucsb.edu/privacy-notification/">Privacy Notification</a> /
    <a href="/accessibility">Accessibility</a>
    <br>
    Last Modified May 4, 2018 /
    Questions or contacts? Please <a href="/contact">contact us</a>
</footer>
```
