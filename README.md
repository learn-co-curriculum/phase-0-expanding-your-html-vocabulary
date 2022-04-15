# Expanding Your HTML Vocabulary via MDN

## Learning Goals

- Identify the Mozilla Foundation and MDN
- Navigate the MDN Reference Guide

## Introduction

Because of the pace of change in web technologies, it often feels like as soon
as you learn something it's already obsolete. How can a developer stay
up-to-date? Developers need to be able to reference the latest documentation in
a just-in-time fashion.

When you have a question, you should consult the best source, take what you
need, and use it. The purpose of this README is to help you get oriented with a
popular source of HTML documentation, the [Mozilla Developer Network
(MDN)][mdn].

## Identify the Mozilla Foundation and MDN

The Mozilla Foundation is an open-source company that has a long history with
browsers and browser technology.

Mozilla is a reliable reference for the latest HTML tags. There are many other
sites online that exist to discuss these tags, but when you want a thorough
explanation of a tag, Mozilla is often a great choice.

There are some drawbacks in using MDN. Because Mozilla is so trusted, their
information tends to be ... _exhaustive_. Because it's so _ahem_ thorough, it
can sometimes be hard to digest. Their information tends to be for _reference_,
not _tutorial_ purposes.

Drawbacks aside, MDN is a good solid starting place for research and it can take
you from "Does something like this exist?" to "Now I know that this thing
exists, maybe I can find a tutorial!"

## Navigate the MDN Reference Guide

The [MDN HTML Reference Guide][mdn-html-reference] is a list of HTML tags
grouped together by their functions. These sections are not entirely "human
readable," which makes it a bit difficult to understand where to start looking.
Some of the headings are very technical-sounding.

To help you find what you need in this listing, we've created this helpful table
to help you convert **between** MDN-ese and the HTML terms you have learned. We've
also listed only the MDN content sections that you're most likely to use:

| MDN Section Title     | Human-Friendly Section Title                                                            | Summary                                                                                                                                                                                                                                         |
| --------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Main Root             | The `html` tag                                                                          | _The `html` tag and that's it!_                                                                                                                                                                                                                 |
| Document metadata     | Website data that goes in the `head` tag                                                | _Metadata contains information about the page. Information about styles, scripts and data to help software (search engines, browsers, etc.) use and render the page._                                                                           |
| Sectioning Root       | The `body` tag                                                                          | _The `body` tag and that's it!_                                                                                                                                                                                                                 |
| Content sectioning    | Headings, titles, divs, sections, footers, etc.                                         | _Content sectioning elements allow you to organize the document content into logical pieces._                                                                                                                                                   |
| Text content          | Formatting/structure for text: paragraphs, list items, horizontal rules, blockquotes, etc.    | _Use HTML text content elements to organize blocks or sections of content placed between the opening and closing `body` tags ... [to] identify the purpose or structure of that content._                                                                                                                  |
| Inline text semantics | Citation, emphasis, underlines, etc.                                                    | _Use the HTML inline text semantics to define the meaning, structure, or style of a word, line, or any arbitrary piece of text._                                                                                                                |
| Image and multimedia  | Adding pictures and media!                                                              | _HTML supports various multimedia resources such as images, audio, and video._                                                                                                                                                                  |
| Embedded content      | Advanced: Using material hosted elsewhere on other servers, `iframe` is the biggie here | _In addition to regular multimedia content, HTML can include a variety of other content, even if it's not always easy to interact with._                                                                                                        |
| Scripting             | Advanced: JavaScript and Drawing Support (Vector Graphics)                              | _In order to create dynamic content and Web applications, HTML supports the use of scripting languages, most prominently JavaScript. Certain elements support this capability._                                                                 |
| Table content         | Tables                                                                                  | _Tables_                                                                                                                                                                                                                                        |
| Forms                 | Advanced: Tags for building forms for sign-up or login, for example                     | _HTML provides a number of elements that can be used together to create forms which the user can fill out and submit to the Web site or application. There's a great deal of further information about this available in the HTML forms guide._ |

## Conclusion

As developers, we will often feel uncomfortable with the fact that the
technologies we depend on are always growing and changing. With authoritative
guides like [MDN][mdn-html-tutorial], we have found out that we can learn just
the little bit we need as we need it.

[mdn]: https://developer.mozilla.org/en-US/docs/Web/HTML
[mdn-html-reference]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
[mdn-html-tutorial]: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
