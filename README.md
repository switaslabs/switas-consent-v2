# Switas Consent Widget v2

[![License](https://img.shields.io/github/license/switaslabs/switas-consent-v2)](LICENSE)

## Overview

The **Switas Consent Widget v2** is a free, open-source solution to help websites comply with privacy laws and regulations. This widget provides a customizable and user-friendly way to obtain and manage user consent for cookies and other tracking technologies.

## Features
 
- **Free to use:** It is always free to use and feel free to ask about integrations also.
- **Easy Integration:** Simple to add to any website with minimal configuration.
- **Customizable Design:** Easily adjust the look and feel to match your website's branding.
- **User-Friendly:** Clear and straightforward interface for users to give or withdraw consent.
- **Compliance Ready:** Helps ensure your site meets privacy regulations such as GDPR and CCPA.
- **Lightweight:** Minimal impact on website performance.

## Installation

### Manual Integration

1. **Visit the Consent Generator**
   Go to our [Free Consent Generator](https://www.switas.com/tools/free-consent-generator) to customize and generate your consent widget script.

2. **Generate Your Script**
   Follow the instructions on the consent generator page to customize your widget. Once you've configured your settings, you'll receive a script to include in your website.

3. **Include the Script**
   Add the generated script to the `<head>` section of your HTML:

```html
<script type="text/plain" data-cookie-consent="strictly-necessary" src="/js/login-session.js"></script>
<script type="text/plain" data-cookie-consent="tracking">
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
ga('create', GOOGLE_PROPERTY_ID_GOES_HERE, 'auto');
ga('send', 'pageview');
</script>
