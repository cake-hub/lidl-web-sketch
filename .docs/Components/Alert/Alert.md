<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Alerts

Different types of notifications with contextual feedback about user actions as well as permanent presentation of important information.

---

## General information

**Our "info" alert matches our brand-primary color**. Blue is the best color to demonstrate an "info" alert from UX point of view, in our case and in online studies. Part of the LIDL brand colors is "blue" and also the "brand-primary-color" on a digital device. It didn't make sense to create a new color "blue" for an "info" purpose. That's why the "brand-primary-color" for LIDL matches the "info" color. But if, for example, the "brand-primary-color" for LIDL will change, only the components using the "brand-primary-color" will change. This has the benefit that all info elements will stay "blue".

---

## Recommendations

- **Keep the alerts text as short as possible. Especially the title.**
- Use an alert, i.e for feedback, product recalls or support.
- Use links in the alert with caution. It might be more appropriate to link the entire alert instead of one word.

---

## Overall styling

- The text style is [large bold](../../General/Typography/Typography.md#large-bold) for the **title** and [basic](../../General/Typography/Typography.md#basic) for the **text**.
- The line-height for the "alert title" is **120%**, it stays **140%** for the "alert text".
- Every variant uses the **darker-color** as **text-** and **icon-color**.
- The outline comes in **base-color**.
- The alert background always is the main-color's **background-color**.
- The border has a **thickness of 1px**.
- The components has **rounded corners of 2px**.
- It uses the **shadow-default**.
- All widths are individually adjustable and fit into the layout columns and the 8-point-grid.
- The height depends on the content and the additional components shown.
- Every alert comes with the icon "cross" as "close" -icon in the right upper corner.
- The color of the icon "cross" stays the same in the focus/hover state. Only the cursor changes to pointer.

### Title & icon

- Some alerts come with an additional fixed icon to emphasize their meaning.

| Version | Attributes | Preview |
|---|---|---|
| primary | text- & icon-color: brand-primary-darker<br>outline-color: brand-primary-base<br>background-color: brand-primary-background<br>fixed icon: information-circle.svg | ![info](assets/with-title/info@1x.png) |
| info | text- & icon-color: info-darker<br>outline-color: info-base<br>background-color: info-background<br>fixed icon: information-circle.svg | ![info](assets/with-title/info@1x.png) |
| danger | text- & icon-color: danger-darker<br>outline-color: danger-base<br>background-color: danger-background<br>fixed icon: exclamation-triangle.svg | ![danger](assets/with-title/danger@1x.png) |
| success | text- & icon-color: success-darker<br>outline-color: success-base<br>background-color: success-background<br>fixed icon: hook-circle.svg | ![success](assets/with-title/success@1x.png) |
| warning | text- & icon-color: warning-darker<br>outline-color: warning-base<br>background-color: warning-background<br>fixed icon: exclamation-circle.svg | ![warning](assets/with-title/warning@1x.png) |
| gray / neutral | text- & icon-color: gray-darker<br>outline-color: gray-base<br>background-color: gray-background<br>icon: not fix (currently placeholder.svg) | ![gray-neutral](assets/with-title/gray-neutral@1x.png) |

### Text

- Simple alerts to only display text.

| Version | Attributes | Preview |
|---|---|---|
| primary | text- & icon-color: brand-primary-darker<br>outline-color: brand-primary-base<br>background-color: brand-primary-background | ![info](assets/text/info@1x.png) |
| info | text- & icon-color: info-darker<br>outline-color: info-base<br>background-color: info-background | ![info](assets/text/info@1x.png) |
| danger | text- & icon-color: danger-darker<br>outline-color: danger-base<br>background-color: danger-background | ![danger](assets/text/danger@1x.png) |
| success | text- & icon-color: success-darker<br>outline-color: success-base<br>background-color: success-background | ![success](assets/text/success@1x.png) |
| warning | text- & icon-color: warning-darker<br>outline-color: warning-base<br>background-color: warning-background | ![warning](assets/text/warning@1x.png) |
| gray / neutral | text- & icon-color: gray-darker<br>outline-color: gray-base<br>background-color: gray-background | ![gray-neutral](assets/text/gray-neutral@1x.png) |

---

## Link

Some alerts use links to direct the user to another page.

- Every variant uses the **darker-color** as **text-color**.
- In the default/hover/focus state the **text-decoration** is **underline**.

| State | Attributes | Preview |
|---|---|---|
| Default / visited |  | ![alert link default](assets/link/default-hover-info@1x.png) |
| Hover / focus | cursor: changes to pointer  | ![alert link hover](assets/link/default-hover-info@1x.png) |
| Active / pressed | text-decoration: none | ![alert link active](assets/link/active-pressed-info@1x.png) |

---

## Spacing & Measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px | ![Horizontal spacing](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 16px<br>margin-bottom: 8px | ![Vertical spacing](assets/measurements/vertical-spacing@1x.png) |
| Icon size | meaning: 32x32px<br>close: 16x16px | ![Icon size](assets/measurements/icon-size@1x.png) |

---

## Specials

- Alerts can also be used in their brand-primary color besides or with just a different meaning to the „info“-alert (i.e. „brand-primary“ or „wine“)

---

## What can be modified?

- Override the text and icons.
- Adjust the width and height according to the content.
- Modify alerts to your project needs by adding other symbols or styles (i.e. like dividers or links).

### Our workflow in Sketch

- Use the „Overrides“-function to select the required variant, to edit the content, to change the icon if necessary or if the alert can’t be closed.
