<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Product tile

Each product is presented with the product tile.

The product tile is a basic component which can be combined with other components (e.g.: price-fields, ribbons, availabilities, etc).


---

## Recommendations

- Ideally, the product title should be single-line or a maximum of two lines.
- The look of the default product tile is not mandatory. We only deliver a default product tile that can be modified to your projects needs.
- Change the text styles for your project needs but please stick to the given [text styles](../../General/Typography/Typography.md) of CAKE.


---

## Overall styling

- The text style of the product title is [basic](../../General/Typography/Typography.md#basic).
- The text style of the product description is [small](../../General/Typography/Typography.md#small).
- The line-height is **120%**.
- The image ratio always is **4:3**.
- The components has **rounded corners of 2px**.
- Every state uses the **shadow-default**.
- The height of the white area depends on the content and the additional components shown.
- All widths are fixed and aligned to the layout grid of the breakpoints.
- The width of the component is divisible by 8 and equal to the image-width.


| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker <br> background-color: basic-white | ![product-tile default](assets/status/default@1x.png) |
| Hover / focus | text-color: gray-darker, underlined <br> background-color: basic-white <br> image overlay: basic-white with 50% opacity | ![product-tile hover-focus](assets/status/hover-focus@1x.png) |

---

## Spacing & measurements

| Types | Attributes | Preview |
|---|---|---|
| Image size | Always ratio 4:3 | ![product-tile image](assets/measurements/LG/image-width@1x.png) |
| Overall <br> Padding | LG - SM: 16px <br> XS: 8px| ![product-tile padding LG-XS](assets/measurements/LG/padding@1x.png) ![product-tile padding XS](assets/measurements/XS/padding@1x.png)|
| Padding <br> title to description| LG - SM: 8px <br> XS: 4px | ![product-tile margin LG](assets/measurements/LG/margin@1x.png) ![product-tile margin XS](assets/measurements/XS/margin@1x.png) |

---

## Position

| Types | Attributes | Preview |
|---|---|---|
| LG | 4 tiles with width over 3 columns | ![position: LG](assets/position/LG@1x.png) |
| MD | 4 tiles with width over 3 columns | ![position: MD](assets/position/MD@1x.png)|
| SM | 2 tiles with width over 2 columns | ![position: SM](assets/position/SM@1x.png) |
| XS | 2 tiles with width over 1 column | ![position: XS](assets/position/XS@1x.png) |

---

## What can be modified?

- Override the text and image.
- Adjust the height.
- Change the text to a two line scenario.
- Modify product tiles to your project needs by adding other symbols to the product tile (i.e. ribbons, priceboxes, product ratings, badges).

### Our workflow in Sketch

- To change the text or image use the "Overrides"-function.
- Place additional elements like the pricebox element on top of the product tile and resize the height.
