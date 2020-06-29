<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Breadcrumb

Indicate the current page’s location within a navigational hierarchy.

It is positioned near the header and is used primarily as a visual display to the customer, but is still interactive.

---

## Recommendations

- Don't show any breadcrumb on a tablet (portrait) and smartphone device.

---

## Overall styling

- The text-style always is **small**.
- The hover state changes the **mouse cursor into a link cursor (pointer).**
- Always use **house** as home-icon and **arrow-right** as seperator.

| Types | Attributes | Preview |
|---|---|---|
| Default / hover / active | text-color: gray-darker <br> icon-color: gray-darker | ![Breadcrumb complete](assets/complete@1x.png) |

---

## Spacing & Measurements

- If the breadcrumb is larger than the viewport it breaks in a second line.
- Normally, there are not more than 5 levels shown.

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | margin: 4px|  ![Breadcrumb: horizontal-spacing](assets/measurements/vertical-spacing@1x.png) |
| Horizontal spacing | padding: 8px | ![Breadcrumb: vertical-spacing](assets/measurements/horizontal-spacing@1x.png) |
| Size | home: 16x16px <br> seperator: 8x8px | ![Breadcrumb: icon-size](assets/measurements/size/icon@1x.png)<br> ![Breadcrumb: seperator-size](assets/measurements/size/seperator@1x.png)|
| Width | result of the addition of all symbols | ![Breadcrumb: complete](assets/complete@1x.png) |

---

## What can be modified?

- Override the text.
- Adjust the width of a single symbol according to the text.

### Our workflow in Sketch

- The breadcrumb is made up of the individual symbols from the CAKE UI Core and the CAKE UI Kit.
- They add up seamlessly to each other.
- The text can be changed using the "Overrides"-function.
