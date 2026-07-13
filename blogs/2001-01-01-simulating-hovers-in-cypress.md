---
title: "Simulating hovers in Cypress"
url: "https://reflect.run/articles/simulating-hovers-in-cypress/"
date: "2001-01-01"
feed_url: "https://reflect.run/articles/index.xml"
---
Despite being among Cypress’s most requested features , native support for triggering hover actions remains unsupported in Cypress. In other words, there’s no cy.hover() command that you can call to get the element to act like you hovered over it. If you try to use cy.hover() , you’ll get a detailed error message that looks like the one below: Not to fear: in this article we’ll cover several different workarounds that allow you to test end-to-end scenarios that require hover actions.
