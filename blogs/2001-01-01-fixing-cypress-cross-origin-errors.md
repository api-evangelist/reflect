---
title: "Fixing Cypress cross-origin errors"
url: "https://reflect.run/articles/fixing-cypress-cross-origin-errors/"
date: "2001-01-01"
feed_url: "https://reflect.run/articles/index.xml"
---
Introduction Although older versions of Cypress did not support testing across domains, with the addition of cy.origin() in version 9.6, tests can now be created that span multiple domains. In this article, we will cover how to create cross-domain tests with Cypress using the new cy.origin() and cy.session() functions, and identify some limitations with these new commands that you may run into in your own testing. What is Cypress?
