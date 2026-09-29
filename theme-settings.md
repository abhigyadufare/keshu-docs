# Theme settings

Theme settings change the whole store. In the theme editor, open them with the paintbrush
icon (**Theme settings**) in the left sidebar.

## Colors

Keshu uses **color schemes**. A scheme is a set of colors that go together, and each section
picks one with its **Color scheme** setting. Change a scheme here and every section using it
changes too.

Each scheme has:

| Color | Used for |
|---|---|
| Background | The section's background |
| Background gradient | Replaces the background with a gradient, if set |
| Text | Headings and body text |
| Accent | Links, italic words in headings, sale prices, focus outlines, and illustrations |
| Button | Filled buttons |
| Button label | Text on filled buttons |
| Border | Outlines, dividers, and input borders |

Keep text readable: pick **Text** and **Background** colors with strong contrast, and the
same for **Button label** and **Button**. A contrast checker (search for "WCAG contrast
checker") tells you if a pair passes; aim for at least 4.5 to 1.

## Typography

- **Heading font** and **Body font**: any font from Shopify's font library. Bold and italic
  styles load automatically.
- **Heading size**: scales every heading up or down.
- **Body text size**: the size of paragraphs, labels, and prices.
- **Heading case**: show headings as typed, or in uppercase.

## Layout

- **Page width**: Narrow or Wide. Sections set to use the full page width ignore it.
- **Page margin**: space at the left and right edges of the page.
- **Space between sections**: vertical space between sections. Each section also has its own
  top and bottom padding.

## Style

- **Corners**: Square, Soft, or Round, for cards, images, and panels.
- **Button shape**: Pill, Rounded, or Square.
- **Button font**: use the heading font or the body font on buttons.
- **Show raised edge**: adds a darker edge under buttons that presses in when clicked.
- **Input style**: Outlined or Filled, for text fields, dropdowns, and the search bar.
- **Card style**: Soft shadow, Outline, or None, for product cards and other cards.
- **Badge style**: Sticker, Pill, or Square, for Sale, Sold out, and custom badges.
- **Show stitched dividers**: draws dividers and outlines as a dashed stitch line.

## Product cards

These apply to product cards everywhere: collections, search, and featured collections.

- **Image shape**: Square, Portrait, or Natural. Natural uses the shape of each collection's
  first product image, so every card in a grid matches.
- **Show second image on hover**: shows the product's second image when a mouse is over the card.
- **Show vendor**
- **Show color swatches**: shows the product's color options as small swatches. Clicking one
  opens quick add with that color selected.
- **Show quick add**: adds a button to each card. Products without options go straight into
  the cart. Products with options open a window to choose them first.
- **Quick add button**: **Text** shows a full-width button under the card. **Icon** shows a
  small cart button on the image that shows its label when hovered.

Cards show a **Sale** badge when a product has a compare-at price, and **Sold out** when
nothing is in stock. See [Custom data](README.md#custom-data-keshu-can-use) to add your own
badge.

## Animation

- **Animation level**:
  - **Off**: nothing moves.
  - **Subtle**: sections fade in as visitors scroll, cards in a grid appear one after another,
    and a product's photo flies to the cart icon when added.
  - **Expressive**: everything in Subtle, plus headings appear word by word and slideshow and
    image with text photos move slower than the page as it scrolls (in browsers that support
    scroll animations, like Chrome, Edge, and Safari).
- **Animation style**: the feel of the motion: Gentle, Playful (a little bounce), or Snappy.

Visitors who turn on reduced motion on their phone or computer see no animation, whatever
this is set to.

## Cart

- **Cart type**: **Drawer** opens the cart from the side of the page after adding a product.
  **Page** takes customers to the cart page.
- **Show discount code field**: lets customers enter discount codes in the cart. You can also
  leave this off and let them use the field at checkout. In a narrow cart, like on phones,
  the Apply button shows as an arrow.
- **Show order note**: lets customers leave a note with their order.
- **Free shipping threshold**: the order total, in your store's currency, that gets free
  shipping. The cart shows a progress bar toward it. Leave it empty to hide the bar. This
  setting only shows the bar; set up the free shipping rate itself in Settings → Shipping and
  delivery.
- **Suggested products**: up to 3 products to suggest in the cart. Products already in the
  cart are left out.

## Favicon

The small icon in the browser tab. Use a square .png, 32 × 32px.

## Social media

Add the web address of each account you have. The footer shows an icon for each one when
**Show social media icons** is on in the Footer section.
