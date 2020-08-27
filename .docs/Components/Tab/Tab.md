<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Tabs

A component to organize and navigate between related content at the same level of a website.

---

## Usage

- Use Tabs to organize similar content groups on the same page.
- This allows content to be viewed without having to navigate away from that page.
- The tabs are used to show the weekly offers on the start page.

---

## Overall styling

- Text style is **basic**.
- The line-height is **120%**.
- All states use **shadow-default**.

### Desktop & Tablet landscape (LG & MD)

- Dividers come in **gray-light** as color with a **1px thickness**.
- The whole component has **rounded corners with a 2px radius**.
- The width is only scalable by adding up the different symbols (left, center or right).

![tab: LG+MD](assets/types/complete/LG-MD@1x.png)

| Types | Attributes | Preview |
|---|---|---|
| Active | text-color: gray-darker<br>background-color: basic-white | ![tab: active (LG/MD)](assets/states/LG/active@1x.png) |
| Hover / Focus | text-color: basic-white<br>background-color: brand-primary-base  | ![tab: hover-focus (LG/MD)](assets/states/LG/hover-focus@1x.png) |
| Inactive | text-color: gray-darker<br>background-color: gray-lightest | ![tab: inactive (LG/MD)](assets/states/LG/inactive@1x.png) |

#### Elements

- The individual elements come with pre-set round corners.
- In combination, these individual elements are combined to the complete tab component.

| Types | Attributes | Preview |
|---|---|---|
| Left | Rounded corners: 2px (upper-/lower-left)  | ![tab: left (LG/MD)](assets/elements/LG/left@1x.png) |
| Center | Rounded corners: none<br>divider: left  | ![tab: center (LG/MD)](assets/elements/LG/center@1x.png) |
| Right | Rounded corners: 2px (upper-/lower-right)<br>divider: left | ![tab: right (LG/MD)](assets/elements/LG/right@1x.png) |

### Tablet portrait & Smartphone (SM & XS)

- There is **no inactive state**.
- The states can be switched via the slider-buttons.
- Styling of the slider-buttons can be found [here](../Slider%20button/Slider%20button.md).

![tab: SM+XS](assets/types/complete/SM-XS@1x.png)

|Types | Attributes | Preview |
|---|---|---|
| Active | text-color: gray-darker<br>background-color: basic-white | ![tab: active (SM/XS)](assets/states/XS/active@1x.png) |
| Hover / Focus | text-color: gray-darker<br>background-color: basic-white | ![tab: hover-focus (LG/MD)](assets/states/XS/hover-focus@1x.png) |

---

## Spacing & Measurements

### Desktop & Tablet landscape (LG & MD)

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px | ![LG/MD: horizontal spacing](assets/measurements/LG/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 16px | ![LG/MD: horizontal spacing](assets/measurements/LG/vertical-spacing@1x.png) |


### Tablet portrait & Smartphone (SM & XS)

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 8px | ![SM/XS: horizontal spacing](assets/measurements/XS/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 16px | ![LG/MD: horizontal spacing](assets/measurements/XS/vertical-spacing@1x.png) |

---

## What can be modified?

- Override the text.
- Override the arrows.
- Adjust the width of a single symbol according to the text.
- Modify tabs to your project needs by adding or deleting single tab symbols.

### Our workflow in Sketch

- Change the states of text, states and arrows using the "Overrides"-function.
