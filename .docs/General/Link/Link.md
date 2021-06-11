<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Links

A reference for the user that can lead directly to an external or internal destination by clicking or tapping on it.

---

## Overall styling

- The text-style depends on the body text and is either [small,](../../General/Typography/Typography.md#small) [basic](../../General/Typography/Typography.md#basic) or [large](../../General/Typography/Typography.md#large).
- The line-height is set to **default**.
- A link can have multiple states: **default/visited**, **hover/focus**, **active/pressed**.
- The appearance of the state depends on the usage or context.
- There’s also a positive and negative version to layout on a light or dark background.
- The icon can only be placed **before**, **not after** the link.
- Icons are always displayed like in the font color.

---

## Positive version

- Use the positive version if you want to display a link on a light background.
- Always make sure you have enough contrast when choosing the background.

| State | Attributes | Preview |
|---|---|---|
| Default / visited | text-color: brand-primary-base<br>text-decoration: underline | ![positive: default/visited](assets/positive/default-visited@1x.png) |
| Hover / focus | text-color: brand-primary-darker<br>text-decoration: underline | ![positive: hover/focus](assets/positive/hover-focus@1x.png) |
| Active / pressed | text-color: brand-primary-darker | ![positive: active/pressed](assets/positive/active-pressed@1x.png) |

---

## Negative version

- Use the negative version if you want to display a link on a dark background.
- Always make sure you have enough contrast when choosing the background.

| State | Attributes | Preview |
|---|---|---|
| Default / visited | text-color: basic-white<br>text-decoration: underline | ![negative: hover/focus](assets/negative/default-visited@1x.png) |
| Hover / focus | text-color: gray-light<br>text-decoration: underline | ![negative: hover/focus](assets/negative/hover-focus@1x.png) |
| Active / pressed | text-color: gray-light | ![negative: active/pressed](assets/negative/active-pressed@1x.png) |

---

## Text styles

### Small

| Breakpoint | Font size | Preview |
|---|---|---|
| LG | 14px | ![positive: small](assets/small/LG/default-visited@1x.png) |
| MD-XS | 12px | ![positive: small](assets/small/MD-XS/default-visited@1x.png) |

### Basic

| Breakpoint | Font size | Preview |
|---|---|---|
| LG | 18px | ![positive: basic](assets/basic/LG/default-visited@1x.png) |
| MD-XS | 16px | ![positive: basic](assets/basic/MD-XS/default-visited@1x.png) |

### Large

| Breakpoint | Font size | Preview |
|---|---|---|
| LG | 22px | ![positive: large](assets/large/LG/default-visited@1x.png) |
| MD-XS | 20px | ![positive: large](assets/large/MD-XS/default-visited@1x.png) |

---

## Spacing & measurements

| Type | Attributes | Preview |
|---|---|---|
| Vertical spacing | 8px between icon and label | ![spacing: small](assets/measurements/spacing/small@1x.png)<br>![spacing: basic](assets/measurements/spacing/basic@1x.png)<br>![spacing: large](assets/measurements/spacing/large@1x.png) |
| Icon size | small: 16x16px<br>basic: 24x24px<br>large: 32x32px | ![icon: small](assets/measurements/icon/small@1x.png)<br>![icon: basic](assets/measurements/icon/basic@1x.png)<br>![icon: large](assets/measurements/icon/large@1x.png)  |

---

### Our workflow in Sketch

- Take one of the text styles for the different font sizes to display a linked text.
- The text style is then manually adapted to the status to be displayed (e.g. hover/focus: underlined, brand-primary-darker,…).
- Detach the text-style if you want to show a link in a copy-text.
