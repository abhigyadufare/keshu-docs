# Product page

The product page has the gallery on one side and blocks on the other. Add, remove, and
reorder blocks in the theme editor to choose what shows and in what order. The same blocks
work in the **Featured product** section.

## Gallery

The gallery shows one photo, video, or 3D model at a time, with arrows and thumbnails. On
computers it stays in view beside the details while the customer scrolls. When a customer
picks a variant, its photo shows first.

- **Thumbnail position**: **Below** the image or down the **Left** side. Phones always show
  them below.
- **Image zoom**: **Open full screen** shows every photo large, one under the other.
  **Magnify on hover or tap** zooms the photo in place; with a mouse it follows the pointer,
  and on a phone a tap zooms in and a drag moves around.
- **Show sticky buy bar**: a bar with the product, price, and **Add to cart** that appears at
  the bottom of the screen once the buy buttons scroll out of view.

Videos and 3D models load only when the customer presses play, so they don't slow the page.

**Tip:** use photos with the same shape for a product. The gallery takes the first photo's
shape, and taller or wider photos fit inside it.

## Blocks

### Title, Vendor, Price

- **Title**: **Heading size** is Large, Medium, or Small.
- **Vendor**: the product's vendor.
- **Price**: the price, the compare-at price when it's on sale, and the unit price when the
  product has one. **Show tax and shipping note** adds "Shipping calculated at checkout" (linked to your
  shipping policy if you have one) and, when your prices include tax, says so.

### Variant picker

One picker per option, like Size and Color. **Style** is **Buttons** or **Dropdown**. Options
with swatches (set up in the product's options) always show as swatches. Options that are
sold out stay selectable, crossed out, so customers can see them.

### Buy buttons

- **Show quantity selector**
- **Show dynamic checkout buttons**: shows the customer's preferred payment method, like
  PayPal or Apple Pay.
- **Show gift card recipient form**: on gift card products, lets customers send the gift card
  to someone else, with a message, on a date they choose.

When a product sells subscriptions, the subscription options show above the buttons.
When Shop Pay Installments is available, a line about it shows under the price.

### Inventory status

Shows "In stock", "Out of stock", "Out of stock, ships when restocked" (when you keep selling
without stock), or, when stock falls to the **Low stock threshold**, "Only 3 left". It reads your real inventory, so the product needs inventory tracking on.

### Pickup availability

Shows whether the selected variant can be picked up at your nearest location, and opens to
list every pickup location and when the order is ready. Shows nothing if no location has local pickup turned on (Settings →
Shipping and delivery).

### Delivery estimate

An estimated delivery date range, worked out from your own shipping times:

- **Fastest delivery, in working days** and **Slowest delivery, in working days**.
- **Order cutoff hour**: orders after this hour, in your store's time zone, ship the next
  working day. Working days are Monday to Friday.
- **Local delivery postal codes** and **Local delivery message**: add postal codes (one per
  line) to show a field where customers check if you deliver to them. Each code matches every
  postal code that starts with it, so `97` matches `97205`.

The estimate doesn't check with a carrier. Keep the numbers realistic.

### Offer box

A highlighted box for a real offer or promise, like "Free gift wrap this week". Set an
**Icon**, **Heading**, **Text**, and **Color scheme**. Connect **Text** to a product metafield
to show a different offer on each product.

### Volume pricing

For B2B customers with quantity price breaks in their catalog: a table of the price at each
quantity. Other customers don't see it.

### Gift message

A field for a gift note, saved with the order line as "Gift message". Set a **Heading** and
**Maximum characters**.

### Description

The product description.

### Specifications

A table of details, like size, material, and weight. Type one per line, as `Label: value`,
for example `Material: Beech wood`. Connect it to a product metafield to show each product's
own details. **Open by default** shows it open.

### Collapsible row

A heading that opens to show text, like care or sizing. Use **Text**, or **Page content** to
show a page (the same text on every product). Connect **Text** to a product metafield for
different text on each product. **Open by default** shows it open.

### Trust icons

A row of short points with icons, like "Free returns" and "Secure checkout". Add an **Icon
with text** block for each one.

### Bought together

This product plus up to 3 others, each with a checkbox and one button to add them all. Products
with options get a dropdown to choose one. Connect **Products** to a product metafield (a list
of products) so each product has its own set.

### Complementary products

Products that go well with this one, from the **Search and Discovery** app (Complementary
products). Set a **Heading** and **Products to show**. Hidden when a product has none.

### Share button

Opens the phone's share menu, or copies the product link on a computer.

### Custom Liquid and app blocks

Add app blocks from apps you've installed, or your own code with **Custom Liquid**.
