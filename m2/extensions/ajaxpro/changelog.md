---
layout: default
title: Ajaxpro Changelog
category: AjaxPro
---

# Changelog

### Version 1.5.11

> Aug 11, 2020

**Bugfixes**
 - Fix checkout.cart block not exist after 2.4 integration


### Version 1.5.10

> Aug 10, 2020

**Bugfixes**
 - Fix sidebar overlap
 - Prevent double show() calling

### Version 1.5.9

> Aug 7, 2020

**Bugfixes**
 - Fix IE quick-view (ie not support es6 template literals)
 - Fixed quick-view of out-of-stock products
 - Fix get total-information after order place (empty quote 404)
 - Rename ajaxpro-checkout.cart.after => ajaxpro-checkout.cart.fixes

### Version 1.5.8

> Jul 29, 2020

 - magento 2.4 intagration

### Version 1.5.7

> Jul 23, 2020

**Improvements**
 - Add animation feature

**Bugfixes**
 - Fix blank empty checkout.cart block
 - Fix override minicart empty bug, add loading by click

###Version 1.5.6

> Jul 10, 2020

**Bugfixes**
 - Add force redirect to cart checking
 - Fix (commented) force customer data 'cart' reloading if override_minicart === true

### Version 1.5.5

> Jul 1, 2020

**Improvements**
 - Disable quick view by default
 - Refactoring ajaxpro (disposableCustomerData); remove timechecking from modal-manager
 - Add using expirableSectionNames
 - remove invalidate after #24

**Bugfixes**
 - Fixed missing quick view button at Argento Home (and probably Argento Luxury).

### Version 1.5.4

> Jun 17, 2020

**Improvements**
 - Add Quick View enable/disable config option
 - Init block was refactored

### Version 1.5.3

> Jun 16, 2020

**Features**
 - Add Quick View feature

**Bugfixes**
 - Refactored logic in modal-manager

### Version 1.5.1

> May 7, 2020

**Features**
 - Improve translates.

### Version 1.5.0

> Apr 30, 2020

**Features**
 - Add/Update translations ar_SA, uk_UA, sw_SE, es_ES, ru_RU, pt_PT, pl_PL, nb_NO, ko_KR,
    ja_JP, it_IT, he_IL, de_DE, fr_FR, nl_NL, zh_CN etc.

**Bugfixes**
 - Improve checkTimestamp logic in modal-manager (fix timeout racing)

### Version 1.4.19

> Apr 21, 2020

 - Fix mage.configurable spConfig.containerId empty bug
 - Fix no gap at the top of the popup at category page with one column layout

### Version 1.4.18

> Mar 17, 2020

 - Fix minicart overiding time (add timeout)

### Version 1.4.17

> Feb 17, 2020

 -  Code optimizations.
 -  Added 'Grouped products' support.

### Version 1.4.16

> Jan 31, 2020

