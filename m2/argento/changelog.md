---
layout: default
title: Argento changelog
description: Argento changelog
category: Argento
---

# Argento Changelog

### Version 1.19.0

> Aug 5, 2020

 -  Magento 2.4 compatibility in themes and modules.
 -  PHP 7.4 compatibility added in bundled modules.
 -  Critical CSS added to all themes to improve PageSpeed score.
 -  Fixed missing review form on ArgentoForce theme when load product page via
    url "...#review-form"
 -  Removed deprecated installation instructions.

**Extensions Updates**

 -  [Ajax Pro](/m2/extensions/ajaxpro/) — 1.5.8 (was 1.5.5)
    -  Magento 2.4 compatibility.
    -  Add optional fly to cart animation feature.
 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.9.8 (was 1.9.5)
    -  Magento 2.4 compatibility.
    -  Include tax to the product price if needed.
 -  [AMP](/m2/extensions/amp/) — 1.4.3 (was 1.4.1)
    -  Magento 2.4 compatibility.
    -  Removed prohibited loading attribute from images
    -  Fixed store menu processing when Varnish used.
 -  [Askit](/m2/extensions/askit/) — 1.8.2 (was 1.8.0)
    -  Magento 2.4 compatibility (unexpected token 'case' error in backend).
    -  Fixed issue when unable to assign product/category/page to question.
 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.8 (was 1.5.7)
    -  Prevent page jumping when image is loading.
    -  Fixed mispositioned dimensions label in backend form.
 -  [EasyCatalogImages](/m2/extensions/easycatalogimages/) — 1.4.11 (was 1.4.9)
    -  Added category to hide and listing mode options to departments page configuration
 -  [EasySlide](/m2/extensions/easyslider/) — 1.5.7 (was 1.5.6)
    -  Performance improvements.
    -  Prevent page jumping when image is loading.
 -  [Easytabs](/m2/extensions/easytabs/) — 1.9.0 (was 1.8.12)
    -  Prevent page jumping while scripts are initializing.
    -  Fixed automatic cache invalidation on content and tab update.
 -  [Featured Attributes](/m2/extensions/featured-attributes/) — 1.1.4 (was 1.1.3)
    -  Performance improvements.
 -  [GDPR](/m2/extensions/gdpr/) — 1.3.7 (was 1.3.4)
    -  PHP 7.4 compatibility
    -  Allow to translate cookie title and description via i18n files
    -  Do not show cookie bar until scripts are ready
    -  Fixed newsletter signup styles in Magento 2.4
 -  [Highlight](/m2/extensions/highlight/) — 1.6.3 (was 1.6.2)
    -  Improve [Prolabels](/m2/extensions/prolabels/),
       [Seo Images](/m2/extensions/seo-images/) and [Seo Templates](/m2/extensions/seo-templates/)
       extensions support.
 -  [Hover Gallery](/m2/extensions/hover-gallery/) — 1.3.7 (was 1.3.5)
    -  Fixed issue at Magento 2.4.0 at product listing when pagination and limits are ignored.
    -  Performance improvemements.
 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.14.7 (was 1.14.5)
    -  Fixed invalid category image path in Magento 2.4
    -  PHP 7.4 compatibility
 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.4.4 (was 1.4.2)
    -  Magento 2.4 compatibility.
    -  Minimize layout shifts with own css loader.
    -  Don't push/preload images from `<picture>` tag.
    -  Fix webp+picture and lazyload data-srcset bug combination.
    -  Config refactoring.
 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.5 (was 1.5.3)
    -  Performance improvements.
    -  Fixed issue at Magento 2.4.0 at product listing when pagination and limits are ignored.
    -  Improve labels rendering on product page for configurable products.
 -  [Seo Suite](/m2/extensions/seo-suite/)
    -  *swissup/module-seo-core — 1.2.3* (was 1.2.2)
       - Reduce page rendering time by reducing number if queries for SEO Templates and SEO Images extensions.
    -  *swissup/module-hreflang — 1.4.1* (was 1.4.0)
       - Reduce number of database queries.
    -  *swissup/module-seo-images — 1.3.6* (was 1.3.2)
       - Fixed issue at Magento 2.4.0 at product listing when pagination and limits are ignored.
       - Performance improvemements.
    -  *swissup/module-seo-pager — 1.2.6* (was 1.2.4)
       - Fixed issue at Magento 2.4.0 at product listing when pagination and limits are ignored.
    -  *swissup/module-seo-templates — 1.5.11* (was 1.5.8)
       - Performance improvemements.
       - Fixed issue at Magento 2.4.0 at product listing when pagination and limits are ignored.
    -  *swissup/module-seo-urls — 1.5.12* (was 1.5.11)
       - Fixed PHP error "Call getColumnValues on array".
       - Performance improvemements.
    -  *swissup/module-seo-xml-sitemap — 1.1.7* (was 1.1.6)
       - Add missing other links to sitemap XML.
 -  [QtySwitcher](/m2/extensions/qty-switcher/) — 1.1.6 (was 1.1.5)
    -  Integrate into AjaxPro popup.
    -  Get proper stock config for grouped product children.

### Version 1.18.0

> Jul 1, 2020

 -  Added favicons in all themes
 -  Fixed error when Facebook Like Button module is not installed
 -  "Photo in description" can play video now
 -  Improved layered navigation styles when filters in main column
 -  Fixed horizontal scrollbar when js is not initialized yet on RTL stores
 -  Allow to change logo size with magento's admin settings
 -  Fixed missing prolabels on product page after theme installation
 -  Fixed installation error when some module is missing
 -  Argento Stripes: Fixed partially invisible text in Braintree inputs on checkout
 -  Argento Pure2: Always render configurable header at the page top
 -  Argento Pure2: Added config to disable configurable header on specific pages
 -  Other small fixes and improvements in styles, templates and scripts

**Extensions Updates**

 -  [Ajax Pro](/m2/extensions/ajaxpro/) — 1.5.5 (was 1.5.1)
    -  Added quick product view feature on the product listing
    -  Refactored logic in modal-manager
    -  Init block was refactored
 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.9.5 (was 1.9.1)
    -  Added Elasticsearch 7 compatibility
    -  Fixed wrong price in search popup when store uses multiple currencies
    -  Fixed RTL style issue
    -  Fixed error when searching '~'
 -  [AMP](/m2/extensions/amp/) — 1.4.1 (was 1.3.14)
    -  Disable move JS to page bottom on AMP
    -  Full page cache now works on AMP
    -  Fixed missing view details button for products with required options
    -  Fixed missing svg logo on AMP
    -  Fixed missing menu when using Varnish
    -  Fixed page jumping while scripts are initializing
    -  Do not render cookie notice block when it's disabled
 -  [Askit](/m2/extensions/askit/) — 1.8.0 (was 1.7.5)
    -  New mass actions in Questions grid - “Assign to…”
    -  Fixed error when post answer from Admin grid with questions
    -  Improvements and fixes to admin interfaces of edit questions/answers
 -  [Attribute Pages](/m2/extensions/attributepages/) — 1.2.6 (was 1.2.4)
    -  Do not activate 'exclude_from_display' checkbox when click on another cell
    -  Removed end slash from pages URLs
 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.7 (was 1.5.6)
    -  Added identity interface for block and placeholder
 -  [EasyCatalogImages](/m2/extensions/easycatalogimages/) — 1.4.9 (was 1.4.8)
    -  Small style improvement on AMP
 -  [EasySlide](/m2/extensions/easyslider/) — 1.5.6 (was 1.5.5)
    -  Small style improvement on AMP
 -  [Easytabs](/m2/extensions/easytabs/) — 1.8.12 (was 1.8.10)
    -  Fixed broken Delete action in actions column
    -  Added enabled config for product tabs
    -  Fixed typos in description tab name and translations
 -  [Featured Attributes](/m2/extensions/featured-attributes/) — 1.1.3 (was 1.1.2)
    -  Display all attributes. Previously, only attributes from default attribute set were displayed.
 -  [GDPR](/m2/extensions/gdpr/) — 1.3.4 (was 1.3.2)
    -  Fixed error when customer logging in
    -  Place consents before captcha/recaptcha field
 -  [Highlight](/m2/extensions/highlight/) — 1.6.2 (was 1.6.1)
    -  Fixed highlight carousel on AMP
 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.14.5 (was 1.14.3)
    -  Fixed flyout menu from top left corner in Safari when fade animation is used
    -  Code cleanup and installer improvements
    -  Fixed rare bug when nowrap or sticky features does not applied on the initial page load
 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.4.4 (was 1.4.2)
    -  Fix in removing of empty ‘criticalCss’
    -  Fixed double slash in URLs to static content
    -  Fixed duplicated sources in 'picture' if image repeated on the page
    -  Added preconnect with dns-prefetch
    -  Added optional link rel='preload'
 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.5 (was 1.5.3)
    -  Fixed PHP warning - division by zero
    -  Fixed PHP warning - array must contain at least one element
 -  [Seo Suite](/m2/extensions/seo-suite/)
    -  *swissup/module-seo-core — 1.2.3* (was 1.2.2)
       - Fix for chinese locales when slufigy package installed
    -  *swissup/module-hreflang — 1.4.1* (was 1.4.0)
       - Don't include store view into hreflangs when it is disabled in admin
    -  *swissup/module-rich-snippets — 1.4.10* (was 1.4.9)
       - Added support for availability pre-order
    -  *swissup/module-seo-html-sitemap — 1.1.6* (was 1.1.5)
       - Improved third-party modules compatibility
    -  *swissup/module-seo-urls — 1.5.12* (was 1.5.11)
       - Fixed params resolving logic when yes/no filter and 'No' selected
    -  *swissup/module-seo-templates — 1.5.11* (was 1.5.8)
       - Fixed 'categories' and 'parents' directive for products
       - Update category and product metadata only at pages where it is really necessary
 -  [SoldTogether](/m2/extensions/soldtogether/) — 1.6.10 (was 1.6.9)
    -  Fixed error when saving newly created product with sold together data
 -  [Testimonials](/m2/extensions/testimonials/) — 1.2.9 (was 1.2.8)
    -  Improved slider widget
    -  Fixed error when admin notification email is empty

### Version 1.17.0

> May 7, 2020

 -  Compatibility with Magento 2.3.5 and Content Security Policies
 -  Added translation for 16 locales in all themes and modules
 -  Customize category page from admin using [Category Page Builder][cp-builder]
 -  Customize product page from admin using [Product Page Builder][pp-builder]
 -  Argento Pure2: you can now change header layout directly from admin using [Header Builder][h-builder]
 -  Argento Luxury: styles improvements and optimization
 -  Improved filters styles at one column page layout
 -  Fancy scroll at Ajaxpro popup
 -  Fixed wrong logo size in Magento 2.3.5

