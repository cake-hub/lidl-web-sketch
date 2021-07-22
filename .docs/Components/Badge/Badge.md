<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>


# Badges

Use it for a number of functions, but mostly to demonstrate status and progress to the customer.

Basically it is positioned in a context with a text.

---

## Versions

- There are different versions of the badge: **standard** and **addon**.

| Standard | Addon |
|---|---|
| Use it in conjunction with text. | Use it in the user-navigation of the header. |

---

## Recommendations

- If you decide to use a badge, never use more than a maximum of 2 variations.
- Keep the text in a badge as short as possible.

---

## Overall styling

- The text-style or font-size depends on the component but is always [basic bold](../../General/Typography/Typography.md#basic-bold).
- The line-height is **120%**.
- The text-color always is **basic-white**.
- The border is in **basic-white** with a **1px thickness**.
- It always has rounded corners of **50% of its height**.

---

## Standard

- This badge is called **standard** and should be used in conjunction with text.
- It comes in **3 different sizes** depending of the corresponding text-styles.
- Please use the badge corresponding to the breakpoint since there are different sizes.
- The badge has 4 colored variations: **primary**, **highlight**, **gray** and **info**.

| Types | Attributes | Preview |
|---|---|---|
| Primary | text-style: small, basic, large<br>background-color: brand-primary-base | ![primary: LG](assets/standard/LG/primary@1x.png) |
| Highlight | text-style: small, basic, large<br>background-color: danger-base | ![highlight: LG](assets/standard/LG/highlight@1x.png)|
| Gray | text-style: small, basic, large<br>background-color: gray-base | ![gray: LG](assets/standard/LG/gray@1x.png) |
| Info | text-style: small, basic, large<br>background-color: info-base | ![info: LG](assets/standard/LG/info@1x.png)|


### States

- A badge can also be given as a link.
- The only thing that changes is the background-color.

| Types | Attributes | Preview |
|---|---|---|
| Default | brand-primary-base<br>danger-base<br>gray-base<br>info-base | ![state: default](assets/variants/standard/states/default@1x.png) |
| Hover / focus and active | brand-primary-darker<br>danger-darker<br>gray-darker<br>info-darker | ![state: hover](assets/variants/standard/states/hover@1x.png) |

---

## Addon

- This badge is called **addon** and is only used in the user-navigation section of the header.
- It comes in 3 different sizes depending on the breakpoints.

| Breakpoints | Attributes | Preview |
|---|---|---|
| LG | font-size: 12px<br>line-height: 100%<br>background-color: brand-primary-base  | ![pill: LG](assets/variants/pill/LG@1x.png) |
| MD-XS | font-size: 10px<br>line-height: 100%<br>background-color: brand-primary-base | ![pill: MD-XS](assets/variants/pill/MD-XS@1x.png) |

---

## Usage

- Stick to the following examples to implement a **badge-standard** in combination with a text.

### Headlines

| Text style | Attributes | Preview |
|---|---|---|
| Headline 1 | text-style: headline 1<br>badge: large | ![example: headline 1](assets/examples/headline-1@1x.png) |
| Headline 2 | text-style: headline 2<br>badge: basic | ![example: headline 3](assets/examples/headline-2@1x.png) |
| Headline 3 | text-style: headline 3<br>badge: basic | ![example: headline 3](assets/examples/headline-3@1x.png) |
| Headline 4 | text-style: headline 4<br>badge: basic | ![example: headline 4](assets/examples/headline-4@1x.png) |
| Headline 5 | text-style: headline 5<br>badge: small | ![example: headline 5](assets/examples/headline-5@1x.png) |

### Text

| Text style | Attributes | Preview |
|---|---|---|
| Small | text-style: small(-bold)<br>badge: small | ![example: headline 1](assets/examples/small@1x.png) |
| Basic | text-style: basic(-bold)<br>badge: basic | ![example: headline 1](assets/examples/basic@1x.png) |
| Large | text-style: large(-bold)<br>badge: large | ![example: headline 1](assets/examples/large@1x.png) |


---

## Spacing & measurements

### Standard

| Types | Attributes | Preview |
|---|---|---|
| LG horizontal spacing | LG padding: 16px | ![horizontal-spacing](assets/measurements/standard/lg-horizontal-spacing@1x.png) |
| MD-XS horizontal spacing | MD-XS padding: 16px | ![horizontal-spacing](assets/measurements/standard/md-xs-horizontal-spacing-16@1x.png) |
| Vertical spacing for all badges on all breakpoints (LG-XS) | LG-XS padding: 4px | ![vertical-spacing](assets/measurements/standard/vertical-spacing@1x.png) |
| Distances | margin: 8px | ![distance](assets/measurements/standard/distance@1x.png) |

### Addon

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 4px | ![horizontal-spacing](assets/measurements/pill/horizontal-spacing@1x.png) |
| Size | LG: 20px<br>MD-XS: 16px | ![vertical-spacing](assets/measurements/pill/size@1x.png) |
| Position | Overlaps an icon by 50% to the right<br>Text expands the element to the left  | ![position](assets/measurements/pill/position@1x.png) |

---

## What can be modified?

- Override the text.
- Adjust the width according to the text.
- Modify badges to your project needs by changing colors of background, outline and text.
