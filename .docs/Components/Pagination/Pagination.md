<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Pagination

Pagination is used to spread content or data over multiple pages.

It allows the user to jump to the respective pages by browsing.

---

## Recommendations

- Use the provided pagination as the simplest and smallest solution.
- The complete pagination can be placed either left, centered or right on a web page.
- It can also be placed above or below the page content.

---

## Overall styling

- The text-style always is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- The background is **basic-white with a shadow-default**.
- The whole element has **rounded corners with a 2px radius**.
- Use „arrow-left“ and „arrow-right“ as icons.
- **Only arrows can be disabled!**
- The width depends on the number of shown digits or arrows.
- It is only scalable by adding up the digits or arrows.

![pagination overview](assets/overall@1x.png)

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker <br> icon-color: gray-darker <br> background-color: basic-white | ![default arrow](assets/status/arrow/default@1x.png)![default digit](assets/status/digit/default@1x.png) |
| Hover / focus / active | text-color: basic-white <br> icon-color: basic-white <br> background-color: brand-primary-base | ![hover-focus-active arrow](assets/status/arrow/active-hover-focus@1x.png)![hover-focus-active digit](assets/status/digit/active-hover-focus@1x.png) |
| Disabled | icon-color: gray-light <br> background-color: basic-white | ![disabled arrow](assets/status/arrow/disabled@1x.png) |

---

## Spacing & measurements

### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Digits | padding: 8px | ![digit: LG](assets/measurements/LG/digit/horizontal-spacing@1x.png) ![digit: MD-XS](assets/measurements/MD-XS/digit/horizontal-spacing@1x.png) |
| Arrows | padding: 16px (LG)<br> padding: 12px (MD-XS) | ![arrow: LG](assets/measurements/LG/arrow/horizontal-spacing@1x.png) ![arrow: MD-XS](assets/measurements/MD-XS/arrow/horizontal-spacing@1x.png) |

### Measurements

| Types | Attributes | Preview |
|---|---|---|
| Height | LG: 48px <br> MD-XS: 40px | ![height: LG](assets/measurements/LG/height@1x.png)<br> ![height: MD-XS](assets/measurements/MD-XS/height@1x.png) |
| Width | LG: 48px <br> MD-XS: 40px | ![width: LG](assets/measurements/LG/width@1x.png)<br> ![width: MD-XS](assets/measurements/MD-XS/width@1x.png) |
| Size | icon: 16x16px| ![icon-size](assets/measurements/icon-size@1x.png) |

---

## Usage

- This section shows the usage of active arrows depending on the page shown to the user/customer.

| Types | Attributes | Preview |
|---|---|---|
| Right | more than one page <br>first index is shown | ![pagination right arrow](assets/usage/right-active@1x.png) |
| Both | more than one page <br> middle index is shown | ![pagination both arrow](assets/usage/both-active@1x.png) |
| Left | more than one page <br> last index is shown | ![pagination left arrow](assets/usage/left-active@1x.png)|

---

## Variants

- You can create more or less digits.
- Just detach the symbol to define your own element.

![pagination overview of variants](assets/variants/overview@1x.png)

---

## What can be modified?

- Override the digits.
- Modify paginations for your project needs by adding or deleting single pagination symbols (i.e. like more digits or more arrows).

### Our workflow in Sketch

- Change the states of indexing and arrows using the "Overrides"-function.
