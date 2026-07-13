---
title: "How to save and restore state in Cypress tests"
url: "https://reflect.run/articles/how-to-save-and-restore-state-in-cypress-tests/"
date: "2001-01-01"
feed_url: "https://reflect.run/articles/index.xml"
---
Best Practices on Sharing State Sharing state across multiple tests is considered a bad practice. Consider the following passage from Cypress’s “Best Practices” docs : You only need to do one thing to know whether you’ve coupled your tests incorrectly, or if one test is relying on the state of a previous one. Change it to it.only on the test and refresh the browser.
