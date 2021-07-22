<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Ribbons

Use ribbons to add unique selling prepositions or other information.

Basically it is positioned in a context with a product tile, teaser, or image.

---

## Overall styling

- The text style is [small bold](../../General/Typography/Typography.md#small-bold).
- The line height is **120%**.
- The image has a **free-ratio**.
- The color of the triangle always is **gray-darker**.
- The background-shadow is **shadow-default**.
- The background has **rounded corners of 2px on the upper- & lower-left**.

---

## Recommendations

- If you decide to use a ribbon, never use more than a **maximum of 2 variations** <br>*(our "info" ribbon matches our brand-primary color due to the purpose of the color "blue")*.
- At best, the width of the ribbon should not overlap more than **50% of the underlying element**.

---

## Variants

- The ribbon has 4 colored variations: **primary**, **highlight**, **gray** and **info**.
- And can be used to show 2 different contents: **text** and **image**.

| Variants | Attributes | Preview |
|---|---|---|
| primary | text-color: basic-white<br>background-color: brand-primary-base | ![primary](assets/variants/primary@1x.png) |
| highlight | text-color: basic-white<br>background-color: danger-base | ![highlight](assets/variants/highlight@1x.png) |
| gray | text-color: basic-white<br>background-color: gray-base | ![gray](assets/variants/gray@1x.png) |
| info | text-color: basic-white<br>background-color: info-base | ![info](assets/variants/info@1x.png) |

---

## Spacing & measurements

### Desktop (LG)

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding-left/-right: 8px<br>text-alignment: centered | ![Horizontal spacing (LG)](assets/measurements/LG/horizontal-spacing@1x.png) |
| Vertical spacing<br>*Only for the image ribbon*  | padding-top/-bottom: 8px | ![Vertical spacing (LG)](assets/measurements/LG/vertical-spacing@1x.png) |
| Size | triangle: 8x8px | ![Size: triangle (LG)](assets/measurements/LG/size@1x.png) |
| Height | ribbon: 32px<br>with triangle: 40px | ![Height (LG)](assets/measurements/LG/height@1x.png) |

### Tablet & smartphone (MD-XS)

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding-left/-right: 4px<br>text-alignment: centered | ![Horizontal spacing (MD-XS)](assets/measurements/MD-XS/horizontal-spacing@1x.png) |
| Vertical spacing<br>*Only for the image ribbon*  | padding-top/-bottom: 4px | ![Vertical spacing (MD-XS)](assets/measurements/MD-XS/vertical-spacing@1x.png) |
| Size | triangle: 4x4px | ![Size: triangle (MD-XS)](assets/measurements/MD-XS/size@1x.png) |
| Height | ribbon: 20px<br>with triangle: 24px | ![Height (MD-XS)](assets/measurements/MD-XS/height@1x.png) |

---

## Position

- A ribbon takes its place at the **upper right corner**.
- The distance of the first ribbon on an element to the upper edge is **8px**.
- Several ribbons have **no distance** to each other at the bottom.

![position](assets/position/product-tile@1x.png)

---

## What can be modified?

- Override the text and image.
- Adjust the height and width according to the text.
- Adjust the height and width according to the image ratio.
- Modify ribbons to your project needs by changing the content to another element (i.e. to an icon or an icon with text).
