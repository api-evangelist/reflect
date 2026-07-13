---
title: "Strategies for handling async code in Cypress"
url: "https://reflect.run/articles/strategies-for-handling-async-code-in-cypress/"
date: "2001-01-01"
feed_url: "https://reflect.run/articles/index.xml"
---
It can be difficult to determine what is executing synchronously vs asynchronously within a web application. Static assets in the page, such as images, CSS, and other media, are requested in order but can be processed either synchronously or asynchronously depending on the type of asset it is, and how it’s defined within the page. Cascading style sheets (CSS) are evaluated synchronously by the browser, but images, fonts, and videos referenced inside the CSS are loaded and display asynchronously.
