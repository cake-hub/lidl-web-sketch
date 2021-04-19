<AlertWarning alertHeadline="Not modifiable">
 It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Pricebox

The use of the consistent Lidl pricebox is an elementary part of our brand awareness.

The pricebox contains several fix and optional elements and is available in different color combinations due to different visualizations (standard, offer, lidl-plus, etc.).

---

## Recommendations

- If there is already a currency symbol in the price box no additional currency sign should be displayed in the recommended retail price or label.

---

## Elements

| Types | Attributes | Preview |
|---|---|---|
| Basic | 1. Prefix <br> 2. Price <br> 3. Asterik <br> 4. Currency |![basic pricebox](assets/forms/basic@1x.png)|
| Offer | 5. Label <br> 6. Basic pricebox |![offer pricebox](assets/forms/offer@1x.png)|
| Discount | 7. Discount text <br> 8. Recommended Retail Price (rrp) |![discount pricebox](assets/forms/discount@1x.png)|

---

## Overall styling

- The text-style is [pricebox-small](../../General/Typography/Typography.md#pricebox-small) or [pricebox-medium](../../General/Typography/Typography.md#pricebox-medium) for the two possible sizes of the price.
- The text-style is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for asterisk, currency & prefix.
- The line-height is set to **default**.
- Additionally you can choose between a pricebox with or without prefix.

| Types | Attributes | Preview |
|---|---|---|
| Basic | text-color: gray-darker <br> background-color: basic-white <br> outline-color: gray-light |![basic pricebox](assets/basic-box/small-no-prefix@1x.png) ![small pricebox with prefix](assets/basic-box/small-with-prefix@1x.png)|
| Action | text-color: basic-white <br> background-color: danger-base <br> outline-color: danger-base |![action pricebox](assets/basic-box/small-no-prefix-action@1x.png) ![action pricebox with prefix](assets/basic-box/small-with-prefix-action@1x.png) |

## Sizes

- There are two sizes of this component for different purposes.
- For each breakpoint, you can select a corresponding symbol with different price text sizes to suit your layout.

| Size | Usage | Preview |
|---|---|---|
| Small | i.e. product overview | ![small pricebox no prefix](assets/basic-box/small-no-prefix@1x.png)|
| Medium | i.e. product detail page | ![medium pricebox no prefix](assets/basic-box/medium-no-prefix@1x.png)|

---

## Label

- The text-style always is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon).
- The line-height is set to **default**.
- Always use the **base-color** as background-color.
- Combine the standard pricebox with a label to display promotions or discounts.
- Use the label as an add-on for the **offer** pricebox.
- You can advertise discounts, promotions or offers.
- Like the pricebox, you can choose between different label colors.

| Types | Attributes | Preview |
|---|---|---|
| Action | text-color: basic-white <br> background-color: danger-base | ![action label](assets/elements/labels/action@1x.png) |
| Offer | text-color: gray-darker <br> background-color: mark-base | ![offer label](assets/elements/labels/offer@1x.png) |

---

## Basic quantity

