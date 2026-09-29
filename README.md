# Keshu documentation

Keshu is a Shopify theme for shops that sell toys, gifts, beauty, and things for the home.
It has soft shapes, friendly type, and gentle motion, and comes in three presets.

These pages use the same names you see in the theme editor. If something here doesn't match
what you see, tell us (see [Support](support.md)).

- [Get started](#get-started) (this page)
- [Theme settings](theme-settings.md): colors, fonts, buttons, product cards, animation, cart
- [Sections](sections.md): every section you can add to a page, and its settings
- [Product page](product-page.md): the gallery and every product block
- [Collection and search pages](collections-and-search.md): banner, filters, sorting
- [FAQ](faq.md)
- [Support](support.md): how to reach us and what support covers

## Get started

### 1. Add the theme

In your Shopify admin, go to **Online Store → Themes**, find Keshu in the Theme Store, and
choose **Try theme** or **Add to theme library**. The theme is added unpublished, so you can
set it up before customers see it.

### 2. Pick a preset

Keshu comes with three presets. Each one is a starting point with its own colors, fonts,
corner style, animation, and home page.

| Preset | Looks like | Good for |
|---|---|---|
| **Keshu** | Rounded corners, blush and plum, bouncy motion | Kids, toys, gifts |
| **Soft** | Cream and sage, serif headings, slow fades | Beauty, skincare, wellness |
| **Bold** | High contrast, big type, square corners, quick motion | Home, kitchen, decor |

You choose a preset when you add the theme. To switch later, add the theme again with the
other preset. Every preset uses the same settings, so you can also get from one look to
another by changing [theme settings](theme-settings.md).

### 3. Set up menus

The header uses your **Main menu** and the footer uses your **Footer** menu (Online Store →
Navigation).

- A menu item with items under it opens a dropdown in the header.
- If those items have items of their own (three levels), the dropdown becomes a wide menu with
  a column per second-level item.
- On phones, the menu opens in a drawer from the side.

### 4. Build your home page

Open **Customize**. The home page from your preset is already filled in with sections. Replace
the images and text with your own, remove what you don't need, and add sections with
**Add section**. See [Sections](sections.md) for what each one does.

### 5. Set up filters

Collection and search pages show filters from the free **Search and Discovery** app by
Shopify. Install it to choose which filters show and in what order. See
[Collection and search pages](collections-and-search.md).

### 6. Check before you publish

- Add a logo (Header section) and a favicon (Theme settings → Favicon).
- Add your social media links (Theme settings → Social media).
- Look at the store on a phone. Use the phone icon at the top of the theme editor.
- Open a product with options and add it to the cart.

## Custom data Keshu can use

Some blocks can show different content for each product through **metafields** (Settings →
Custom data). Keshu doesn't need any of them, but these help:

| What | Where it shows | How |
|---|---|---|
| A badge on product cards, like "New" or "Bestseller" | Product cards | Create a product metafield with namespace and key `keshu.badge`, type **Single line text**. |
| Specifications | Specifications block | Create a product metafield (type **Multi-line text**) and connect it to the block's Specifications setting. |
| Care or size text | Collapsible row block | Create a product metafield (type **Rich text** or **Multi-line text**) and connect it to the block's Text setting. |
| Bought together products | Bought together block | Create a product metafield (type **Product**, list) and connect it to the block's Products setting. |
| A banner image per collection | Collection page banner | Create a collection metafield (type **File**, image) and connect it to Banner background image. |

To connect a metafield, select the setting in the theme editor and use the **Connect dynamic
source** icon next to it.