**Fixes**
 - Add 'Grouped products support'
 - Add composer dependencies
 - Invalidate 'ajaxpro-cart' localStorage for fixes in 'ajaxpro.checkout.cart.after' (close #24)
 - Remove not actual code
 - Update json serializer
 - Fix some deprecated dependency


### Version 1.4.15

> Jan 13, 2020

 - Fix document.write() js eval
 - Remove 'block not exist' debug messages
 - Override messages.phtml for messages block. To remove coockieMessages displaying
 - Improve layout builder
 - Fix circular dependecy


### Version 1.4.14

> 11 Dec 2019

 - Fixed missing add to cart popup in production mode
 - Fix: Product with custom options add to cart fails (close #22)

### Version 1.4.13

> Nov 15, 2019

 - MEQP improvements (severity 9)

### Version 1.4.12

> Oct 16, 2019

 -  Remove direct 'jquery/ui' usage to improve js performance.

### Version 1.4.11

> Sep 27, 2019

 -  Removed crosssell block from simple type popup
 -  Improved performance when using cart popup

### Version 1.4.10

> Aug 19, 2019

 -  Fixed possible redirect to broken page after 'Add to Cart' action.

### Version 1.4.9

> Jul 8, 2019

 -  Fix override minicart not showing bug
 -  Refactor modal-manager

### Version 1.4.8

> Jul 1, 2019

**Bugfixes**
 -  Fixed bug: block 'checkout.cart' not exist for 2.3 in popup minicart case

### Version 1.4.7

> Jun 12, 2019

 -  Fixed possible warning during 'di:compile' command

### Version 1.4.6

> Jun 7, 2019

 -  Update catalog-add-to-cart widget
 -  Remove 'Ajaxpro' requirejs shortname

### Version 1.4.5

> Apr 30, 2019

 -  RTL fixes for floating cart mode
 -  Fixed 'Delete item' confirmation popup behind overlay
 -  Fixed css issue with argento 'compare products' toolbar

### Version 1.4.4

> Mar 29, 2019

 -  Fixed static content deployment on Magento 2.3 (There was an error about
    missing swatches.less file)

### Version 1.4.3

> Feb 26, 2019

 -  Javascript fixes for modal window
 -  Fixed css style issue, when using "floating cart" design

### Version 1.4.2

**Features**
 - magento 2.3 compatibility

**Bugfixes**
 - Fix swatches.css does't exist in 2.3 bug
 - Added fix to don't show old windows (modal-manager.js)
 - Code style was improved

### Version 1.4.1
 - Marketplace rebuild

### Version 1.4.0

**Features**
 - Rename composer package swissup/ajaxpro => swissup/module-ajaxpro

**Bugfixes**
 - Fix override minicart
 - Fix (uncomment): "Proceed to checkout" button does nothing + slide mode
 - Fix 'ugly scrollbar' when viewed on slide mode and small screen
 - Increase more timeoffset for override_minicart variant
 - Fix min-width for slide minicart


### Version 1.3.3

**Bugfixes**
 - Fix missing getSerializedConfig method (window.checkout = ;)

### Version 1.3.2

**Bugfixes**
 - Fix js error 'Cannot read property 'backUrl' of null'
 - Fix redundant reload ajaxpro sections after page refresh .reload([])

### Version 1.3.1

 -  Add eval native <script>
 -  Fix modal z-index for 2.2.6
 -  Add patch for .price-box bug configurable.js mixin
 -  Fix lost js lib bug _
 -  Fix eslint and jscs warnings
 -  Fix radio disabled bug was patched
 -  Remove floating.cart at checkout pages

### Version 1.3.0

 -  Added slide mode for modal dialog
 -  Added floating cart widget
 -  Added new dialog type like a minicart
 -  Fix priceBox bug
 -  Add refresh shiping methods patch
 -  Fix override modal widget bug
 -  Add ajaxpro product view +swatches at homepage integration
 -  Cart-sidebar widget was added
 -  Fix ESlint and jscs code style warnings

### Version 1.2.8

 -  Added compatibility with [Swissup_Attributepates](/m2/extensions/attributepages/)
    and [Swissup_Highlight](/m2/extensions/highlight/) modules
 -  Fixed multiple add-to-cart initializations in case of ajax loaded content

### Version 1.2.7

 -  Removed tabs and review summary from product popup
 -  Remove authentication window in product view popup
 -  Small fixes

### Version 1.2.5

- Add product.view popup on home page
- Add check is response json

### Version 1.2.4

- Add integration with ?option=cart
- Add translation
- Remove MEQP.Exit workaround

### Version 1.2.3

- Improve magento 2.2 compatability
- Small bugfixes
- etc.

### Version 1.2.2

- Fix MEQP errors
- Fix ESLint and JSCS warnings
- Add plugin for custom events
- Fix 2.1 integrity
- Add js debug mode

### Version 1.2.1

- Improved styles for 'simple' popup window
- Improve config options depends
- Fix Lite speed web server (view_preprocessed) remove '/* comment // *

### Version 1.2.0

- Add require swissup/suggestpage
- Improve compare, wishlist intagration
- Improve re-initialisation
- Add modal manager
- Add abstract customer data class
- Add ajaxpro.less
- Fixes timeout bugs
- Improve xml handles structure
- Fix Modal UI: clickableOverlay option doesn't work
- Add timeout auto close for popup (+idle)

### Version 1.1.2

- Acl sort order fixes
- Layouts buildings and his destructing was optimised
- Forced totals recalculation was added
- Add selectors ".action.tocart" in ajaxcian (related, crosell, etc.)


### Version 1.1.0

> This version is **not compatible** with old Magento versions.
>
> Magento 2.1 and newer are supported only.

- Magento 2.1.0 compatibility
- Added ACL resource file
- Compare functionality was added
- New validation behavior was added