- The text-style always is [small](../../General/Typography/Typography.md#small).
- The line-height is **120%**.
- It's used as additional info for the packaging unit, quantity or drained weight.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text-color: gray-darker | ![basic quantity](assets/elements/basic-quantity@1x.png) |

---

## Discount

- The text-style always is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for the discount text and the recommended retail pice (rrp).
- The line-height is set to **default**.
- If you want to use a discount, it can be placed in the pricebox **standard** (positive) as well as in the pricebox **offer** (negative) - with or without prefix.
- The strike comes either in **danger-base** or **gray-darker** with a **1px thickness**.
- There is a positive and negative version matching the underlying standard pricebox.

| Types | Attributes | Preview |
|---|---|---|
| Positive | text-color: gray-darker <br> strike-color: danger-base | ![discount positive](assets/elements/discount/positive@1x.png) |
| Negative | text-color: basic-white <br> strike-color: gray-darker | ![discount negative](assets/elements/discount/negative@1x.png) |

---

## Spacing & Measurements

- The height of the pricebox depends on the content and the additional components shown.
- The width of the pricebox depends on the content.
- The width of the label denpends on the content of the pricebox.
- The height of the label is fixed for a single-line text.
- **Exception!** Designers set the margins to 4px due to a Sketch software problem with different text block widths while **the development uses 2px**.

### Pricebox

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | LG: 8px <br> MD+SM: 8px<br> XS: 4px | ![pricebox horizontal spacing LG](assets/measurements/basic/horizontal/LG@1x.png) ![pricebox horizontal spacing XS](assets/measurements/basic/horizontal/MD+SM@1x.png) ![pricebox horizontal spacing XS](assets/measurements/basic/horizontal/XS@1x.png) |
| Horizontal spacing | LG: 8px / 4px <br> MD+SM: 8px / 4px<br> XS: 4px / 4px | ![pricebox vertical spacing LG](assets/measurements/basic/vertical/LG@1x.png) ![pricebox vertical spacing LG](assets/measurements/basic/vertical/MD+SM@1x.png) ![pricebox vertical spacing XS](assets/measurements/basic/vertical/XS@1x.png) |

### Label

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing |  LG: 4px / 12px<br>MD+SM: 4px / 12px<br>XS: 2px / 10px | ![label LG vertical spacing](assets/measurements/label/vertical/LG@1x.png) ![label MD+XS vertical spacing](assets/measurements/label/vertical/MD+SM@1x.png) ![label XS vertical spacing](assets/measurements/label/vertical/XS@1x.png) |
| Horizontal spacing | LG: 8px<br>MD+SM: 8px<br>XS: 4px | ![label LG horizontal spacing](assets/measurements/label/horizontal/LG@1x.png) ![label MD+SM horizontal spacing](assets/measurements/label/horizontal/MD+SM@1x.png) ![label XS horizontal spacing](assets/measurements/label/horizontal/XS@1x.png) |
| Height | LG: 30px<br>MD+SM: 28px<br>XS: 24px | ![label LG height](assets/measurements/label/height/LG@1x.png) ![label MD+SM height](assets/measurements/label/height/MD+SM@1x.png) ![label XS height](assets/measurements/label/height/XS@1x.png) |

### Discount

| Types | Attributes | Preview |
|---|---|---|
| Discount | LG: 8px / 0px<br>MD+SM: 8px / 0px<br> XS: 4px / 0px | ![discount LG](assets/measurements/discount/small/LG@1x.png) ![discount SM-MD](assets/measurements/discount/small/SM-MD@1x.png) ![discount XS](assets/measurements/discount/small/XS@1x.png) |

---

## Position

### Label

- The pricebox always **overlays the label by 8px**.

| Types | Attributes | Preview |
|---|---|---|
| Offset | LG: 8px <br> MD+SM: 8px <br> XS: 4px | ![label position LG](assets/position/label/LG@1x.png) ![label position MD+SM](assets/position/label/MD+SM@1x.png) ![label position XS](assets/position/label/XS@1x.png) ||


### Basic quantity

- This information always is placed to the **right below the pricebox**.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text and pricebox align right <br> margin-top: 2px | ![special offer](assets/position/basic-quantity@1x.png) |

---

## Combinations

- There are **different combinations** of priceboxes and labels in the Lidl universe.
- They are called "themes".

| Types | Attributes | Preview |
|---|---|---|
| Offer #1 | label: action <br> pricebox: standard | ![offer #1](assets/combinations/offer-1@1x.png) |
| Offer #2 | label: offer <br> pricebox: standard | ![offer #2](assets/combinations/offer-2@1x.png) |
| Special offer | label: offer <br> pricebox: action | ![special offer](assets/combinations/special-offer@1x.png) |

---

## Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Enter the text first. Then adjust the width of the symbol.
- The color variants of the label can be selected in the complete pricebox via the "Overrides"-function.
- The discount has to be added manually as a symbol to the pricebox:
  - First change the height.
  - Second, place the discount in the middle with the corresponding padding.
  - Finally insert the text via the "Overrides"-function.
