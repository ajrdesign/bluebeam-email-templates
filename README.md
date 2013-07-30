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

Email Blueprints
================

[Brought to you by MailChimp](http://www.mailchimp.com/), these email blueprints are licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).

Email Blueprints is a collection of HTML email templates that can serve as a solid foundation and starting point for the design of emails. They include template language elements that make them customizable when imported into a MailChimp account, as well as merge tags that will generate dynamic content when sent through MailChimp. Not a MailChimp user? You can [sign up free](http://www.mailchimp.com/signup) or simply strip out merge tags and use these templates to send through any system.

All templates have been tested vigorously in all major email clients. If you find a bug we would greatly appreciate your patch submission to the [Github repository](https://github.com/mailchimp/Email-Blueprints/).


Contents
--------

**/responsive-templates** contains a collection of responsive / mobile-friendly email templates with various layouts.

**/templates** contains a collection of fixed-width email templates with various layouts.

Responsive Templates & CSS Inlining
-----------------------------------

When inlining the CSS in the responsive templates, be sure **not** to include the styles within the media query; they should remain in the &lt;head&gt; of the email. MailChimp inlines the CSS correctly, but many services may not.

![Bitdeli](https://d2weczhvl823v0.cloudfront.net/mailchimp/Email-Blueprints/trend.png)