**Extensions Updates**

 -  [Ajax Pro](/m2/extensions/ajaxpro/) — 1.5.1 (was 1.4.18)
    -  Fixed issue with configurable products
    -  Modal logic fix
 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.9.1 (was 1.8.8)
    -  css fix for search in Header Builder
 -  [AMP](/m2/extensions/amp/) — 1.3.14 (was 1.3.13)
    -  Magento 2.3.5 CSP compatibility
    -  Fixed too big :focus border around the image
    -  Fixed error at products compare page
 -  [Askit](/m2/extensions/askit/) — 1.7.5 (was 1.7.0)
    -  Remove template and js file not used anymore
    -  Fixed askit widget at homepage
 -  [Attribute Pages](/m2/extensions/attributepages/) — 1.2.4 (was 1.2.3)
 -  [EasySlide](/m2/extensions/easyslider/) — 1.5.5 (was 1.5.4)
    -  Improved positioning of slide description
    -  Fixed error on image upload page - compatibility with Magento 2.3.5
 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.6 (was 1.5.4)
    -  Fixed small image in newsletter popup
    -  GDPR cookie consent integration
    -  Magento 2.3.5 CSP compatibility
    -  Fixed broken chart in backend
 -  [EasyCatalogImages](/m2/extensions/easycatalogimages/) — 1.4.8 (was 1.4.7)
 -  [Easytabs](/m2/extensions/easytabs/) — 1.8.10 (was 1.8.9)
    -  Added config to enable accordion layout on desktop
 -  [Fblike](/m2/extensions/fblike/) — 1.3.5 (was 1.3.4)
    -  Magento 2.3.5 CSP compatibility
 -  [Featured Attributes](/m2/extensions/featured-attributes/) — 1.1.2 (was 1.1.1)
    -  Improved performance
 -  **FontAwesome** — 1.4.1 (was 1.4.0)
    -  Magento 2.3.5 CSP compatibility
 -  [GDPR](/m2/extensions/gdpr/) — 1.3.2 (was 1.2.3)
    -  [Cookie consent](/m2/extensions/gdpr/configuration/#cookie-consent-section) feature added
    -  Fixed error during static content deploy
    -  Fixed cookie bar positioning
 -  [Highlight](/m2/extensions/highlight/) — 1.6.1 (was 1.6.0)
    -  Block title now affects the cache
 -  [LightboxPro](/m2/extensions/lightboxpro/) — 1.2.10 (was 1.2.9)
    -  Removed add session param to url: Magento 2.3.5 compatibility
 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.14.3 (was 1.14.0)
    -  Fixed bug when dropdown wasn’t shown on mouse hover
    -  Decreased cache memory consumption
    -  Added marketplace installer support
 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.4.2 (was 1.3.17)
    -  Added google pagespeed insights integration in config
    -  Added image optimization by schedule
    -  Added filename and limit arguments to ‘images:resize’ console command
    -  Added comments about heavy server load for some features in config
    -  Magento 2.3.5 CSP compatibility
    -  Added ability to exclude some scripts from defer
    -  Added http/2 pushing for fonts
 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.3 (was 1.5.2)
    -  On Sale, Is New and Stock labels can be disabled for specific customer group
 -  [Review Reminder](/m2/extensions/reviewreminder/) — 1.1.6 (was 1.1.5)
    -  Fixed showing wrong products in email
 -  [Seo Suite](/m2/extensions/seo-suite/) — 1.9.1 (was 1.9.0)
     - *swissup/module-hreflang — 1.4.0* (was 1.3.7)
       - Fixed empty hreflang value for chines locales when "Remove region...".
       - Build hreflang links using all websites of Magento instance.
     - *swissup/module-rich-snippets — 1.4.8* (was 1.4.9)
       - Compatibility with Firebear_ConfigurableProducts module.
     - *swissup/module-seo-urls — 1.5.11* (was 1.5.10)
       - Add `nofollow` to category filter in layered navigation.
 -  [SoldTogether](/m2/extensions/soldtogether/) — 1.6.9 (was 1.6.8)
 -  [Testimonials](/m2/extensions/testimonials/) — 1.2.8 (was 1.2.7)

[cp-builder]: /m2/argento/customization/theme-editor/#category-page-builder
[pp-builder]: /m2/argento/customization/theme-editor/#product-page-builder
[h-builder]: /m2/argento/customization/theme-editor/#header-builder

### Version 1.16.0

> Mar 26, 2020

 -  Fixed broken image markup in sticky-add-to-cart component
 -  RTL styles for argento tabs (homepage)
 -  A lot of improvements in [Askit](/m2/extensions/askit/) module
 -  Argento Pure2 — added category page configuration section in theme editor with the following features:
    -  change category page layout
    -  change page content width
    -  set products per page and list mode
    -  configure the number of products in a row for different page sizes
    -  all changes are immediately visible in page layout preview

**Extensions Updates**

 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.8.8 (was 1.8.7)
    - Fixed search button not working on iOS

 -  [AMP](/m2/extensions/amp/) — 1.3.13 (was 1.3.10)
    - Fixed broken add to cart on homepage
    - Fixed rating error on category page
    - Styles from app/design theme folder now included on AMP pages
    - Fixed broken allow cookie action in Magento 2.3

 -  [Askit](/m2/extensions/askit/) — 1.7.0 (was 1.6.4)
    - Totally reworked internal implementation at frontend
    - Question and Answer forms build with UI Component
    - Questions list loaded with ajax request reacts immediately on customer actions (voting, page changing)
    - Improved UX at backend

 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.4 (was 1.5.3)
    - Fixed small image in newsletter popup when PageSpeed module enabled
    - Fixed js error when there are two banners with the same ID in database

 -  [Easytabs](/m2/extensions/easytabs/) — 1.8.9 (was 1.8.6)
    - Content in attribute tab now pocesses widget instructions
    - Tabs admin grid improvements: added alias column and colors for block types
    - Removed the limit for product attribute tab: add as many attributes as you need

 -  [Highlight](/m2/extensions/highlight/) — 1.6.0 (was 1.5.6)
    - Added color swatches support to the Highlight widgets and pages
    - Improved magazine layout look on mobile devices
    - Added ability to set custom ‘View All’ page url
    - Improved pagination/limit logic (Amasty_Preorder module compatibility)

 -  [HoverGallery](/m2/extensions/hover-gallery/) — 1.3.5 (was 1.3.3)
    - Escape hover image URL: SEO Images module compatibility
    - Fixed hover image position when using list mode

 -  [LightboxPro](/m2/extensions/lightboxpro/) — 1.2.9 (was 1.2.8)
    - Now image is resized when height is updated in configuration

 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.14.0 (was 1.13.7)
    - Fixed possibly empty menu when using Argento installer and ‘All Stores’ option
    - Added ability to set dropdown settings for third dropdown level
    - Fixed possible error when category name is missing in the backend navpro’s tree

 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.3.17 (was 1.3.15)
    - Fixed issue with umlauts in image name
    - Fixed issues with wrong image alt text
    - Improved advanced bundling: added Swissup themes integration
    - Improved image optimization and lazy load features

 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.2 (was 1.5.1)
    - Fixed label without styles at product page

 -  [Review Reminder](/m2/extensions/reviewreminder/) — 1.1.5 (was 1.1.3)
    - Added ability to use TrustedShops review link in email

 -  [Seo Suite](/m2/extensions/seo-suite/) — 1.9.0 (was 1.8.3)
     - Improvements in SEO Urls and SEO Images - remove double quotes, replace non-breakable space with dash
     -  *Hreflang*:
         -  Fixed poorly worked urls at Magento 2.3.4
         -  Force remove store_code parameter from url
         -  Fixed warning during order placing
     -  *Seo Images*:
         -  Added SEO Images Magento Index to speed up initial page rendering
         -  “Production Mode” feature (beta)
     -  *Seo Templates*:
         - Improved third-party modules compatibility
         - Improved price directive for products
     -  *Seo URLs*:
         - Fixed incorrect category urls in hreflangs

 -  [SoldTogether](/m2/extensions/soldtogether/) — 1.6.8 (was 1.6.6)
    - RTL fixes
    - Fixed compilation error

### Version 1.15.2

> Feb 17, 2020

 -  A lot of RTL fixes and improvements.
 -  CSS styles cleanup in Pure2 theme.
 -  Login popup added that allows to login from any page.
 -  Added server and browser cache invalidation when changing CSS via theme editor.
 -  New [Marketplace](https://github.com/swissup/module-marketplace#marketplace)
    installer support added.

**Extensions Updates**

 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.8.7 (was 1.8.6)
    - JS code optimizations.
 -  [Askit](/m2/extensions/askit/) — 1.6.5 (was 1.6.3)
    - Fixed broken 'answers' grid in Magento 2.3.4.
 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.3 (was 1.5.1)
    - Fixed newsletter popup styles in Firefox.
    - RTL fixes.
 -  [EasyCatalogImages](/m2/extensions/easycatalogimages/) — 1.4.7 (was 1.4.6)
    - CSS code optimizations.
 -  [GDPR](/m2/extensions/gdpr/) — 1.2.3 (was 1.2.2)
    - RTL fixes.
 -  [HoverGallery](/m2/extensions/hover-gallery/) — 1.3.3 (was 1.3.2)
    - Improve hover image positioning when it has smaller height than requested for listing.
 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.13.7 (was 1.13.6)
    - RTL fixes.
    - Fixed broken magento installation when navpro is enabled before Magento was installed.
 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.3.15 (was 1.3.12)
    - Fixed 'Segmentation fault' error.
    - MagentoCloud fixes.
    - Prevent possible memory exhausted error.
 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.1 (was 1.5.0)
    - Don't show low stock label for products with zero qty. (Backordered products)
 -  [QuantitySwitcher](/m2/extensions/qty-switcher/) — 1.1.5 (was 1.1.4)
    - RTL fixes.
 -  [SlickCarousel](/m2/extensions/slick-carousel/) — 1.3.3 (was 1.3.2)
    - RTL fixes.
 -  [SoldTogether](/m2/extensions/soldtogether/) — 1.6.6 (was 1.6.5)
    -   Rework templates to make blocks work at checkout success page. Carousel
        template can be used for frequently bought together block also.

### Version 1.15.1

> Jan 31, 2020

 -  Magento 2.3.4 compatibility:
    -  Fixed newsletter block styles.
    -  Fixed jumping "Product Page" when clicking on a tab.
    -  Fixed customer menu dropdown styles.
    -  Fixed too small homepage images.
 -  [ProLabels](/m2/extensions/prolabels/) is now integrated into
    [AMP](/m2/extensions/amp/) pages.
 -  Minor CSS fixes.

**Extensions Updates**

 -  [Ajax Pro](/m2/extensions/ajaxpro/) — 1.4.16 (was 1.4.15)
    - 'Grouped products' support added.
    - Code cleanup.
 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.8.6 (was 1.8.4)
    - Magento 2.2 compatibility
    - Fixed Elastcsearch ItemProvider fatal in Magento 2.3.1
 -  [Easybanner](/m2/extensions/easybanners/) — 1.5.1 (was 1.5.0)
    - Fixed incorrect newsletter block width in Magento 2.3.4
 -  [Easytabs](/m2/extensions/easytabs/) — 1.8.5 (was 1.8.4)
    - Fixed not working ajax tabs at [AMP](/m2/extensions/amp/) pages.
    - Stability improvements.
 -  [GDPR](/m2/extensions/gdpr/) — 1.2.2 (was 1.2.1)
    - Fixed broken ACL resources page in Magento older than 2.3.4
    - Fixed too large margin in newsletter checkbox in Magento 2.3.4
 -  [LightboxPro](/m2/extensions/lightboxpro/)
    - Fixed incorrectly sized image in Magento 2.3.3 when magnifier is used.
    - Fixed incorrectly sized thumbnail when gallery is shown on non-product view page.
      (In third-party ajax popups at home and category pages, for example.)
    - Code cleanup. (Removed fixes for old Magento versions (2.0, 2.1))
 -  [NavigationPro](/m2/extensions/navigationpro/) — 1.13.6 (was 1.13.5)
    - Fixed invisible dropdowns in sidebar menu, when it has `.navro-nowrap` class.
 -  [Pagespeed](/m2/extensions/pagespeed/) — 1.3.12 (was 1.3.10)
    - Fixed broken 'Bundle Product' page when JS Defer is enabled.
    - Fixed multiple '.webp' extensions added to the filename.
    - Code cleanup.
 -  [ProLabels](/m2/extensions/prolabels/) — 1.5.0 (was 1.4.1)
    - [AMP](/m2/extensions/amp/) integration added.
    - Improved 'Final Price' calculation for configurable products.
    - Code cleanup.
 -  [QtySwitcher](/m2/extensions/qty-switcher/) — 1.1.4 (was 1.1.3)
    - Fixed incorrect available quantities per selected configurable product.

### Version 1.15.0

> Jan 17, 2020

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-1142---1150)

 -  New [**Pagespeed module**](/m2/extensions/pagespeed/) added
 -  Theme Editor: allow using SVG base64 in background image config
 -  Improved toolbar sorter styles on mobile devices
 -  Fixed distorted images on mobile devices
 -  Argento Essence: improved sidebar products styles on mobile devices
 -  Argento Stripes: fixed homepage banners styles
 -  Argento Force: fixed missing reviews form at product page on Magento 2.2.x
 -  Argento Flat and Pure 2: enabled lazyload for brands slider

**Extensions Updates**

 -  [Ajax Pro](/m2/extensions/ajaxpro/) — 1.4.15 (was 1.4.13)
    -   Fixed add to cart for products with options
    -   Added display of backorders notifications
 -  [Ajax Search](/m2/extensions/ajaxsearch/) — 1.8.4 (was 1.8.3)
    -   Added Elasticsearch integration
    -   Fixed missing suggestions popup for second query
 -  [AMP](/m2/extensions/amp/) — 1.3.8 (was 1.3.7)
    -   Allowed CMS block widgets on AMP
    -   Removed loader when critical CSS is enabled
  - [Attribute Pages](/m2/extensions/attributepages/) — 1.2.2 (was 1.2.1)
    -   Do not display products not assigned to any category
 -  [Easy Tabs](/m2/extensions/easytabs/) — 1.8.4 (was 1.8.2)
    -   Fixed error when using module on Magento Cloud
    -   Fixed not loaded reviews when expanded layout enabled
 -  [GDPR](/m2/extensions/gdpr/) — 1.2.1 (was 1.2.0)
    -   Fixed broken ACL resources page
 -  [Hover Gallery](/m2/extensions/hover-gallery/) — 1.3.2 (was 1.3.1)
    -   Don't render prolabels for hover image
 -  [Navigation Pro](/m2/extensions/navigationpro/) — 1.13.5 (was 1.13.3)
    -   Fixed issues with Magento Page Builder inside NavigationPro forms
    -   Fixed ‘X-Magento-Tags’ header size issue
    -   Display message about incorrect category data when importing items
 -  [Seo Suite](/m2/extensions/seo-suite/) — 1.8.3 (was 1.8.1)
     -  Added translation files to all modules
     -  Improved compatibility with Magento Commerce Cloud
     -  *Seo Canonical*:
         -  Do not add canonical to root category
     -  *Rich Snippets*:
         -  Fixed possible PHP notice $offers is undefined
     -  *Seo Images*:
         -  Compatibility with Magento 2 Commerce
     -  *Seo URLs*:
         -  Show 404 page when unrecognized characters found in url

### Version 1.14.2

> Dec 6, 2019

 -  New option for product tabs - load content with ajax. More details you can find at [Swissup Easytabs module](/m2/extensions/easytabs/) docs.
 -  New banner [Exit-intent](/m2/extensions/easybanners/interfaces/#conditions-tab) popup added. Check [Newsletter popup example](/m2/extensions/easybanners/use-cases/newsletter-popup/) powered by Swissup Easybanners module.
 -  New SEO feature - templates for product image alternate text. Check more details at [Swissup Metadata Template module](/m2/extensions/seo-templates/) docs.
 -  Few style improvements for product page of grouped product at all themes.
 -  Stripes theme got better product page styles. No more content floating and jumping. All parts of product page are at the same places at any product. Slightly changed product image gallery at mobile view.
 -  Force theme product page looks perfect when expanded layout for tabs enabled.
 -  Force theme - fixed missing review form at product on Magento 2.2.x.

**Extensions Updates**

**swissup/module-ajaxsearch — 1.8.3** (was 1.8.1)

 -  Product price in search results respects tax include/exlude setting.

**swissup/module-amp — 1.3.7** (was 1.3.6)

 -  Fixed overlap for long submenus.

**swissup/module-easybanner — 1.5.0** (was 1.4.0)

 -  [Exit-intent](/m2/extensions/easybanners/interfaces/#conditions-tab) popup banners added.
 -  Fixed non-editable date field in backend conditions tab.
 -  JS code improvements.

**swissup/module-easytabs — 1.8.2** (was 1.7.3)

 -  New option for tab "Load content with Ajax". The biggest benefit from this option is reduce initial page size.
 -  Totally reworked admin interfaces for tab editing. Edit form build as Magento 2 UI Component. It looks up to date and works like a charm.
 -  No more separate grids for product tabs and widget tabs. All in one place. Product tabs has field "Hide on Product" as No and widget tabs "Hide on Product" - Yes.
 -  Block HTML cache and Full Page Cache marked as invalidated after tab save.

**swissup/module-highlight — 1.5.5** (was 1.5.4)

 -  Added "alt" to higllight title-images (mostly used when carousel enabled).
 -  Fixed duplicated 2nd page in casousel when there are products only for one page.
 -  Fixed carousel when it didn’t show more then two pages even when there are more products available.

**swissup/module-hover-gallery — 1.3.1** (was 1.3.0)

 -  Fixed always visible hover image at Magento 2.2.x.
 -  Respect image visibility.

**swissup/module-navigationpro — 1.13.3** (was 1.13.1)

 -  Prevent unwanted accordion collapse on mobile devices when click outside of the menu.
 -  Fixed invalid category links when using iconic or megamenu with thumbnails menu types.
 -  Fixed bug when new category wasn’t added to the menu’s.

**swissup/module-pro-labels — 1.4.1** (was 1.3.7)

 -  Added advanced text editor for product labels text and CSS in Magento AdminAdvanced text editor based on CodeMirror library.
 -  Fixed missing onSale label for grouped products.
 -  Improve stability at frontend. Prevent division by zero. Occurs when product special price is 0.

**swissup/module-reviewreminder — 1.1.3** (was 1.1.2)

 -  Fixed wrong grouped products link in email.
 -  Fixed rare issue when customer email is empty

**swissup/module-rich-snippets — 1.4.5** (was 1.4.4)

 -  Change how configurable product is presented in data snippet. Now it is a product with multiple offers.
 -  User can specify properties in `offers` and `aggregatedRating` parts of data snippet. It is possible with "Structured data" option in config. Syntax example for "Property Name" column - `offers/mpn`.

**swissup/module-slick-carousel — 1.3.2** (was 1.3.1)

 -  Fixed distorted slider images on mobile devices.

**swissup/module-seo-templates — 1.5.3** (was 1.4.2)

 -  Generate alternate text for product images.
 -  CLI command to generate metadata - `bin/magento swissup:seotemplates:generate`.
 -  Significant improvements for metadata generation via Cron. No more problems with Magento Cache when job is running.

**swissup/module-sold-together — 1.6.5** (was 1.6.4)

 -  Fixed message "Requested product does not exists" on edit product in Magento Admin. Error occurs when assigned product deleted.
 -  Fixed infinit loader in "Add Customers Bought Together" popup at product edit in Magento Admin when popup open before before "Add Frequently Bought Products" popup.
 -  New breakpoints in carousel for "Customers also buy" widget.

### Version 1.14.1

> Oct 16, 2019

 -  Magento 2.3.3 compatibility.
 -  Font preload added to improve PageSpeed rank. To make this possible we've
    moved google fonts from CDN to local theme resources.
 -  Fixed possible missing [NavigationPro](/m2/extensions/navigatiopro/) menu
    after theme installation.
 -  Fixed blurry images in header cart and hover images when using ArgentoStripes
    or ArgentoLuxury theme.

**Extensions Updates**

 -  Magento coding standard fixes in all modules.
 -  Removed direct "jquery/ui" usage in all modules to impove PageSpeed rank.
 -  Improved [HoverGallery](/m2/extensions/hover-gallery/) images generation.
 -  [SeoImages](/m2/extensions/seo-images/): Improved generated image path when
    watermarks are used.
 -  Fixed missing watermark in [LightboxPro](/m2/extensions/lightboxpro/) popup.

### Version 1.14.0

> Sep 27, 2019

 -  New [Slideout](/m2/extensions/navigationpro/use-cases/slideout-menu/) menu
    type added to NavigationPro module.
 -  New [SeoImages](/m2/extensions/seo-images/) module added. It allows you to
    build product image name based on product name and/or product attributes.
 -  Fixed blurry product images in minicart popup.
 -  Code cleanup.

**Extensions Updates**

**swissup/module-ajaxpro — 1.4.11** (was 1.4.10)

 -  Removed crosssell block from simple type popup
 -  Improved performance when using cart popup

**swissup/module-hreflang — 1.3.1** (was 1.3.0)

 -  Fixed exception "Illegal state..." at some Magento instances on AMP.
 -  Get rid of around plugins. Slightly improve TTFB.
 -  Compatibility with Magento 2.3.x.

**swissup/module-navigationpro — 1.13.0** (was 1.12.0)

 -  [Slideout](/m2/extensions/navigationpro/use-cases/slideout-menu/) menu type added.
 -  New "Air" theme added with borderless shadowed dropdowns.
 -  Simplified CSS modifiers usage. You can now select them
    from the [list](/m2/extensions/navigationpro/backend/menu-settings/#modifiers).
    Previously you had to write them manually into CSS Class field.
 -  Added ability to write [custom CSS](/m2/extensions/navigationpro/backend/menu-settings/#general-settings)
    from Edit Menu page.
 -  Simplified menu creation. You can create [many menu](/m2/extensions/navigationpro/menu-types)
    types with just one click.
 -  Improved [Amazon Menu](/m2/extensions/navigationpro/use-cases/amazon-menu/)
    type builder. Now, it automatically shows parent category thumbnail
    in second level dropdowns.
 -  Improved [Megamenu](/m2/extensions/navigationpro/use-cases/megamenu/)
    type builder. Now, it automatically shows parent category thumbnail
    in category dropdown.
 -  New effects added to reveal menu dropdowns: Fade, SlideIn, SlideOut, None.
 -  Improved dropdown positioning.
 -  Many CSS fixes for Dark, Compact, and Flat themes.

**swissup/module-seo-urls — 1.5.5** (was 1.5.4)

 -  Get rid of around plugin when redirect to CMS homepage.
 -  Fixed DI compilation when hreflang is not installed at all.

### Version 1.13.3

> Sep 25, 2019

 -  Meet latest Magento coding standarts requirements. Remove serialize from theme installers.
 -  Theme installers - lazy load for brand sliders.
 -  Fixed scroll to top when click review star at review form at Argento Force.
 -  Minor fixes in Swissup EasySlide and Swissup AMP modules.

### Version 1.13.2

> Sep 13, 2019

 -  Fixed error during static content deployment when ajaxsearch is disabled.
 -  Improved styles for product listing in sidebar.
 -  Minor CSS improvements for Easy Catalog Images, Slick Carousel and Highlight modules.
 -  Fixes for Argento Force theme:
     -  qty field toggler position in latest Chrome browser;
     -  qty field padding on cart page in Firefox;
     -  layered navigation - align on desktop and nowrap for subtitle;
     -  mobile navigation - Account - remove pointer bakcrground when active.

**Extensions Updates**

 -  [Ajaxsearch](/m2/extensions/ajaxsearch/) — 1.8.1 (was 1.8.0):
     +  Fix: remove cms page dublication in search result.

 -  [Askit](/m2/extensions/askit/) — 1.6.2 (was 1.6.1):
     +  Fix: redirect+coockie message.

 -  [EasySlide](/m2/extensions/easyslider/) — 1.5.0.1 (was 1.4.0):
     +  New highly demanded features - lazy load and responsive images for slides.
     +  Updated slider JS library (swiper) for better performance.
     +  Reworked admin interfaces. Build according latest Magento 2 trends (UI components).

 -  [Easytabs](/m2/extensions/easytabs/) — 1.7.1 (was 1.7.0):
     +  Fixed no tabs when widget is added via Magento Admin interface.

 -  [RichSnippets](/m2/extensions/richsnippets/) — 1.4.3 (was 1.4.2):
     +  Show correct price in snippet when including tax enabled;
     +  Fixed Magento Coding Standard error - no explicit Proxy in contructor.

### Version 1.13.1

> Aug 21, 2019

 -  Improved layered navigation styles when using 1column layout for (All themes).
 -  Fixed 'select all/unselect all' labels in dropdown elements at product page
    when product has related products (All themes).
 -  ArgentoForce fixes:
    -  Fixed qty dropdown overlap with Paypal buttons.
    -  Added missing 'Additional CSS' field in backend editor.
    -  Improved spacing between 'addto' and 'paypal' buttons.
    -  Small fixes for category pages when using 3columns/2columns-right layouts.

### Version 1.13.0

> Aug 19, 2019

Argento 1.13.0 brings a new [**ArgentoForce**](/m2/argento/force/) theme,
two new features, and **A LOT** of CSS improvements for all existing
themes.

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v1130 class="phone-up-1 tablet-up-3 photoswipe" %}

 -  New [ArgentoForce](/m2/argento/force/) theme added.
 -  Ability to create [sticky 'Add to Cart' panel](/m2/argento/customization/add-sticky-tocart/)
    at product page.
 -  Ability to [add large product photo to the product description](/m2/argento/customization/add-photo-in-description/)
 -  Recently viewed products carousel added to the bottom of category pages.
 -  Improved search results dropdown styles.
 -  Refined minicart styles for all themes.
 -  Shopping Cart page improvements for all themes.
 -  Many small CSS fixes and improvements.

**Extensions Updates**

 -  [swissup/module-ajaxpro](/m2/extensions/ajaxpro/) — 1.4.10 (was 1.4.8)
    - Fixed possible redirect to broken page after ‘Add to Cart’ action.
 -  [swissup/module-ajaxsearch](/m2/extensions/ajaxsearch/) — 1.8.0 (was 1.7.1)
    -  New "minimalistic form" layout added. Now AjaxSearch provides
       [three form layouts](/m2/extensions/ajaxsearch/configuration/#design):
       - Default - Initially visible form
       - Icon only - Minimalistic form
       - Icon only - Fullscreen form
    -  Improved product list styles in results dropdown.
    -  Improved results dropdown sizing when browser gets resized.
    -  Better scrolling inside dropdown results on mobile devices.
    -  Fixed possible js error on initial page load.
    -  Prevent horizontal scrollbar on small tablets.
    -  Prevent search form 'jumping' while script is initialized.
    -  Fixed disabled CMS pages in search result (They shoudn't appear in results).
    -  Do not close results dropdown when click inside that dropdown.
    -  All styles moved to `_module.less` which allows to redefine ajaxsearch
       variables from your theme less files.
 -  [swissup/module-amp](/m2/extensions/amp/) — 1.3.5 (was 1.3.4)
    -  Fixed DOMDocument empty string warning caused by third-party menu modules.
 -  [swissup/module-askit](/m2/extensions/askit/) — 1.6.1 (was 1.6.0)
    -  Fixed grid mass action title(s).
 -  [swissup/module-easy-slide](/m2/extensions/easyslider/) — 1.4.0 (was 1.3.3)
    -  Added ability to use Magento directives in slider description field.
    -  Improved slider rendering when slide url is not set.
 -  [swissup/module-easycatalogimg](/m2/extensions/easycatalogimages/) — 1.4.4 (was 1.4.3)
    -  Added ability to show parent category link as button. Used at ArgentoForce theme.
 -  [swissup/module-easytabs](/m2/extensions/easytabs/) — 1.7.0 (was 1.6.0)
    -  New tab condition - Show tab for selected Product Type only
 -  [swissup/module-hover-gallery](/m2/extensions/hover-gallery/) — 1.2.1 (was 1.2.0)
    -  Don’t add hover image if it is the same as main image.
    -  LESS variables to customize transition effect.
 -  [swissup/module-hreflang](/m2/extensions/seo-suite/) — 1.3.0 (was 1.2.3)
    -  Integrate with Swissup AMP: Add hreflangs to the head of AMP variant of page.
 -  [swissup/module-lightboxpro](/m2/extensions/) — 1.2.4 (was 1.2.3)
    -  Added new variables for easier customization by third-party theme developers.
 -  [swissup/module-navigationpro](/m2/extensions/) — 1.12.0 (was 1.11.1)
    -  [Mass edit feature](/m2/extensions/navigationpro/ui/menu-items-mass-edit/) added.
    -  Added ability to set
       [global item settings](/m2/extensions/navigationpro/backend/menu-settings/#global-item-settings)
       based on item level.
    -  Added ability to sync [item](/m2/extensions/navigationpro/backend/menu-edit/#advanced-settings)
       and [dropdown](/m2/extensions/navigationpro/backend/menu-edit/#dropdown-settings)
       settings with global settings from menu.
    -  Improved default value for dropdown layout settings in each item. Now it
       shows properly inherited dropdown layout.
    -  Added ability to hide html content/widget
       [when item has no children](/m2/extensions/navigationpro/ui/dropdown-layout-builder/#widget-or-plain-html).
    -  Added ability to use
       [depend and var directives](/m2/extensions/navigationpro/ui/menu-item-name-as-html/#available-variables)
       for item name renderer.
    -  All styles moved to `_module.less`. This allows easely redefine navigationpro
       variables within your theme.
    -  Improved [nowrap feature](/m2/extensions/navigationpro/use-cases/nowrap/) logic.
    -  Do not allow to import root category as it's cannot be rendered at frontend.
    -  Fixed possible js errors when rendering dropdown content at the backend.
    -  Fixed always enabled wysiwyg editors. Now they are disabled by default.
 -  [swissup/module-pro-labels](/m2/extensions/) — 1.3.5 (was 1.3.2)
    -  Fixed missing category labels on Magento 2.3.x (after fixed missing special price at listings in Magento 2.2.x in previous release).
    -  Fixed missig special price at listing when ProLabels enabled.
 -  [swissup/module-quantity-switcher](/m2/extensions/qty-switcher/) — 1.1.1 (was 1.1.0)
    -  Added dropdown switcher type.
 -  [swissup/module-seo-html-sitemap](/m2/extensions/seo-suite/) — 1.1.3 (was 1.1.2)
    -  Don't show disabled CMS pages on sitemap.
 -  [swissup/module-seo-urls](/m2/extensions/seo-suite/) — 1.5.4 (was 1.5.3)
    -  Don't reset router params in search url. (Third-party modules integration).
 -  [swissup/module-sold-together](/m2/extensions/sold-together/) — 1.6.3 (was 1.6.2)
    -  Customers Also Bought - don't add tocart checkbox for composit items.
       Composit items are configurable, bundle or grouped products.
    -  Remove module blocks from AjaxPro popup.

### Version 1.12.0

> Jul 1, 2019

This release includes Magento 2.3.2/2.2.9 compatibility of Argento Themes and
updates for modules shipped together with Argento.

 -  Magento 2.3.2/2.2.9 compatibility
 -  Expand layered navigation mixin moved to Blank and can be used in any theme
 -  Fixed missing newsletter subscribe button in Magento 2.3.2/2.2.9
 -  Fixed newsletter block styles when GDPR enabled in Luxury theme

**Extensions Updates**

 -  [Ajaxpro](/m2/extensions/ajaxpro/) — 1.4.8 (was 1.4.7)
    -   Fixed not working cart button when slide mode enabled
 -  [Ajaxsearch](/m2/extensions/ajaxsearch/) — 1.7.1 (was 1.7.0)
    -   Improved search block loading speed
 -  [AMP](/m2/extensions/amp/) — 1.3.4 (was 1.3.3)
    -   Fixed disabled add to cart button in Magento 2.3.2/2.2.9
    -   Fixed wrong image sizes on category page
 -  [Askit](/m2/extensions/askit/) — 1.6.0 (was 1.5.0)
    -   Added [Swissup AMP](/m2/extensions/amp/) module integration
    -   Added size for Gravatar image
 -  [Easytabs](/m2/extensions/easytabs/) — 1.6.0 (was 1.5.2)
    -   Added [Swissup AMP](/m2/extensions/amp/) module integration
    -   New condition to display tab only when AMP enabled
 -  [Quantity Switcher](/m2/extensions/qty-switcher/) — 1.1.0 (was 1.0.0)
    -   Added new switcher type: dropdown

### Version 1.11.0

> Jun 12, 2019

This release includes some style fixes in Argento Themes and a lot of updates
for modules shipped together with Argento:

 -  [Ajaxpro](/m2/extensions/ajaxpro/) — 1.4.7 (was 1.4.5)
    -   Fix warning during DI compilation at Magento 2.1.x.
    -   Code cleanup
 -  [Ajaxsearch](/m2/extensions/ajaxsearch/) — 1.7.0 (was 1.6.0)
    -   New alternative search method for MySQL Search Engine - "LIKE". It
        allows to search for strings with dash (-), one-two-character substrings
        and has other algorithm for relevance. Can be enabled in module
        configuration under
        ["MySQL Search Engine" section](/m2/extensions/ajaxsearch/configuration/#mysql-search-engine).
    -   Fixed disabled 'Search' button when folded design is used (ArgentoLuxury
        and ArgentoFlat themes)
    -   Code cleanup
 -  [AMP](/m2/extensions/amp/) — 1.3.3 (was 1.3.2)
    -   Fixed possible duplicate amphtml pages for configurable products
 -  [Askit](/m2/extensions/askit/) — 1.5.0 (was 1.4.1)
    -   Style improvements
    -   Hide question form by default (A button 'Ask Question' is shown instead)
    -   Backend form improvements
    -   Code cleanup
 -  [EasySlide](/m2/extensions/easyslider/) — 1.3.3 (was 1.3.1)
    -   Fixed invalid data in the grid after filters reset.
 -  [Easycatalogimg](/m2/extensions/easycatalogimg/) — 1.4.3 (was 1.4.2)
    -   Fixed ability to apply different thumbnail per store view.
 -  [Easytabs](/m2/extensions/easytabs/) — 1.5.2 (was 1.5.0)
    -   Fixed error during data install (area code not set).
 -  [Fblike](/m2/extensions/fblike/) — 1.3.2 (was 1.3.1)
    -   Stability improvements in js code
 -  [GDPR](/m2/extensions/gdpr/) — 1.2.0 (was 1.1.1)
    -   Account newsletter management page support added.
    -   Fixed missing accepted consents at 'privacy tools' page.
    -   Fixed not working link to the customer account page from the requests grid.
    -   Fixed not-working autocomplete in forms when gdpr is enabled for this form.
    -   Code cleanup.
 -  [HoverGallery](/m2/extensions/hover-gallery/) — 1.2.0 (was 1.1.1)
    -   Code improvements.
 -  [Hreflang](/m2/extensions/hreflang/) — 1.2.3 (was 1.2.2)
    -   Improved integration with pages for third-party modules - Swissup AskIt,
        Swissup Highlight and Swissup EasyCatalogImg
 -  [Navigationpro](/m2/extensions/navigationpro/) — 1.11.1 (was 1.9.3)
     -  Added ability to [activate dropdowns with click](/m2/extensions/navigationpro/use-cases/click/)
        instead of mouseover.
     -  [Accordion menu](/m2/extensions/navigationpro/use-cases/sidebar-menu/#&gid=1&pid=3) added.
     -  Nowrap feature [improved](/m2/extensions/navigationpro/use-cases/nowrap/#offset-feature).
     -  Improved backend [dropdown layout builder](/m2/extensions/navigationpro/ui/dropdown-layout-builder/).
        Now it shows a preview of what customer will see on the frontend when
        changing children settings or html content.
     -  Added ability to limit number of categories to display in dropdown.
        When using this option, a 'Shop All' link will be displayed if children count
        exceed the limit. [View Megamenu Example](/m2/extensions/navigationpro/use-cases/megamenu/).
     -  Improved cache cleanup when edit menu settings or create new menu. No more
        manual cache update after each operation!
     -  New categories are now automatically synced into appropriate menu's. You don't
        need to manually import new categories into the tree!
 -  [ProLabels](/m2/extensions/prolabels/) — 1.3.2 (was 1.3.0)
     -  Use JSON to store labels conditions instead of "serialize".
     -  Show labels in recently viewed products widget.
     -  Fixed lables index update when save configurable product.
     -  Fixed incorrect prices in labels when tax included in price. Respect tax settings.
     -  Improve OnSale label determination for configurable products.
 -  [Reviewreminder](/m2/extensions/reviewreminder/) — 1.1.1 (was 1.1.0)
    -   Fixed missing delete button on the edit form
    -   Fixed save and continue from products tab
 -  [RichSnippets](/m2/extensions/richsnippets/) — 1.4.2 (was 1.4.1)
    -   Slightly improved product description for structured data.
 -  [SeoCanonical](/m2/extensions/seo-canonical/) — 1.0.3 (was 1.0.2)
    -   Improve module stability.
 -  [SeoPager](/m2/extensions/seo-pager/) — 1.2.0 (was 1.1.1)
    -   New feature - add page number to title of page where paginated content presented.
    -   Improved integration with Catalog Search pages.
 -  [SeoTemplates](/m2/extensions/seo-templates/) — 1.4.0 (was 1.3.0)
    -   New option for 'attribute' directive - `max_length` (set max allowed
        length for output). It can be usefull for attributes with long content.
    -   HTML tags removed from output of 'attribute' directive when respective
        attribute has marked as "html allowed".
    -   New config section "Optimize metadata" where you can set optimal length
        for metadata.
 -  [SeoUrls](/m2/extensions/seo-urls/) — 1.5.3 (was 1.5.1)
    -   Fixed compatibility with latest Swissup Ajaxsearch module.
        (“Nothing found” message appeared for any instant search request.)
 -  [SoldTogether](/m2/extensions/soldtogether/) — 1.6.2 (was 1.4.2)
    -   Fix warning during DI compilation at Magento 2.1.x.
    -   Prevent unwanted products in the cart after check/uncheck some checkboxes.
    -   Added ability to show suggestions based on shopping cart items. See
        [firecheckout intro popup example](/m2/extensions/firecheckout/customization/use-cases/intro-popup/#frequently-bought-together)
    -   Added mass action "Delete" at module grids. Now you can delete multiple relations at once.
    -   CLI commands to index/reindex Sold Together relations with bin/magento commands.
    -   Code cleanup

### Version 1.10.0

> May 02, 2019

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v1100 class="phone-up-1 tablet-up-3 photoswipe scroll" %}

 -  **Clean [configurable](/m2/argento/customization/checkout-styles/) checkout styles**
    —   This improvement will increase conversion rate and overall customer
        experience when browsing your store.
 -  **Refined compare toolbar** — Now it doesn't take a space in the header and
    remains visible on mobile devices.
 -  **Conditional tabs** in EasyTabs module.
 -  Refined ['Scroll to Top' button styles](/m2/argento/customization/add-scroll-up/).
 -  Small CSS fixes and improvements.
 -  RTL style fixes.
 -  ArgentoEssence:
    -   Fixed ability to change columns count in EasyCatalogImages widget on the homepage.
 -  ArgentoLuxury:
    -   Alternative logo option moved to the default Magento's logo option page:
        _Content > Design > Configuration_.
 -  ArgentoStripes:
    -   Added ability to [show quantity field](/m2/argento/stripes/customization/#show-qty-field-at-product-page)
        at the product page.
    -   Improved styles of contacts page.
    -   Fixed missing "Recently Viewed" block.
 -  Custom Themes:
    -   Fixed CSS and alternative logo issues in custom themes that are inherited
        from Luxury theme.

**Extensions Updates**

 -  [Ajaxpro](/m2/extensions/ajaxpro/)
    - Fixed css issue with argento 'compare products' toolbar
    - RTL fixes for floating cart mode
    - Fixed 'Delete item' confirmation popup behind overlay
 -  [Ajaxsearch](/m2/extensions/ajaxsearch/)
    - Added ability to show 'Popular Search Terms' when focusing empty search field
        (See _Stores > Configuration > Swissup > Ajaxsearch > Popular Search Terms Suggestions_ options.)
    - Small JS and CSS fixes
 -  [AMP](/m2/extensions/amp/)
    - FPC compatibility fixes
    - Fixed cache issue with navigation block
 -  [EasyCatalogImg](/m2/extensions/easyslider/)
    - CSS improvements
 -  [EasyFlags](/m2/extensions/easyflags/)
    -   Fix delete image for store view. Previously it was not possible to
        remove image assigned to store view.
    -   Improve compatibility with Magento 2.2.0.
 -  [EasySlide](/m2/extensions/easyslider/)
    - Fixed warning in logs about missing .map source file
 -  [EasyTabs](/m2/extensions/easytabs/)
    -   New feature - conditions for tabs. Now it is possible to show tab when
        customer is signed in or when product has some attribute value.
    -   Improved stability when there is tab for some third-party module but
        module is disabled or removed.
 -  [Fblike](/m2/extensions/facebooklikebutton/)
    - Improve CSS for custom button.
    - Fix not initialized like buttons. Update Facebook SDK.
 -  [Highlight](/m2/extensions/highlight/)
    - Fixed missing title image in magazine layout
    - Fixed invalid currency code when cache is enabled
 -  [Lightboxpro](/m2/extensions/lightboxpro/)
    - Fixed Vimeo video on product page
 -  [SeoSuite](/m2/extensions/seo-suite/)
    - Fixed structured data error for grouped and bundle products - `offerCount` can’t be empty.
    - Compatibility with PHP 7.2.
 -  [Testimonials](/m2/extensions/testimonials/)
    - Fixed image resize when height is empty

### Version 1.9.1

> Mar 29, 2019

 -  Magento 2.3 compatibility
 -  Small CSS improvements for RTL languages

**Extensions Updates**

 -  [Ajaxpro](/m2/extensions/ajaxpro/)
    - Fixed static content deployment on Magento 2.3 (There was an error about
      missing swatches.less file)
 -  [Ajaxsearch](/m2/extensions/ajaxsearch/)
    - Fixed possible XSS vulnerability
    - Fixes for RTL styles
    - Style improvements in search dropdowns
 -  [AMP](/m2/extensions/amp/)
    - Magento 2.3.1 compatibility (Fixed missing tabs at product page)
    - New customization [abilities added](/m2/extensions/amp/use-cases/#remove-tag)
 -  [EasySlide](/m2/extensions/easyslider/)
    - Magento 2.3.1 compatibility (Fixed broken backend form)
    - Added ability to start slider from [random slide](/m2/extensions/easyslider/interfaces/#slider-parameters)
 -  [GDPR](/m2/extensions/gdpr/)
    - Fixed mysql error on client consents page when table prefixes are used
 -  [HoverGallery](/m2/extensions/hover-gallery/)
    - Fixed broken html markup when product name has special symbols in the name
    - Removed invalid 'srcset' attribute
 -  [NavigationPro](/m2/extensions/navigationpro/)
    - Magento 2.3.1 compatibility (Fixed horizontal scrollbar)
    - Fixed invalid breadcrumbs when multiple menu's found on the same page
 -  [ProLabels](/m2/extensions/prolabels/)
    - Magento 2.3 compatibility (Fixed broken file uploader)
 -  [SoldTogether](/m2/extensions/soldtogether/)
    - RTL styles added
 -  [Testimonials](/m2/extensions/testimonials/)
    - Magento 2.3 compatibility (Fixed broken file uploader)

### Version 1.9.0

> Feb 26, 2019

 -  **Quantity Switcher** [module added](/m2/extensions/qty-switcher/)
 -  **8 New badges** added to [ProLabels module](/m2/extensions/prolabels/#version-126)

**Fixes and improvements**

 -  Fixed empty mobile navigation sidebar in ArgentoLuxury in Safari browser
 -  Fixed product gallery styles for RTL locales
 -  Fixed footer overlapping issue in IE11
 -  Fixed header styles in ArgentoFlat for medium screens
 -  Fixed broken editor in custom CSS field when js minification is enabled
 -  Fixed incorrect markup in product image in AMP site version
 -  Fixed incorrect canonical URL for homepage

**Extensions Updates**

 -  **AjaxSearch**: Added ability to disable directly from module configuration
 -  **Askit**: Added ability to write response in with html tags (for Admin users only)
 -  Small fixes in
    [AjaxPro](/m2/extensions/ajaxpro/changelog/#version-143),
    [AMP](/m2/extensions/amp/changelog/#version-121),
    [Askit](/m2/extensions/askit/changelog/#version-140),
    [EasyCatalogImages](/m2/extensions/easycatalogimages/changelog/#version-141),
    [NavigationPro](/m2/extensions/navigationpro/changelog/#version-192),
    [Highlight](/m2/extensions/highlight/changelog/#version-151),
    [RichSnippets](/m2/extensions/richsnippets/changelog/#version-131),
    [Testimonials](/m2/extensions/testimonials/changelog/#version-123),
    Suggestpage,
    and [SeoCrossLinks](/m2/extensions/seo-cross-links/changelog/#version-101)
    modules.

### Version 1.8.0

> Jan 4, 2019

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v180 class="phone-up-1 tablet-up-3 photoswipe scroll" %}

 -  Mobile-view styles improvements for the homepage in Argento Stripes theme.
 -  A lot of tiny mobile-view improvements in the header for all themes:
    - Icons alignment
    - Border and background color fixes
    - Logo alignment
 -  **More SEO features!**
    - [CrossLinks](/m2/extensions/seo-cross-links/)
    - [Canonical URL](/m2/extensions/seo-canonical/)
    - And a lot of must-have [fixes and improvements](/m2/extensions/seo-suite/changelog/#version-130)
 -  **AMP improvements**
    - "Add to cart" support for configurable products added
    - Rich snippets support added
    - Attributepages support added
    - Highlight pages support added
    - Cookie restriction mode added
    - Magento 2.1 and 2.2 compatibility fixes

**Fixes and improvements**

 -  Fixed 'Phantom Scrolling' bug in Chrome, when sticky menu us used
 -  Fixed empty sidebar menu in Safari browser in ArgentoFlat and ArgentoPure2 themes
 -  Fixed missing product image at the shopping cart page
 -  Fixed scroll to footer on page resize
 -  Fixed scroll to product list in ArgentoStripes and ArgentoLuxury themes at the
    category pages, when layered navigation is enabled

**Extensions Updates**

Almost all modules were updated with small improvements and fixes. Here is a few
highlighted changes:

 -  Many small fixes into variety of modules:
    - Better Magento 2.1 and 2.2 compatibility
    - CSS fixes and code cleanup
 -  Bugfixes:
    - Askit (Askit form on the homepage)
    - Easybanner (Broken backend charts on slow networks)
    - Highlight (Mobile style fixes)
    - Prolabels (Improved labels calculation for the children of configurable product,
        Fixed label reindex in Magento Commerce version)
    - SoldTogether (Fixed DB error during reindex, Magento 2.3 fixes, carousel
        styles fixes)

### Version 1.7.2

> Dec 4, 2018

 -  Magento 2.3.0 and 2.2.7 compatibility
 -  Fixed horizontal scrollbar on mobile devices
 -  Added missing image size config in view.xml (Magento 2.3.0 fix)

**Extensions Updates**

**swissup/module-ajaxpro — [1.4.2](/m2/extensions/ajaxpro/)** (was 1.4.1)

 -  Fixed 404 error (swatches.css file) in Magento 2.3.0
 -  Prevent accident shopping cart popup window when browsing accross the site

**swissup/module-ajaxsearch — [1.4.1](/m2/extensions/ajaxsearch/)** (was 1.4.0)

 -  Added 2.2.7 and 2.3.0 compatability
 -  Fixed broken CSS styles on the iPhone devices
 -  Fixed not working "Search" button on iOS devices

**swissup/module-attributepages — [1.1.1](/m2/extensions/attributepages/)** (was 1.1.0)

 -  Widget template updated according to the latest SlickCarousel module

**swissup/module-highlight — [1.4.1](/m2/extensions/highlight/)** (was 1.4.0)

 -  Widget template updated according to the latest SlickCarousel module
 -  Prevent possible non-seo links

**swissup/module-hreflang — [1.2.1](/m2/extensions/hreflang/)** (was 1.2.0)

 -  Remove not used `use` statement (Magento 2.3.0 compatibility)

**swissup/module-lightboxpro — [1.2.1](/m2/extensions/lightboxpro/)** (was 1.2.0)

 -  Magento 2.3.0 fixes
 -  Added correct alt text for preloading image

**swissup/module-navigationpro — [1.8.1](/m2/extensions/navigationpro/)** (was 1.8.0)

 -  Improved column-count calculation in Chrome browser

**swissup/module-pro-labels — [1.2.2](/m2/extensions/prolabels/)** (was 1.2.1)

 -  Performance improvements
 -  Improved javascript stability
 -  Slightly improved admin styles
 -  Improved logic to check if product has discount

**swissup/module-seo-pager — [1.1.1](/m2/extensions/seo-pager/)** (was 1.1.0)

 -  Added note in config about SEO Pagination

**swissup/module-seo-urls — [1.5.0](/m2/extensions/seo-urls/)** (was 1.3.2)

 -  New option added to enable rel="nofolow" in the layered navigation links
 -  Fixed possible js erorr when colorswatches are used in product listing
 -  Improved autogenerated URLs values
 -  Fixed possible fatal error when toggle canonical url option in config

**swissup/module-seo-xml-sitemap — [1.1.1](/m2/extensions/seo-xml-sitemap/)** (was 1.1.0)

 -  Use the same images as used on storefront. (Previosly Sitemap generated
    images that does not exist at storefront)

**swissup/module-slick-carousel — [1.3.0](/m2/extensions/slick-carousel/)** (was 1.2.0)

 -  SlickCarousel library updated 1.8.1

**swissup/module-sold-together — [1.4.0](/m2/extensions/soldtogether/)** (was 1.3.1)

 -  Template updated according to the latest SlickCarousel module
 -  Correct order for items at admin edit product page
 -  Fixed "Item with ID aleady exists" error
 -  Source code improvements

**swissup/module-testimonials — [1.2.1](/m2/extensions/testimonials/)** (was 1.2.0)

 -  Template updated according to the latest SlickCarousel module

### Version 1.7.1

> Nov 1, 2018

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-170---171)

 -  Small CSS fixes in Argento theme

**Extensions Updates**

 -  **AjaxPro** — 1.4.1
    -  Multiple fixes for cart slide mode
 -  **EasyCatalogImages** — 1.4.0
    -  Added ability to use widget with categories of one StoreGroup at another StoreGroup
    -  Fixed broken image url, if width wasn’t set to a proper number
 -  **GDPR** — 1.1.0
    -  Fixed mysql error on client consents page when table prefixes are used
 -  **Lightboxpro** — 1.2.0
    -  Improved compatibility with ProLabels
    -  Added correct alt text for preloading image
 -  **ProLabels** — 1.2.1
    -  Update label indexes when product updated
    -  Improve predefined variables search in label text
    -  Get product final and regular price properly
 -  **Richsnippets** — 1.2.1
    -  Remove tags in product description
    -  Added product brand to structured data
 -  **Regional and Language URLs** — 1.3.2
    -  Select swatches on listing when filter applied
    -  Fixed broken redirect to homepage when customer reaches respective CMS page via its URL
    -  Fixed 'Invalid return type' error on Magento 2.1.x
 -  **SEO Templates** — 1.1.1
    -  Improved metadata generation stability
    -  Fixed 404 for actions in admin grid
 -  **Soldtogether** — 1.3.1
    -  Improved code stability, prevent 'ID already exists' error
    -  Moved slick init params from template to block

### Version 1.7.0

> Sep 28, 2018

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-160---170)

**Major updates**

 -  Magento 2.2.6 compatibility
 -  Greatly improved [ProLabels](https://docs.swissuplabs.com/m2/extensions/prolabels/)
    module with [new backend interface](https://docs.swissuplabs.com/images/m2/prolabels/preview-demo.gif)
    and a bunch of [ready-to-use presets](https://docs.swissuplabs.com/images/m2/prolabels/presets-110.png).

**Extensions Updates**

 -  **Fblike** — 1.1.4
    - Fixed error "Action Requires At Least One Reference" when custom button is used
 -  **Navigationpro** — [1.7.0](https://docs.swissuplabs.com/m2/extensions/navigationpro/changelog/#version-170)
    - Magento 2.2.6 compatibility
    - Backend interface improvements
 -  **ProLabels** — [1.1.0](https://docs.swissuplabs.com/m2/extensions/prolabels/changelog/#version-110)
    - Backend interface improvements
    - Ready-to-use presets added

### Version 1.6.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-150---160)

 -  New [**Accelerated Mobile Pages**](/m2/extensions/amp/) module added
 -  Fixed styles for [**Firecheckout themes**](/m2/extensions/firecheckout/configuration/#theme)

**Extensions Updates**

 -  **AjaxPro** — 1.3.2
    -  Fixed js error
    -  Fixed redundant reload of AjaxPro sections
 -  **Attributepages** — 1.0.10
    -  Fixed delete mass action and store filter in admin grid
    -  Fixed error in options list when identifier is missing
    -  Fixed 404 error for options with html entities in name
 -  **Compare** — 1.0.1
    -  Css fixes
 -  **EasySlide** — 1.1.5
    -  Added AMP integration
 -  **Easy Catalog Images** — 1.2.1
    -  Added AMP integration
 -  **EasyTabs** — 1.3.3
    -  Fixed delete mass action and store filter in admin grids
 -  **GDPR** — 1.0.1
    -  Fixed possible issue with invalid config value
 -  **Hover Gallery** — 1.0.2
    -  Changed logic to determine image position in media gallery
    -  Added opacity transition for original image
 -  **SEO Suite** — 1.0.1
    -  Minor improvements and Magento 2.1.x compatibility fixes
 -  **Testimonials** — 1.1.0
    -  New testimonials listing page design
    -  New testimonials slider widget
    -  Added feature to export product review to testimonial
    -  Added config options to require rating and to disable testimonial submit for guests

### Version 1.5.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-140---150)

 -  New [**Compare module**](/m2/extensions/compare/) added
 -  New [**Regional and Language URLs** module](/m2/extensions/hreflang/) added as part of [Seo Suite](/m2/extensions/seo-suite/)
 -  New [**SEO XML Sitemap** module](/m2/extensions/seo-xml-sitemap/) added as part of [Seo Suite](/m2/extensions/seo-suite/)
 -  Css fixes for reviews toolbar
 -  Css fixes for Askit questions toolbar
 -  Added compatibility with Magento 2.2.5 when installing theme on 'All Store Views'

**Extensions Updates**

 -  **AjaxPro** — 1.3.1
    -  Added slide mode for modal dialog
    -  Added floating cart
    -  Fixed priceBox bug
    -  Fixed bug with disabled radio buttons in shipipng estimation
    -  Fixed configurable products add to cart issue on homepage
 -  **Askit** — 1.2.17
    -  Added email subject translation
 -  **Easybanners** — 1.2.3
    -  Fixed possible error on bundle product pages
 -  **EasyTabs** — 1.3.2
    -  Fixed activate and scroll to tab on external link click
 -  **Fblike** — 1.1.3
    -  Overall JavaScript improvements (load Facebook SDK only it is necessary, better utilization of Magento RequireJS functionality)
 -  **Hover Gallery** — 1.0.1
    -  Fixed both images visible issue when using transparent png product images
 -  **Navigationpro** — 1.6.0
    -  New menu styles: [Ribbon Menu](/m2/extensions/navigationpro/use-cases/ribbon-menu/), [Apple Menu](/m2/extensions/navigationpro/use-cases/apple-menu/), [Link Bar Mobile Menu](/m2/extensions/navigationpro/use-cases/link-bar/)
    -  New Use Case added: [Iconic Dropdown Menu](/m2/extensions/navigationpro/use-cases/iconic-menu/#dropdown-menu)
    -  Small CSS fixes
 -  **ProLabels** — 1.0.24
    -  Fixed php notice on Single Store mode in Edit Label interface
 -  **SEO Suite** — 1.0.0
     -  includes new module [Regional and Language URLs](/m2/extensions/hreflang/)
     -  includes new module [SEO XML Sitemap](/m2/extensions/seo-xml-sitemap/)
     -  *Richsnippets*  — 1.1.3
         -  Fixed missing breadcrumbs data at product pages in Magento 2.2.4+
         -  Fixed possible notice at product page with grouped product
         -  Using full description in snippet when short description is empty
     -  *SEO HTML Sitemap*  — 1.0.1
         -  Renamed admin menu item "HTML Sitemap Links" to "Sitemap Links"
         -  Fixed PHP fatal error in custom links grid when Magento Admin session expired
     -  *SEO URLs*  — 1.2.1
         -  Config section renamed from "Urls" to "SEO URLs"
         -  Integration with "Regional Urls (hreflang)" module
     -  *SEO Pager*  — 1.0.1
         -  Canonical URL now removed correctly
     -  *SEO Templates*  — 1.0.2
         -  Fixed error during compilation

### Version 1.4.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-131---140)

 -  New [**GDPR module**](/m2/extensions/gdpr/) added
 -  New [**SEO Metadata Templates** module](/m2/extensions/seo-templates/) added
 -  Fixed not working "Add to Cart" button on Stripes theme when ColorSwatches
    are used on the product page
 -  Fixed toolbar position on non-anchor 1-column page in Stripes theme
 -  CSS fixes for RTL languages
 -  Small CSS fixes

**Extensions Updates**

 -  **Askit**
    -  Magento 2.2.4 compatibility in email templates
    -  Added client-side form validators
 -  **Attributepages**
    -  Fixed error when page identifier is entered in invalid registry
 -  **Easybanners**
    -  Fixed image styles in [Book layout](/m2/extensions/easybanners/layouts-for-html-banners/#book)
 -  **Email**
    -  Added predefined smtp providers settings
    -  Fixed Magento 2.2.4 compatibility
 -  **Soldtogether**
    -  Added new config option that allows to disable 'Create relations on order save'
 -  **Navigationpro**
    -  Allow to use absolute links in [menu items](/m2/extensions/navigationpro/backend/menu-edit/#general-settings)
    -  [Nowrap feature](/m2/extensions/navigationpro/use-cases/nowrap/) added
    -  Improved dropdown positioning
    -  Small fixes and improvements

### Version 1.3.1

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-130---131)

 -  Magento 2.2.4 compatibility
 -  Fixed "jumping" carousel and tabs styles on the homepage during script initialization
 -  Fixed white links in Stripes menu, when NavigationPro is disabled
 -  Products carousel at the Mall's homepage replaced with Highlight ajax carousel widget
 -  Small css and js fixes

**Extensions Updates**

 - **Ajax Search**
     +  Add popular search terms suggestions when input is empty
     +  Improved initialization speed
     +  Add store filter to the cms page results

 - **Attributepages**
     +  Fixed 404 error in backend options grid, when using pagination

 - **Easytabs**
     +  Fixed possible “Requested product doesn’t exist” error, when editing cart item

 - **Fblike**
     +  Fixed compatibility with button initialization in ajax updated product listing

 - **Highlight**
     +  Fixed bug with Magento 2.2.4 when limit/sort order doesn't work

 - **Navigationpro**
     +  Fixed bug with Magento 2.2.4 when breadcrumbs are missing on the product page

 - **SoldTogether**
     +  Fixed issue with “Grouped” products price calculation in “Amazon” view

### Version 1.3.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-120---130)

 -  We introduce new colorful theme - Argento Stripes. Check it out at [Stripes Theme Demo](http://magento2demo.argentotheme.com/stripes_en/).
 -  No more "jumping search" during page loading.
 -  A lot of small fixes and improvements to provide your store the best user experience.

**Extensions Updates**

 - **Ajax Search**
     +  Category filter for search requests
     +  Grid layout for suggestions popup.

 - **Ajax Pro**
     +  Remove product review summary and tabs from add product popup.

 -  **Easybanners**
     +  Magento 2.1 compatibility.
     +  Removed url validation as it does not allow to use .html suffix.
     +  Fixed ‘Undefined variable: options’ error for banners without placeholders.
     +  Fixed 'display_count_per_customer' conditions when FPC is enabled.

 -  **Easy Catalog Images**
     +  Added configurable ‘Departments’ page with masonry layout style.

 -  **Easytabs**
     +  Expanded tabs layout added.

 -  **Highlight**
     +  Added ability to show products widget as ajax carousel.
     +  Fixed bug when you can’t call for multiple widgets with different conditions on the same page.
     +  Fixed php error when using pagination in ajax carousel

 -  **Navigation Pro**
     +  New simplified form to create menu with a few clicks.
     +  RTL support added.
     +  [Overlay feature added](http://docs.swissuplabs.com/m2/extensions/navigationpro/use-cases/overlay/).

 -  **ProLabels**
     +  Optimize labels rendering on storefront.

 -  **SEO Suite**
     +  *Richsnippets*:
         +  Do not add rating to snippet when product reviews do not have ratings.
     +  *SEO URLs*:
         +  Improve compatibility with not English speaking stores.

 -  **Sold Together**
     +  New Stripe layout for 'Frequently Bought Together' block. Now can can choose between 'Amazon Inspired' (default) and 'Stripe' layout style.

### Version 1.2.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-110---120)

 -  Added RTL support in Luxury theme _(currently in beta)_
 -  [SEO Pagination](/m2/extensions/seo-pager/) added as part of [Seo Suite](/m2/extensions/seo-suite/)

**Luxury Theme**

 -  Fixed missing items count on search result listing on mobile devices
 -  Fixed invisible action buttons on the homepage if standard listing is used
 -  Fixed cutted shadow on the top edge of the icon
 -  Bring back an opacity on the action icons in product listing

**Extensions Updates**

 -  **Ajax Pro** — 1.2.5
     -  Fixed redirect to product page when ?option=cart used
     -  Added missing translations
     -  Added product.view popup on home page
     -  Added checking if response is json
 -  **Ajax Search** — 1.2.8
     -  Fixed broken sort by relevance
     -  Added translations
     -  Fixed empty results when limit was equal to number of suggestions
 -  **Askit** — 1.2.12
     -  Fixed missing question label bug
 -  **Attribute Pages** — 1.0.7
     -  Added canonical url to integrate with seo-pager
 -  **Easy Banner** — 1.2.0
     -  Added new conditions
     -  "Don't show anymore" action added to lightbox and awesomebar banners
     -  New predefined HTML layouts
     -  Added ability to assign placeholder to parent container without using "Widgets" page
     -  Fixed not-working banner when it assigned to multiple stores
     -  Improved popup styles and positioning
     -  Backend forms rewritten using UI components
 -  **Facebook Like Button** — 1.1.1
     -  Fixed issues that occurred at some environments with JS minification enabled
     -  Using same product URLs to like on category and product pages
 -  **Navigation Pro** — 1.2.0.1
     -  Added ability to set positioning settings for the first level dropdown: Stick to Left, Center, Stick to Right
     -  Fixed browser freezing on mobile devices when using vertical subcategories alignment
 -  **Pro Labels** — 1.0.21
     -  Fixed warning illegal offset during CLI reindex
 -  **Review Reminder** — 1.0.11
     -  Fixed empty customer name for guests orders
 -  **Seo Suite** — 0.9.0
     -  includes new module [SEO Pagination](/m2/extensions/seo-pager/)
     -  *Rich Snippets*:
         -  Fixed duplicated product structured data on product page.
         -  Minify JSON-LD structured data.
         -  No empty nodes in JSON-LD structured data.
     -  *SEO URLs*:
         -  Fix URL parsing when URL rewrite ends with ‘/’.
         -  Disable SEO URLs when direct controller URL used instead of URL rewrite.
         -  Improved integration with Swissup ALN module (stock filter, rating filter, new filter).
         -  Improved query string parsing when multiple values applied to filter.
         -  If filter separator enabled add it to URLs only when there are applied filters.
 -  **Sold Together** — 1.2.4
     -  Using correct customer select for reindex, increased customer step
     -  Fixed exception 'Item with the same ID already exists'

### Version 1.1.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-100---110)

 -  [Lightbox Pro](/m2/extensions/lightboxpro/) added
 -  [Seo Suite](/m2/extensions/seo-suite/) added with the following modules:
     -  [Google rich snippets](/m2/extensions/richsnippets)
     -  [HTML Sitemap](/m2/extensions/seo-html-sitemap)
     -  [SEO URLs](/m2/extensions/seo-urls)
 -  Fixed missing ProLabels on product page when other theme was installed after previously installed Luxury

**Luxury Theme**

 -  Added homepage fullscreen slider configuration from admin
 -  Added sitemap link in footer links
 -  Fixed wrong logo position on new Ajax Search version
 -  Corrected Navigation Pro styles on homepage
 -  Fixed search icon position when store switcher is not displayed
 -  Fixed listing styles on mobile devices

**Extensions Updates**

 -  **Ajax Search** — 1.2.6
     -  Now product page is opened when click or press enter on the element in popup
     -  Added missing close button and spinner in folded mode
     -  Removed mistakenly added cacheable='false' param, which disabled FPC
     -  Fixed error CollectionFactory already in use
     -  Fixed search form submit only after second tap on mobile keyboard
 -  **Askit** — 1.2.11
     -  Fixed not unique form element ids
     -  Added config for "You have not submitted a question" message
     -  Update ui_component according to the latest requirements
     -  Fixed error on Magento versions before 2.2.0
     -  Fixed vote for question action
 -  **Easy Banner** — 1.1.1
     -  Fixed SQL error "1205 Lock wait timeout exceeded"
     -  Reduced number of database operations
     -  Fixed search at banner conditions page
     -  Code cleanup
 -  **Easy Catalog Images** — 1.1.5
     -  Fixed compatibility with Magento versions 2.1.x
 -  **Navigation Pro** — 1.1.0
     -  Added sidebar menu support
     -  Added navigation pro widget
     -  Added Amazon-like sidebar menu
     -  Fixes for mobile devices
     -  Fixed php error when switching store view in backend interface
     -  Improved dropdown positioning calculations
 -  **Pro Labels** — 1.0.20
     -  Fixed invalid discount values calculation for non-base currencies
 -  **Sold Together** — 1.2.3
     -  Fixed customer reindex (error occured when customer had no orders)
     -  Code cleanup

### Version 1.0.0

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-099---100)

 -  [NavigationPro](/m2/extensions/navigationpro/) added
 -  Css editor improved in theme editor backend. CSS syntax highlight added.

**Luxury Theme**

 -  Improved NavigationPro compatibility
 -  Fixed too long language switcher
 -  Out of stock phrase removed from listing
 -  Improved product quantity styles in header cart

**Extensions Updates**

 -  **AjaxSearch** — [1.2.5](/m2/extensions/ajaxsearch/changelog/#version-125)
 -  **Askit** — [1.2.8](/m2/extensions/askit/changelog/#version-128)
 -  **EasyCatalogImages** — [1.1.4](/m2/extensions/easycatalogimages/changelog/#version-114)
 -  **Prolabels** — [1.0.19](/m2/extensions/prolabels/changelog/#version-1019)
 -  **Reviewreminder** — [1.0.10](/m2/extensions/reviewreminder/changelog/#version-1010)

### Version 0.9.10

 -  Fixed critical vulnerability in EasyBanner module

**Extensions Updates**

 -  **AjaxPro** — 1.2.3
    - Fixed invalid xml layout update instructions
    - Improved compatibility with third-party modules
 -  **EasyBanner** — 1.0.12
    - Fixed critical SQL vulnerability
 -  **EasyTabs** — 1.2.1
    - Fixed ACL rules
 -  **ReviewReminder** — 1.0.10
    - Fixed wrong product url in email on multi-website store installation
 -  **SoldTogether** — 1.2.2
    - Fixed error when product is not available in registry

### Version 0.9.9

> [Upgrade Instructions](../upgrade-instructions/#version-097---099)

 -  **ArgentoLuxury** theme added. [View Docs](../luxury/)
 -  **Hover Gallery** module added. [View Docs](/m2/extensions/hover-gallery/)

**Extensions Updates**

 -  **EasySlide** — 1.1.4
    -   better widget compatibility with third-party modules
 -  **Highlight** — 1.1.2
    -   fixed widget styles
 -  **Facebook Like Button** — 1.1.0
    -   added custom like button layout
 -  **EasyTabs** — 1.2.0
    -  added tabs widget

### Version 0.9.8

 -  Magento 2.2 compatibility

### Version 0.9.7

> [Upgrade Instructions](/m2/argento/upgrade-instructions/#version-096---097)

 -  Added ability to [disable sticky header programmatically](/m2/argento/scripts/argento-sticky/)
 -  All modules updated according to Magento 2.1.7 changes
 -  DI compilation fixes

### Version 0.9.6

**Screenshots**

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v096 class="phone-up-1 tablet-up-3 photoswipe scroll" %}

> [Upgrade Instructions](../upgrade-instructions/#version-095---096)

 -  **ArgentoMall** theme added. [View Docs](../mall/)
 -  ArgentoMall [theme editor](/m2/argento/mall/theme-editor/) added
 -  [Ajax Pro](/m2/extensions/ajaxpro/) extension included

**List of Included Themes**

 -  **Argento Blank** — 0.9.6
 -  **Argento Essence** — 0.9.6
 -  **Argento Flat** — 0.9.6
 -  **Argento Pure2** — 0.9.6
 -  **Argento Mall** — 0.9.6

**Extensions Updates**

 -  **Ajaxsearch** — 1.2.3
    -   Without limit bug was fixed in product provider
 -  **Askit** — 1.2.4
    -   Cms pages integration
    -   Catalog categories integration
    -   You can search Askit questions in Magento admin top search
    -   Grid massactions logic fixed
    -   Grid full-text search fixed
 -  **Easybanner** — 1.0.8
    -   Fixed bug using multiple banners on one page
 -  **Rich Snippets** — 1.0.5
    -   Sort order fixed
    -   Acl added
    -   Fixed error in breadcrumbs json
    -   Added config to disable snippets


### Version 0.9.5

**Screenshots**

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v095 class="phone-up-1 tablet-up-3 photoswipe scroll" %}

> [Upgrade Instructions](../upgrade-instructions/#version-094---095)

 -  **ArgentoPure2** theme added. [View Docs](../pure2/)
 -  Sticky header added to the ArgentoFlat theme
 -  Improved reviews styles on small laptops and tablets
 -  Improved accordion styles
 -  Removed "Add to cart" button from products listing on small devices
 -  Vertical tabs added for laptops and tablets because horizontal tabs does
    not fit the screen width
 -  Bootstrap's `col-md-*` breakpoint changed to 768px
 -  Colorful socials icons [added](/m2/argento/customization/icons/#color-classes)
 -  Many small css improvements

**Fixes**

 -  Fixed horizontal scroll on checkout page
 -  Fixed FontAwesome icons vertical alignment
 -  Fixed incorrect position of submenu dropdown
 -  Fixed invalid dependency in `jquery.visible` plugin which cause js error in
    developer console

**Developer improvements**

 -  ArgentoSticky script added. [View Docs](../scripts/argento-sticky/)
 -  New mixins and classes:
    +  [Less mixins](/m2/argento/customization/less-mixins/)
    +  [Text block alignment classes](/m2/argento/customization/css-helpers/#text-and-block-alignment-classes)
    +  [Colorized social icons](/m2/argento/customization/icons/)

**List of Included Themes**

 -  **Argento Blank** — 0.9.5
 -  **Argento Essence** — 0.9.5
 -  **Argento Flat** — 0.9.5
 -  **Argento Pure2** — 0.9.5

**Extensions Updates**

 -  **Ajaxsearch** — 1.2.2
    -   Final_price replaced min_price in price template
    -   Small css fixes
 -  **Askit** — 1.2.4
    -   Fixed toolbar amount position on mobile devices
    -   Admin email notification was fixed
    -   Adming functionality fixes
 -  **Easybanner** — 1.0.7
    -   Fixed Image insert using WYSIWYG editor
 -  **Easyslide** — 1.1.1
    -   Small css fixes
 -  **FontAwesome** — 1.2.0
    -   Icons updated to 4.7.0
 -  **Prolabels** — 1.2.0
    -   Fixed missing badgets after cron job
    -   Small fixes

### Version 0.9.4

> [Upgrade Instructions](../upgrade-instructions/#version-093---094)

 -  ArgentoFlat [theme editor](/m2/argento/flat/theme-editor/) added
 -  Small css fixes to improve css customization in:
    +  Product listing widgets
    +  Footer links styles
    +  ArgentoFlat [jumbotrons](/m2/argento/flat/jumbotrons/)

**Prolabels**

 -  Fixed possible duplicate label in widgets listings
 -  Improved label loading method

**FontAwesome**

 -  Added ability to use font-awesome icons for backend modules

### Version 0.9.3

**Screenshots**

{% include gallery.html images=site.data.gallery.m2.argento.changelog.v093 class="phone-up-1 tablet-up-3 photoswipe scroll" %}

> [Upgrade Instructions](../upgrade-instructions/#version-092---093)

 -  ArgentoFlat theme added. [View Docs](../flat/)
 -  More Less variables to match developer customization needs
    - Product listing variables
    - Additional Product Tabs variables
    - Additional Navigation variables
    - Crossell, Upsell, Related products variables
 -  Product questions count added to tab title
 -  Improved product listing styles stability in various browsers
 -  Improved Rewiews Tab styles for large screens
 -  Added ability to include custom.js file
 -  Many small css fixes and improvements

**List of Included Themes**

 -  **Argento Blank** — 0.9.3
 -  **Argento Essence** — 0.9.3.1
 -  **Argento Flat** — 0.9.3

**Extensions Updates**

 -  **Ajaxsearch** — 1.2.0
    -   Added Folded Design feature, that hides input field and shows it in
        fullscreen mode with nice effect
    -   Small css fixes
 -  **Askit** — 1.2.0
    -   Added ability to show questions count in tab title
    -   Improved questions styles
    -   Styles rewritten in less with bunch of new variables that allow to change
        design easely
 -  **Easybanner** — 1.0.6.4
    -   Fixed empty spacing below banner
    -   Fixed banner url to product and category pages
 -  **Easycatalogimages** — 1.1.1
    -   Fixed issue in automatic category thumbnails assignment, thumbnails are now
        assigned to default store id
 -  **Easyslide** — 1.1.0
    -   Fixed empty spacing below slider
    -   Added slider themes:
        - Dark
        - White
        - Default (Blue)
 -  **Highlight** — 1.1.0
    -   Product listing styles rewritten to allow to use gutter between products
 -  **Soldtogether** — 1.1.6
    -   Fixed "Add all to cart" button alignment in amazon style mode
    -   Small css improvements

### Version 0.9.2

[Upgrade Instructions](../upgrade-instructions/#version-091---092)

 -  Theme editor added. [Read more](../customization/theme-editor/)
 -  Additional LESS variables added to simplify switching between
    [boxed, full-width and standard layout types](../customization/boxed-full-width-and-standard-layout-types/)
 -  FontAwesome configuration added. Now you can choose between CDN and local version.
 -  Fixed product listing glitches in Safari browser
 -  Bugfixes and improvements to:
    - Attributepages
    - ProLabels
    - SoldTogether
    - Testimonials
 -  [Askit](/m2/extensions/askit/) module added

### Version 0.9.1.2

 -  Additional Magento 2.1 compatibility
 -  Fixed issues with:
    - Core
    - EasySlide
    - SoldTogether
    - EasyBanners
    - Prolabels

### Version 0.9.1

[Upgrade Instructions](../upgrade-instructions/#version-090---091)

> Magento 2.0.* versions are no longer supported.
>
> Please update to Magento to 2.1 or newer to use latest Argento.

**List of Included Themes**

Theme           | Version
:---------------|:-------
Argento Essence | 0.9.2
Argento Blank   | 0.8.5

**Fixes and Improvements**

 -  Removed deprecated css fixes for tablet devices:
    - Added Accordion style to Layered navigation
    - Better Layered Navigation positioning for small tablets
 -  Homepage products count in sidebar blocks decreased to 2
 -  Fixed missing top border in product listing toolbar elements

**Extensions Updates**

All extensions updated according to Magento 2.1 version.

 -  **All Modules**
    - ACL fixes
    - Magento 2.1 compatibility
 -  Soldtogether
    - Slick Carousel added to `Customers Also Bought` block
 -  [Easy Catalog Images](/m2/extensions/easycatalogimages/)
    - Fixed error with missing Thumbnail class
 -  [EasyTabs](/m2/extensions/easytabs/)
    - Fixed missing js component in review tab
 -  Core
    - Added AdminNotification to be in touch with latest swissup updates

### Version 0.9.0

> **Important Notice**
>
> This release breaks compatibility with previous Argento version
> because of new Boostrap powered grid system, that replaces a bit buggy previous
> grid realization.
>
> In order to use new Argento version, you need to:
>
> - [Run installer](/m2/argento/installation/), that will
>   backup and create new cms blocks and homepage
> - Or apply content changes according to
>   [upgrade instructions](/m2/argento/upgrade-instructions/)

**List of Included Themes**

Theme           | Version
:---------------|:-------
Argento Essence | 0.9.1
Argento Blank   | 0.8.4

New Argento is shipped toghether with Swissup Module Manager, that could help you
to keep Swissup modules up to date and [install Argento Theme](/m2/argento/installation/)
in a few clicks.

**New Extensions**

 -  [Attribute based pages][attributepages]
 -  [Easybanner][easybanners]

**Extensions Updates**

 -  **All Modules**
    - Dependency injection compilation errors fixed
 -  [Ajax Search][ajaxsearch]
    - Improved dropdown styles
    - Added animation loader, when ajax request is processing
    - Fixed search field toggler on tablet devices
 -  [Easy Catalog Images][easycatalogimages]
    - Fixed broken page when placeholder is not deployed into pub/static
 -  [Easytabs][easytabs]
    - Fixed broken backend interface on initial load on some linux servers
 -  [Facebook Like button][fblike]
    - Fixed frontend error, when config is not saved

**Theme styles improvements**

 -  **General**
    - Bootstrap powered 12 columns grid added
    - Bootstrap responsive utilites added
    - Bootstrap responsive embed added
    - Bootstrap grid utilized to organize footer content
    - Cms content added aside to logo
 -  **Homepage changes**
    - Bootstrap grid utilized to organize content
    - Banner blocks replaced with Easybanner placeholders
    - Easyslider styles improvements
    - Brands slider manual scrolling fixed
    - All content is properly aligned with theme dimensions
 -  **Product Listing**
    - Fixed list mode styles
    - Grid mode styles improved
    - Widget styles improved

[ajaxsearch]: /m2/extensions/ajaxsearch/
[attributepages]: /m2/extensions/attributepages/
[easybanners]: /m2/extensions/easybanners/
[easycatalogimages]: /m2/extensions/easycatalogimages/
[easytabs]: /m2/extensions/easytabs/
[fblike]: /m2/extensions/fblike/

### Version 0.8.1

Initial release
