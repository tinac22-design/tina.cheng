# Ad URL Templates: A Technical Guide

Ad URL Templates define how your website communicates with an ad server to deliver ads. They are essential for configuring ad calls across web pages, email campaigns, and video platforms. This guide explains the key concepts, ad formats, and setup procedures for creating effective templates.

---

## What is an Ad URL Template?

An **Ad URL Template** is a URL structure used to request ads from an ad server. Templates can be configured for most industry-standard third-party ad servers.  

> **Tip:** If your ad server documentation does not provide a pre-defined URL, someone with basic HTML and JavaScript knowledge can determine it.  

**Example:**

```text
http://www.exampleadserver.com/news/width=300/height=250/

---
### What is an Ad URL Template?
# Supported Ad Formats

Ad templates support several types of ad calls:

Iframe: Used on standard web pages for most front-end ads.

JavaScript: Supports dynamic ads such as expandable or interactive units.

Image: Displays ads on pages without XHTML or JavaScript support, and in email campaigns.

Raw: Returns XML creatives for video ad platforms.
