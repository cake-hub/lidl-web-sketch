<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>


# Header

The header is one of the essential components to create brand awareness.

The appearance symbolizes customers that they are on a LIDL page now. Its strongest supporting element is the LIDL logo with the brand claim.

---

## Recommendations

- Keep the globally known LIDL Logo in the header.
- Only change the brand claim regarding to your country.

---

## Elements

- The structure of the header is **modular**.
- It is a group of symbols and typography from the Core and UI Kit.
- If you combine the individual elements in Sketch, you get the header in various forms and for each breakpoint.
- There is a separate header layout for tablets (portrait) and smartphones:
  - A burger icon opens a dropdown menu with the main- and sub-navigation.
  - In combination with the back-function, our structure allows you to display an endless number of sub-navigation items.
- The header contains the **logo**, **typography: main-, sub-, brand-** and **user-navigation**, as well as **colors** and **shadows**.
- The header comes with a background-color in **basic-white**.
- It uses the **shadow-default**.

### Desktop & tablet landscape (LG & MD)

![Complete: LG+MD](assets/complete/LG+MD@1x.png)

| Brand-navigation | User-navigation | Main-navigation | Sub-navigation |
|---|---|---|---|
| 1. Brand<br>2. Brand-navigation<br>3. Language<br>11. Divider | 4. Logo<br>5. Brand-Claim<br>6. User-navigation| 7. Main-navigation<br>8. Slider button<br>11. Divider | 9. Sub-navigation<br>10. Slider button |

### Tablet portrait & smartphone (SM & XS)

![Complete SM+XS](assets/complete/SM+XS@1x.png)

| Header | Flyout | Others |
|---|---|---|
| 1. Logo<br>2. User-navigation<br>3. Burger-menu | 4. Back-function<br>5. Main-navigation<br>6. Sub-navigation<br>7. Language<br>8. Brand-navigation<br>9. Badge<br>12. Dividers | 10. Overlay<br>11. Flyout |

---

## Main- & sub-navigation

- There are different types of use for each section of the navigation.
- Use the main-navigation for services that LIDL has to offer in your country (e.g. branch or special offers, online shop, travel, recipes …).
- Use the sub-navigation if a service has subitems (e.g. online shop with subcategories such as bicycle, fashion, household & kitchen …).

### Desktop & tablet landscape (LG & MD)

