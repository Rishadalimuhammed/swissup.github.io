---
layout: default
title: GDPR Changelog
description: GDPR changelog
keywords: gdpr changelog
category: GDPR
---

# Changelog

### Version 1.3.8

> Aug 7, 2020

 -  Fixed ability to translate `I accept following cookies: ...` phrase via
    admin configuration _Stores > Configuration > Swissup > GDPR > Personal Data Consents > Cookie Consents_
 -  Do not show empty "Cookie Settings" on "Privacy Tools" page when it's disabled.

### Version 1.3.7

> Aug 5, 2020

 -  PHP 7.4 compatibility.
 -  Allow to translate cookie title and description via i18n files.
 -  Do not show cookie bar until scripts are ready.
 -  Fixed newsletter signup styles in Magento 2.4.
 -  Place consents before captcha/recaptcha field.

### Version 1.3.3

> Jun 18, 2020

 -  Fixed DB error when customer logging in.

### Version 1.3.2

> May 7, 2020

 -  16 locales added to translate backend and frontend phrases:
    - Arabic
    - Chinese
    - Dutch
    - French
    - Hebrew
    - Italian
    - German
    - Japanese
    - Norwegian
    - Korean
    - Polish
    - Portuguese
    - Russian
    - Spanish
    - Swedish
    - Ukrainian

### Version 1.3.1

> Apr 27, 2020

 -  Fixed error during static content deploy when theme buttons use gradient for background.
 -  Fixed cookie bar positioning when theme uses margins on page-wrapper.

### Version 1.3.0

> Apr 17, 2020

{% include gallery.html images=site.data.gallery.m2.gdpr.changelog.v140 class="phone-up-2 tablet-up-3 photoswipe scroll" %}

**Cookie consent feature added. Here is some highlights of the new feature:**

 -  Cookie bar banner in minimalistic and full display modes.
 -  Separate page to control cookie settings.
 -  Cookie settings at customer account page.
 -  When the user creates an account, guest cookie consent automatically links
    with this account.
 -  Module blocks all optional cookies until visitor accept consent.
 -  Accepted cookie consent is saved into DB.
 -  All _unknown_ blocked cookies automatically added to the backend list, so
    you can regulary check if all cookies that are used on the site are
    in the consent list.
 -  Store owner can register unlimited count of additional cookies and groups.
 -  All magento cookies are known by the module out of the box.

### Version 1.2.3

> Feb 17, 2020

 -  RTL fixes for newsletter consent

### Version 1.2.2

> Jan 31, 2020

 -  Fixed broken ACL resources page in Magento older than 2.3.4
 -  Fixed too large margin in newsletter checkbox in Magento 2.3.4

### Version 1.2.0

> Jun 4, 2019

 -  Added consent text to the "Newsletter Subscriptions Management" page.
 -  Added ability to withdraw newletter consent for registered customers.
    (Available at "Newsletter Subscriptions Management" page inside
    customer account.)
 -  Fixed not working form autocomplete when gdpr is initialized on the form.

> **Upgrade Instruction**
>
> Navigate to module configuration and check "Show in Forms" option for
> Newsletter consents config. Two forms should be selected:
>
> - Magento: Newsletter Subscription
> - Magento: Newsletter Subscription Management

### Version 1.1.4

> May 29, 2019

 -  Fixed missing consents at account privacy page when cache is enabled
 -  Fixed not working customer link in requests grid at the backend

### Version 1.1.2

 > May 24, 2019

 -  Deprecated code removed

### Version 1.1.1

> Mar 29, 2019

 -  Added missing localization file
 -  Fixed mysql error on client consents page when table prefixes are used

### Version 1.0.0

 -  Initial Release
 -  Consents in the following forms:
    - Newsletter
    - Contacts
    - Registration
    - Product Reviews
 -  Ability to request account deletion from Privacy Tools page
