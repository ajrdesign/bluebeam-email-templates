# Bluebeam Email Templates

This is a clone of the MailChimp templates that I'm going to use to create Bluebeam's standard templates.

## Process:

It's very important to follow this process for email production else there will be problems when the rest of the marketing team sends it out.

1. Create a copy of one of the base templates.
2. Add content/design to your template.
3. Send it off for approval/revisions.
4. Once approved run the code through this: http://beaker.mailchimp.com/inline-css NOTE: Make sure "Strip out Original CSS Style Tags" is not checked.
5. Remove all but the @media tags in the style tags. All responsive elements need to remain in the head.
6. Send that code to the responsible party.




Contents
--------

**/responsive-templates** contains a collection of responsive / mobile-friendly email templates with various layouts.

**/templates** contains a collection of fixed-width email templates with various layouts.

Responsive Templates & CSS Inlining
-----------------------------------

When inlining the CSS in the responsive templates, be sure **not** to include the styles within the media query; they should remain in the &lt;head&gt; of the email. MailChimp inlines the CSS correctly, but many services may not.

[Brought to you by MailChimp](http://www.mailchimp.com/), these email blueprints are licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).