- The text-style for main-navigation is [large](../../General/Typography/Typography.md#large).
- The text-style for sub-navigation is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- The background-color is **basic-white**.
- The indicator is displayed in a different color for each state.
- The length of the indicator is based on the entered text.
- Its position is at the bottom of the element.

| Types | Attributes | Preview (LG & MD) |
|---|---|---|
| Default | text-color: gray-darker<br>indicator: none| ![main-nav LG/MD default](assets/main+sub/LG+MD/default@1x.png) |
| Hover / focus | text-color: gray-base<br>indicator: gray-base | ![main: LG/MD hover/focus](assets/main+sub/LG+MD/hover-focus@1x.png) |
| Active | text-color: brand-primary-base<br>indicator: brand-primary-base | ![main: LG/MD active](assets/main+sub/LG+MD/active@1x.png) |

### Tablet portrait & smartphone (SM & XS)

- The text-style for main-navigation is [large](../../General/Typography/Typography.md#large).
- The text-style for sub-navigation is [basic](../../General/Typography/Typography.md#basic), except the active state which is analog to the main-navigation.
- The line-height is set to **default**.
- The background-color is **basic-white**.
- The active main- & sub-navigation use a **small linked [badge-standard](../Badge/Badge.md#standard)** in brand-primary.
- The divider is displayed in a different color for each state.
- The length of the divider is the full width of the component.
- Its position is at the bottom of the element.
- The icon always is our "arrow-right".

| Types | Attributes | Preview (SM & XS) |
|---|---|---|
| Default | text-color: gray-darker<br>icon-color: gray-darker<br>divider: gray-lighter | ![main: SM/XS default](assets/main+sub/SM+XS/default@1x.png)|
| Hover / focus | text-color: gray-base<br>icon: gray-base<br>divider: gray-base | ![main-nav SM/XS default](assets/main+sub/SM+XS/hover-focus@1x.png) |
| Active | text-color: brand-primary-base<br>divider: brand-primary-base | ![main: SM/XS default](assets/main+sub/SM+XS/active@1x.png)  |

---

## User-navigation

- This area is for user guidance with support of icons.
- The most important elements for the user should be placed here (e.g. shopping cart or wishlist, leaflets, newsletter registration …).
- Keep the title of the user-navigation as short as possible.
- The title can be used in a two-line scenario, but should never be exceeded.
- The width of the component can be extended for the individual projects requirements.
- The icon is always centered above the text.
- The header has to be adjusted if the text for the title gets longer than specified as in our default component.
- Please ensure that the distance between the elements (icon and text) always stays the same.
- It uses the [badge-addon](../Badge/Badge.md#addon) to display a counter (e.g. how many products are in the shopping cart or wishlist).

### Desktop & tablet landscape (LG & MD)

- The text-style is [small](../../General/Typography/Typography.md#small).
- The line-height has **120%**.
- The background-color always is **basic-white**.

| Types | Attributes | Preview (LG & MD) |
|---|---|---|
| Default / active| text-color: gray-darker<br>icon-color: gray-darker | ![user: LG default](assets/user/LG+MD/default-active@1x.png) |
| Hover / focus | text-color: brand-primary-base<br>icon-color: brand-primary-base | ![user: LG hover/focus](assets/user/LG+MD/hover@1x.png) |

### Tablet portrait & smartphone (SM & XS)

- It only uses an icon to symbolize a user-navigation category.
- The background-color is always **basic-white**.

| Types | Attributes | Preview (SM & XS) |
|---|---|---|
| Default / active| icon-color: gray-darker | ![user: SM+XS default](assets/user/SM+XS/default-active@1x.png) |
| Hover / focus | icon-color: brand-primary-base | ![user: SM+XS hover/focus](assets/user/SM+XS/hover@1x.png) |

---

## Burger-menu

- The text-style always is [small bold](../../General/Typography/Typography.md#small-bold) and **uppercase**.
- The line-height is set to **default**.
- The background-color is always **basic-white**.
- Use this element only for tablets (portrait) and smartphones to demonstrate the main- and sub-navigation.
- In contrast to the user-navigation, a text is shown – limited to 5 letters.
- It uses our "bars-horizontal" icon to display a burger menu.
- The burger changes to our "cross" icon as a close function.

| Types | Attributes | Preview (SM & XS) |
|---|---|---|
| Default | text-color: gray-darker<br>icon-color: gray-darker | ![burger: default](assets/burger/SM+XS/default@1x.png) |
| Hover / focus | text-color: brand-primary-base<br>icon-color: brand-primary-base | ![burger: hover/focus](assets/burger/SM+XS/hover-focus@1x.png) |
| Active | text-color: gray-darker<br>icon-color: gray-darker | ![burger menu active](assets/burger/SM+XS/active@1x.png) |

---

## Brand-navigation

- The text-style is [small](../../General/Typography/Typography.md#small).
- The line-height is set to **default**.
- Some LIDL countries have special pages to present their company (e.g. FAQ, responsibility, career …).

| Types | Attributes | Preview (LG / MD-XS) |
|---|---|---|
| Default | text-color: gray-darker<br> background-color: basic-white |![brand: default](assets/brand/default@1x.png)|
| Hover / focus | text-color: gray-darker<br>background-color: gray-lighter<br>*the text gets underlined* |![brand: hover/focus](assets/brand/hover-focus@1x.png)|

---

## Language

- The text-style is [small](../../General/Typography/Typography.md#small) and **uppercase**.
- The line-height is set to **default**.
- The active state comes with a round indicator in **brand-primary-base** and **1px outline in basic-white**.
- Required by countries that have to offer variants of the LIDL website in different national languages (e.g. Switzerland or Belgium).

| Types | Attributes | Preview (LG / MD-XS) |
|---|---|---|
| Default | text-color: gray-darker <br> background-color: basic-white |![language: default](assets/language/default@1x.png)|
| Hover / focus | text-color: gray-darker<br>background-color: gray-lighter<br>*the text gets underlined* |![language: hover-focus](assets/language/hover-focus@1x.png)|
| Active / selected | text-color: gray-darker<br> background-color: basic-white |![language: active](assets/language/active@1x.png) |

---

## Back-function

- The text-style is [small bold](../../General/Typography/Typography.md#small-bold) and **uppercase**.
- The line-height is set to **default**.
- The recommended icon is **arrow-left**.
- There is **no** hover/focus or selected state.
- Use this element only for tablets (portrait) and smartphones.
- The user can go back to the previous navigation level by clicking on the link.

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker<br>background-color: gray-lightest<br>icon-color: gray-darker | ![back-function](assets/back-function/default@1x.png) |
| Example | Example of „back-function" on the symbol „dropdown-menu“ | ![back-function: example](assets/back-function/example@1x.png) |

---

## Brand

| Types | Attributes | Preview (LG & MD) |
|---|---|---|
| Default | text-style: [small](../../General/Typography/Typography.md#small)
<br>text-color: gray-darker | ![brand-claim](assets/brand/LG+MD/default@1x.png) |

---

## Brand-claim

- This element only exists in desktop and tablet (landscape).

| Types | Attributes | Preview (LG & MD) |
|---|---|---|
| Default | text-style: [brand claim](../../General/Typography/Typography.md#brand-claim)<br>text-color: brand-primary-base<br>position: horizontally centered with logo | ![brand-claim](assets/brand-claim/LG+MD/default@1x.png) |

---

## Divider, overlay & flyout

- Dividers are used in every breakpoint and therefore have different widths.
- The overlay and flyout component only exists in tablet (portrait) and smartphone devices.

| Types | Attributes | Preview |
|---|---|---|
| Divider | color: gray-lighter<br>height: 1px | ![divider](assets/divider/default@1x.png) |
| Overlay | background-color: basic-black<br>opacity: 72% | ![overlay](assets/overlay/default@1x.png) |
| Flyout | background-color: basic-white<br>shadow: default-flyout | ![flyout](assets/flyout/default@1x.png) |

---

## Spacing & measurements

- This section shows the different spacings of the desktop and mobile elements included in the header.


### Desktop & tablet landscape (LG & MD)

- All the spacing for these breakpoints are identical.
- Only the **height** and **width** of the used components are different.

#### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Content | padding-left: 8px | ![content: LG+MD](assets/measurements/LG+MD/content@1x.png) |
| Brand-claim | padding-left: 24px | ![brand-claim: LG+MD](assets/measurements/LG+MD/brand-claim@1x.png) |
| Brand-navigation | padding: 16px (8+8)<br>margin-right: 48px (8+24+16) | ![brand: LG+MD](assets/measurements/LG+MD/brand-navigation@1x.png) |
| User-navigation | padding: 32px (16+16) | ![user: LG+MD](assets/measurements/LG+MD/user-navigation@1x.png) |
| Main-navigation | padding: 32px (16+16) | ![main: LG+MD](assets/measurements/LG+MD/main-navigation@1x.png) |
| Sub-navigation | padding: 16px (8+8) | ![sub: LG+MD](assets/measurements/LG+MD/sub-navigation@1x.png) |

#### Measurements

| Types | Attributes (LG / MD) | Preview |
|---|---|---|
| Height | complete: 208px / 176px<br>brand-navigation: 32px / 24px<br>user-navigation: 88px / 80px<br>main-navigation: 48px / 40px<br>sub-navigation: 40px / 32px<br>| ![height: LG](assets/measurements/LG/height@1x.png)<br>![height: LG](assets/measurements/MD/height@1x.png) |
| Width | complete: 1280px / 960px | ![width: LG](assets/measurements/LG/width@1x.png)<br>![width: LG](assets/measurements/MD/width@1x.png) |
| Logo | size: 72x72px / 64x64px | ![height: LG](assets/measurements/LG/logo@1x.png)![height: LG](assets/measurements/MD/logo@1x.png) |
| Main-navigation | padding: 16px<br>height: 48px / 40px<br>indicator: 3px | ![main-nav: LG](assets/measurements/LG/main-nav@1x.png)![main-nav: MD](assets/measurements/MD/main-nav@1x.png) |
| Sub-navigation | padding: 16px<br>height: 48px / 40px<br>indicator: 2px | ![sub-nav: LG](assets/measurements/LG/sub-nav@1x.png) ![sub-nav: LG](assets/measurements/MD/sub-nav@1x.png)|
| User-navigation | padding: 16px<br>margin-bottom: 2px<br>height: 88px / 80px<br>width: 64px / 56px<br>icon-size: 32x32px / 24x24px | ![user-nav: LG](assets/measurements/LG/user-nav@1x.png) ![user-nav: MD](assets/measurements/MD/user-nav@1x.png) |
| Brand-navigation | padding: 8px<br>height: 32px / 24px  | ![brand-nav: LG](assets/measurements/LG/brand-nav@1x.png)![brand-nav: MD](assets/measurements/MD/brand-nav@1x.png)|
| Language | padding: 16px<br>height: 32px / 24px | ![language: LG](assets/measurements/LG/language@1x.png)![language: MD](assets/measurements/MD/language@1x.png) |

### Tablet portrait & smartphone (SM & XS)

#### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Content | padding: 8px | ![content: SM+XS](assets/measurements/SM+XS/content@1x.png) |
| User-navigation | padding: 16px (8+8) | ![user: SM+XS](assets/measurements/SM+XS/user-navigation@1x.png) |
| Brand-navigation | padding: 8px | ![brand: SM+XS](assets/measurements/SM+XS/brand-navigation@1x.png)

#### Measurements

| Types | Attributes | Preview |
|---|---|---|
| Height | complete: 56px<br>back-function: 40px<br>main-navigation: 48px<br>sub-navigation: 48px<br>language: 24px<br>brand-navigation: depends on content<br> | ![height: SM+XS](assets/measurements/SM+XS/height@1x.png) |
| Width | width: 600px / 320px<br>flyout: 80% / 100% | ![width: SM](assets/measurements/SM/width@1x.png)![width: XS](assets/measurements/XS/width@1x.png) |
| Logo | size: 40x40px  | ![height: SM+XS](assets/measurements/SM+XS/logo@1x.png) |
| Back-function | width: depends on breakpoint<br>icon-size: 16x16px<br>padding: 8px<br>height: 48px (includes arrow)<br>arrow-size: 16x8px| ![back-function: SM+XS](assets/measurements/SM+XS/back-function@1x.png) |
| Main-navigation | width: depends on breakpoint<br>padding: 16px<br>height: 48px<br>divider: 1px | ![main-nav: SM+XS](assets/measurements/SM+XS/main-nav@1x.png) |
| Sub-navigation | width: depends on breakpoint<br>padding: 16px<br>height: 48px<br>divider: 1px | ![sub-nav: SM+XS](assets/measurements/SM+XS/sub-nav@1x.png) |
| User-navigation | padding: 8px<br>height: 56px<br>width: 40px<br>icon-size: 24x24px | ![user-nav SM+XS](assets/measurements/SM+XS/user-nav@1x.png) |
| Brand-navigation | padding: 8px <br>height: 24px |![brand-nav: SM+XS](assets/measurements/SM+XS/brand-nav@1x.png)|
| Burger-menu | padding: 8px<br>margin-bottom: 0px<br>height: 56px<br>width: 40px | ![burger menu measurement](assets/measurements/SM+XS/burger-menu@1x.png)|
| Language | padding: 16px<br>height: 24px | ![language: SM+XS](assets/measurements/SM+XS/language@1x.png) |

---

## Position

| Types | Attributes | Preview |
|---|---|---|
| Addon | padding-right: 8px (LG+MD)<br>padding-right: 0px (SM+XS) | ![addon: LG](assets/position/LG/addon@1x.png)![addon: MD](assets/position/MD/addon@1x.png)![addon: SM-XS](assets/position/SM+XS/addon@1x.png) |
| Language selection | padding-right: 10px (LG)<br>padding-right: 10px (MD-XS)<br>padding-top: 8px (LG)<br>padding-top: 6px (MD-XS) | ![language: LG](assets/position/LG/language-selected@1x.png)![language: LG](assets/position/MD-XS/language-selected@1x.png) |

---

## What can be modified?

- Override the text and icons.
- Adjust the width of single symbols according to the text.
- Adjust the height if you delete navigation sections (i.e. main- or sub-navigation).
- Modify headers for your project needs by deleting single symbols or special sections (i.e. language or user-navigation section).

### Our workflow in Sketch

- To individualize the header in your product you need to detach/unlink the complete symbol from the LIDL CAKE UI Web kit.
