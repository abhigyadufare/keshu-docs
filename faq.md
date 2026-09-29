# FAQ

### How do I make the store look like the demo?

Choose the matching preset when you add the theme: Keshu, Soft, or Bold. The home page and
product page come set up like the demo. Your own products, collections, menus, and photos
replace the demo's.

### Where do I change colors?

Theme settings → **Colors**. Each section picks one of those color schemes. See
[Colors](theme-settings.md#colors).

### Why don't I see filters on my collection pages?

Filters need the free **Search and Discovery** app, and products with the data to filter on
(for example, a Color option). Also check **Show filters** in the collection page's
**Collection** section.

### How do I show a "New" or "Bestseller" badge on a product?

Create a product metafield `keshu.badge` (Single line text) in Settings → Custom data, then
type the badge on each product. See [Custom data](README.md#custom-data-keshu-can-use).

### Color swatches show as plain buttons. Why?

Swatches come from your product options. In the product editor, set the option (like Color)
to use a category metafield or your own swatch colors. Options without swatch data show as
buttons.

### The free shipping bar doesn't show for some customers.

**Free shipping threshold** (Theme settings → Cart) is in your store's currency, so the bar
only shows to customers shopping in that currency. A converted amount wouldn't match the
shipping rate they see at checkout. Set the threshold to match your free shipping rate in
Settings → Shipping and delivery; the bar only shows progress toward it.

### How do I turn off the animations?

Theme settings → **Animation** → **Animation level** → **Off**. Visitors who turn on reduced
motion on their device never see animation.

### Can customers pick a language or country?

Yes, once you add them in Settings → Languages and Settings → Markets. Then turn on the
selectors in the **Footer** section. The mobile menu shows them too.

### Does Keshu support right-to-left languages?

Yes. Layouts, arrows, and drawers flip for languages like Arabic and Hebrew.

### How do I add a size chart?

Create a page with the chart, then add a **Collapsible row** block to the product page and
choose it under **Page content**.

### Can I edit the theme's code?

Yes, but **duplicate the theme first** (Online Store → Themes → ⋯ → Duplicate) and edit the
copy. Code changes aren't covered by support, and a theme update won't include them. For
small additions, use a **Custom Liquid** section or block instead.

### How do I update Keshu?

When a new version is out, Shopify shows it in Online Store → Themes. Updating adds a new copy
of the theme with your settings and content; your current theme stays as it is until you
publish the new one.
