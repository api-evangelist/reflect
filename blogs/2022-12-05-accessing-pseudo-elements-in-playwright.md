---
title: "Accessing pseudo-elements in Playwright"
url: "https://reflect.run/articles/accessing-pseudo-elements-in-playwright/"
date: "2022-12-05"
author: ""
feed_url: "https://reflect.run/articles/index.xml"
---
<p>Pseudo-elements are one of the stranger constructs supported in the HTML and CSS specs. Pseudo-elements don&rsquo;t just modify the styling of an existing element, but can also <strong>add</strong> content to the page. But unlike a normal element, pseudo-elements are not considered a distinct node within the Document Object Model (DOM) and thus cannot be accessed through the <code>querySelector
