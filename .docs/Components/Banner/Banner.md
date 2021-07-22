<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Banner

The banner element is mainly used in the upper section of a page.

It should give the user information about the following section through a title, subheadline and image.

---

## Recommendations

- Keep the text short and avoid line breaks.
- If you select a banner with text, look at it’s contrast to the picture (i.e. choose gray for an image with a bright subject and vice versa).

---

## Overall styling

- The title uses the text-style [large bold](../../General/Typography/Typography.md#large-bold).
- The subhead comes in the text-style [small](../../General/Typography/Typography.md#small).
- The line-height is **120%**.
- However, it has **no** hover or focus state.
- The background-color of a bar always has an opacity of **90%**.
- Its appearance and design is similar to the teaser component.

---

## Variants

- Bars can have two different states: **title** and **with-subhead**.
- They also are available in two colors: **light** and **dark**.

### Title

| Types | Attributes | Preview |
|---|---|---|
| light | text-color: gray-darker<br>background-color: basic-white | ![title: light](assets/variants/title/light@1x.png) |
| dark | text-color: basic-white<br>background-color: gray-darker | ![title: dark](assets/variants/title/dark@1x.png) |

### With subhead

| Types | Attributes | Preview |
|---|---|---|
| light | text-color: gray-darker<br>background-color: basic-white | ![with-subhead: light](assets/variants/with-subhead/light@1x.png) |
| dark | text-color: basic-white<br>background-color: gray-darker | ![with-subhead: dark](assets/variants/with-subhead/dark@1x.png) |

---

## Spacing & measurements

#### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px<br>*text is horizontally centered* | ![horizontal spacing](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | margin-bottom: 2px | ![horizontal spacing](assets/measurements/vertical-spacing@1x.png) |

#### Measurements

- The width of the symbol always adapts to the viewport – up to a maximum of 1920px.

| Types | Attributes | Preview |
|---|---|---|
| Height | LG: 200px<br>MD: 184px<br>SM: 184px<br>XS: 184px | ![height: LG](assets/measurements/height/LG@1x.png)<br>![height: MD](assets/measurements/height/MD@1x.png)<br>![height: SM](assets/measurements/height/SM@1x.png)<br>![height: XS](assets/measurements/height/XS@1x.png) |
| Width | LG: 1280px (max. 1920px)<br>MD: 960px<br>SM: 600px<br>XS: 320px | ![width: LG](assets/measurements/width/LG@1x.png)<br>![width: MD](assets/measurements/width/MD@1x.png)<br>![width: SM](assets/measurements/width/SM@1x.png)<br>![width: XS](assets/measurements/width/XS@1x.png) |

---

## What can be modified?

- Override the text and bars.
- Adjust the width.

### Our workflow in Sketch

- Use the "Overrides"-function to change the bar of the banner.
