---
layout: default
title: Easy Banners Changelog
description: Easy Banners changelog
keywords: easybanner changelog, easybanner updates
category: Easy Banners
---

# Changelog

### Version 1.5.8

> Aug 5, 2020

 -  Fixed responsive images in Luma theme.
 -  Prevent page jumping when image is loading.
 -  Fixed mispositioned dimensions label in backend form.

### Version 1.5.6

> May 4, 2020

 -  Magento 2.3.5 CSP compatibility.
 -  Fixed broken chart in backend.
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

### Version 1.5.5

> Apr 17, 2020

 -  GDPR [cookie consent](/m2/extensions/gdpr/) integration
 -  Fixed small image in newsletter popup when [PageSpeed](/m2/extensions/pagespeed/) is used

### Version 1.5.3

> Feb 17, 2020

 -  Fixed newsletter popup styles in Firefox

### Version 1.5.1

> Jan 31, 2020

 -  Fixed CSS issue with newletter popup in Magento 2.3.4

### Version 1.5.0

> Nov 22, 2019

 -  [Exit-intent popup](/m2/extensions/easybanners/interfaces/#conditions-tab)
    banners added. See [Newsletter popup example](/m2/extensions/easybanners/use-cases/newsletter-popup/).
 -  Fixed non-editable date field in backend conditions tab.
 -  JS code improvements.

### Version 1.4.0

> Oct 16, 2019

 -  Magento 2.1 support dropped (JsonSerializer added instead of serialize).
 -  Magento coding standard fixes.

### Version 1.3.1

 -  Fixed possible JS error in backend Charts when using slow network connection

### Version 1.2.3

 -  Fixed possible error on bundle product pages

### Version 1.2.2

 -  Fixed image styles in [Book layout](/m2/extensions/easybanners/layouts-for-html-banners/#book)
 -  Small CSS fixes

### Version 1.2.1

 -  Magento 2.1 compatibility
 -  Removed url validation as it does not allow to use `.html` suffix
 -  Fixed 'Undefined variable: options' error for banners without placeholders
 -  Fixed 'display_count_per_customer' conditions when FPC is enabled

### Version 1.2.0

IMPORTANT: [**Upgrade Instructions**](/m2/extensions/easybanners/upgrade-instructions/)

**Major Updates**

 -  [New Conditions](/m2/extensions/easybanners/interfaces/#conditions-tab)
    - Page URL
    - Periodical date conditions (Day of week and Day of month)
    - Periodical per-visitor conditions (Display count per day, week, month)
    - Product attribute conditions (Currently viewing product)
 -  "Don't show anymore" action added to lightbox and awesomebar banners
 -  New predefined [HTML layouts](/m2/extensions/easybanners/layouts-for-html-banners/)
 -  Added ability to [assign placeholder](/m2/extensions/easybanners/interfaces/#form)
    to parent container without using 'Widgets' page

**Fixes and Improvements**

 -  Fixed not-working banner when it assigned to multiple stores
 -  Improved popup styles and positioning
 -  Backend forms rewritten into UI components
 -  Code cleanup

### Version 1.1.0

 -  Fixed SQL error '1205 Lock wait timeout exceeded'.
 -  Reduced number of database operations.

### Version 1.0.12

 -  Critical security issue fixed
 -  Default sort order changed in backend grid, so newest banners will be on top

### Version 1.0.10

 -  Magento 2.2 compatibility

### Version 1.0.9

 -  ACL instructions added to UI components according to latest Magento requirements
 -  Fixed DI compilation errors

### Version 1.0.7

 -  Fixed WYSIWYG insert image bug

### Version 1.0.6.2

- Magento 2.1.0 compatibility

### Version 1.0.6

- Fixed "Undefined property" error

### Version 1.0.5

- Added additional css classes support for banner and placeholder blocks
- Compilation error fixes

### Version 1.0.2

- Removed database queries from the loop, when rendering placeholder
- Banners are not shifted on each page refresh, when using placeholder
- Fixed getClassName methods

### Version 1.0.2

- Fixed wrong display and clicks count in banners grid

### Version 1.0.0

- Initial Release
