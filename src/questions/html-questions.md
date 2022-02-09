---
title: HTML Questions
layout: layouts/page.njk
permalink: /questions/html-questions/index.html
---

* What does a `doctype` do?
*** information for the browser to denote what type of document to expect.

* How do you serve a page with content in multiple languages?
*** you can add lang tags to elements

* What kind of things must you be wary of when designing or developing for multilingual sites?
*** make language switcher easy to find, let visitors choose language, autodetect language, account for text expansions in css, font compatibility, date formatting, 

* What are `data-` attributes good for?
*** store data and can use getAttribute() to get that data

* Consider HTML5 as an open web platform. What are the building blocks of HTML5?


* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
*** session storage exists only as long as that session does, i.e. the tab. Local storage stays on that machine on that browser until deleted. A cookie has a lot less storage, can expire and sent with every HTTP request.

* Describe the difference between `<script>`, `<script async>` and `<script defer>`.
*** <script> fetched and executed immediately. <script async> fetched in parallel and executed as soon as it is available. <script defer> fetched in parallel and executed when the page has finished parsing.

* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
*** Links in head allow page to render progressively. script before body will block html parsing while they are being downloaded and executed

* What is progressive rendering?
*** techniques to improve performance of a webpage to render content for display as quickly as possible. images on the page are not loaded all at once. javascript will be used to load an image when the user scrolls to that part. include minimum css necessary for the amount of page that would be rednered. async html - render more things after other tags are rendered or executed.

* Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
*** one or more strings, comma separated, indicating possible image sources. 

* Have you used different HTML templating languages before?
** No. But I know of some, Jade, Liquid. they are similar in functionality.

* What is the difference between `canvas` and `svg`?


* What are empty elements in HTML ?
*** elements that cannot have children

