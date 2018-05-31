# Expanding Your HTML Vocabulary via MDN

## Problem Statement

As a technologist the technologies will always be vaster than our experience of
them. Moreover, they will always be expanding! How can a developer stay
up-to-date with the state of the technologies they use? As a developer you must
be able to reference state-of-the-art documentation in a just-in-time fashion.
That is, when you have a question, you should consult an authoritative source,
take what you need, and integrate it. The purpose of this README is to help you
get oriented with the primary source of HTML documentation, the
[Mozilla Developer Network (MDN)][MDN].

## Learning Objectives

1. Introduce Mozilla Foundation and MDN
2. Navigate the MDN Reference Guide

## Introduce Mozilla Foundation and MDN

The Mozilla Foundation is an open-source organization that has a long history
with browsers and browser technology. In fact, there's a direct familial
relationship between Mozilla and the first commercial web browser, Netscape
Navigator.

Mozilla has established itself as a reliable source for the latest HTML tags.
There are many other sites online that exist to discuss these tags, but when you 
want a thorough, no-frills explanation of a tag, Mozilla is your best bet. 
Because Mozilla is so trusted, their information tends to be ... _exhaustive_. 
Because it's so *ahem* thorough, it can, occasionally, be a bit hard to digest. 
Additionally, the information tends to be for _reference_ and not _tutorial_ purposes.

Nevertheless, MDN is a good solid starting place for research and it can take you
from "Does something like this exist" to "Now I know this thing exists!"

## Navigate the MDN Reference Guide

The [MDN HTML Reference Guide][MDN] is an alphabetical list of HTML tags
grouped together by their functions. These sections are not entirely "human
readable", which makes it a bit difficult to understand where to start looking. 
Some of the headings are very technical-sounding. To help you find what you need 
here, we've created this helpful table to help you convert between MDN-ese and 
the terms you have learned thus far. We've also simplified _all_ the MDN content 
to the sections that you're most likely to use:

_Summary of the MDN HTML reference guide_

|MDN Section Title|Human-Friendly Section Title|Summary|
|------|------|------|
|**Main Root**|The `<html>` tag|The `<html>` tag and that's it!|
|**Document metadata**| Website data that goes in the `<head>` tag | *Metadata contains information about the page. This includes information about styles, scripts and data to help software (search engines, browsers, etc.) use and render the page. Metadata for styles and scripts may be defined in the page or link to another file that has the information.*|
|**Sectioning Root**|The `<body>` tag|The `<body>` tag and that's it!|
|**Content sectioning**| Headings, titles, division, sections, footers, etc. | *Content sectioning elements allow you to organize the document content into logical pieces. Use the sectioning elements to create a broad outline for your page content, including header and footer navigation, and heading elements to identify sections of content.*|
|**Text content**| Formatting for text: list items, horizontal rules, figures listings for under images| *Use HTML text content elements to organize blocks or sections of content placed between the opening <body> and closing </body> tags. Important for accessibility and SEO, these elements identify the purpose or structure of that content.*|
|**Inline text semantics**| Citation, emphasis, underlines, etc. | *Use the HTML inline text semantic to define the meaning, structure, or style of a word, line, or any arbitrary piece of text.*|
|**Image and multimedia**| Adding pictures and media! | *HTML supports various multimedia resources such as images, audio, and video.*|
|**Embedded content**| Advanced: Using material hosted elsewhere on other servers, `<iframe>` is the biggie here | *In addition to regular multimedia content, HTML can include a variety of other content, even if it's not always easy to interact with.*|
|**Scripting**| Advanced: JavaScript and Drawing Support (Vector Graphics) | *In order to create dynamic content and Web applications, HTML supports the use of scripting languages, most prominently JavaScript. Certain elements support this capability.*|
|**Table content**| Tables | *The elements here are used to create and handle data best shown in tables.*|
|**Forms**|Advanced: Tags for building forms for sign-up or login, for example  | *HTML provides a number of elements which can be used together to create forms which the user can fill out and submit to the Web site or application. There's a great deal of further information about this available in the HTML forms guide.*|

## Conclusion

As developers we will often feel uncomfortable with the fact that the
technologies we depend on are always growing and changing. With authoritative
guides like [MDN][], we have found out that we can learn just the little bit we
need as we need it.

[MDN]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
