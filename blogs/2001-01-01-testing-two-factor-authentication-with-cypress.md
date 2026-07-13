---
title: "Testing two-factor authentication with Cypress"
url: "https://reflect.run/articles/testing-two-factor-authentication-with-cypress/"
date: "2001-01-01"
feed_url: "https://reflect.run/articles/index.xml"
---
Introduction Two-factor authentication (2FA) adds an extra layer of security to web applications by verifying a secondary credential beyond the user’s username and password. Common methods for issuing a two-factor challenge include: sending an email, sending an SMS, or requiring the user to enter a “time-based one-time password (TOTP)” via a mobile app like Google Authenticator or Authy . This article will cover how to automatically test these scenarios using Cypress, with a working code example for testing email-based authentication.
