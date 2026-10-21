# Smart Headline Pro

<p align="center">
  <img src"assets/banner.png">
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/AppsTRDesign/Smart-Headline-Pro">
  <img src="https://img.shields.io/github/downloads/AppsTRDesign/Smart-Headline-Pro/total">
  <img src="https://img.shields.io/badge/WordPress-6.0%2B-21759b?logo=wordpress" alt="WordPress 6.0+">
  <img src="https://img.shields.io/badge/PHP-7.4%2B-777bb4?logo=php&amp;logoColor=white" alt="PHP 7.4+">
  <img src="https://img.shields.io/badge/license-GPLv2%2B-16a34a" alt="GPLv2 or later">
</p>

<p align="center">
  <a href="https://wplugins.shop/eklenti/smart-headline-pro.zip"><b>⬇ Download</b></a> ·
  <a href="README.tr.md">🇹🇷 Türkçe</a>
</p>

Query driven WordPress headline sliders with 13 responsive layouts, a Gutenberg block, context-aware latest posts, automatic placement rules, and a shortcode/PHP helper.

**Developer:** AppsTRDesign · [wplugins.shop](https://wplugins.shop) · **Version:** 2.4.2

## Highlights

- Thirteen layouts: Hero, Split, Classic, Minimal, Cards, Cinematic, Magazine, Ticker, Newsroom, Editorial, Category Groups, Category Slideshow, and Related Posts. Click the selected layout again to deselect it.
- Query recent posts, selected categories/tags, a search term, explicit post IDs, or related posts; select posts/pages, result count, and sort order.
- Context-aware **Latest posts**: on category, tag, and custom taxonomy archives only that term's latest posts are shown, on search pages only posts matching the search text, and on single posts the current post is excluded.
- Category Groups and Category Slideshow: a "maximum categories" limit that is active only when no category is selected and disabled automatically once categories are chosen.
- Category Slideshow tab position (left, top, or right) available when the source type is *Selected categories*; tablets and phones always stack the tabs on top.
- Realistic live preview rendered by the real front-end code for all 13 layouts, with desktop, tablet, and mobile widths and light/dark backgrounds.
- Toggle title, category, excerpt, stripped plain-text content, date, author, comment count, reading time, and CTA independently.
- Set desktop/mobile height, title/body sizes and colors, ten Google Font presets or custom Google Fonts, plus filled, outline, or minimal navigation arrows, image focal point, overlay, autoplay, timing, dots, numbers, progress, and thumbnail navigation.
- Automatically place sliders before or after content on home/blog views, singular posts/pages, category/tag archives, search results, or all content areas.
- Theme-view safe: the headline stays visible in themes that offer grid/list/mini switches and below 765px, even when a theme hides its view container.
- AJAX dashboard with modal editing, confirmations, status dialogs, and complete JSON settings import/export.
- Gutenberg block, `[smart_headline id="your-slider-id"]`, and `smart_headline('your-slider-id')` theme helper.
- Modular PHP classes and namespaced CSS/JavaScript assets.

## Installation

1. Upload `smart-headline-pro` to `/wp-content/plugins/` or install the ZIP from WordPress.
2. Activate **Smart Headline Pro** in Plugins.
3. Create a slider in the **Smart Headline Pro** dashboard and configure its content query and components.
4. Copy its shortcode, select it in the Gutenberg block, or enable automatic placement rules. Placement rendering includes a re-entry guard to avoid nested content-filter loops.

## Shortcode

```text
[smart_headline id="your-slider-id"]
```

For theme templates call `smart_headline('your-slider-id')`. To return the generated markup, use `smart_headline_render('your-slider-id')`.

## Requirements

- WordPress 6.0 or later
- PHP 7.4 or later

## License

GPL-2.0-or-later. See the plugin package for the license notice.
