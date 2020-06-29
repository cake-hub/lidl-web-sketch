<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Colors

Colors help to emphasize and highlight your brand's appearance.

---

## Color concept

- Our color concept is a result of our accessibility problems.
- In developing this concept, we focused on **simplicity**, **clarity**, **adaptation** and **portability to the frontend**.

### Create a scale

- The scale has a total of **8 levels**, using the lowest level always as a background color.
- It’s principally based on a **base** color as a reference.
- The basic color becomes either lighter (light, lighter, lightest) or darker (dark, darker, darkest) in the standard 3 steps.
- The **lightest** and **darkest** levels can be disregarded in relation to brand or theme colors, as well as additional colors, thanks to their low contrast with already existing colors (i.e. background or black).
- The **dark** and **darkest** levels of gray can also be disregarded due to no usage in our design system.

| Name | Values | e.g. Gray | Accessibility (on gray-background) |
|---|---|---|
| background | base<br>+96% white | ![gray-background](assets/gray/background@1x.png) | - |
| lightest | base<br>+92% white | ![gray-lightest](assets/gray/lightest@1x.png) | ![accessibility-gray-lightest](assets/gray/accessibility/lightest@1x.png) |
| lighter | base<br>+84% white | ![gray-lighter](assets/gray/lighter@1x.png) | ![accessibility-gray-lighter](assets/gray/accessibility/lighter@1x.png) |
| light | base<br>+68% white | ![gray-light](assets/gray/light@1x.png) | ![accessibility-gray-light](assets/gray/accessibility/light@1x.png) |
| base | - | ![gray-base](assets/gray/base@1x.png) | ![accessibility-gray-base](assets/gray/accessibility/base@1x.png) |
| dark | base<br>+16% black | ![gray-dark](assets/gray/dark@1x.png) | ![accessibility-gray-dark](assets/gray/accessibility/dark@1x.png) |
| darker | base<br>+32% black | ![gray-darker](assets/gray/darker@1x.png) | ![accessibility-gray-darker](assets/gray/accessibility/darker@1x.png)|
| darkest | base<br>+64% black | ![gray-darkest](assets/gray/darkest@1x.png) |  ![accessibility-gray-darkest](assets/gray/accessibility/darkest@1x.png) |

---

## Brand Colors

- The Lidl brand colors communicate the personality of the brand.
- Lidl blue, red and yellow - the contrasting primary colors symbolize **responsibility**, **dynamism** and **vitality**.
- In combination, they appear versatile and unexpected.

### Brand-primary (Lidl blue)

- It seems interactive.
- The base color is used for icons & links, to symbolize activeness, to show possible selection or highlights or different conditions.
- The brand-primary color can be changed according to the desired project color (example: wine).

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #0050AA<br>RGB: 0 / 80 / 170 | - | ![brand-primary-base](assets/brand-primary/base@1x.png) |
| background | HEX: #F5F8FC<br>RGB: 245 / 248 / 252 | base<br>+96% white | ![brand-primary-background](assets/brand-primary/background@1x.png) |
| lighter | HEX: #D6E3F1<br>RGB: 214 / 227 / 241 | base<br>+84% white | ![brand-primary-lighter](assets/brand-primary/lighter@1x.png) |
| light | HEX: #ADC7E4<br>RGB: 173 / 199 / 228 | base<br>+68% white | ![brand-primary-light](assets/brand-primary/light@1x.png) |
| dark | HEX: #00438F<br>RGB: 0 / 67 / 143 | base<br>+16% black | ![brand-primary-dark](assets/brand-primary/dark@1x.png) |
| darker | HEX: #003673<br>RGB: 0 / 54 / 115 | base<br>+32% black | ![brand-primary-darker](assets/brand-primary/darker@1x.png) |

### Danger (Lidl red)

- It stands for danger and shows an error or a malfunction.
- In the digital environment, red is only used to a reduced extent as an additional color.
- The base color should also work as a indicator for pricing.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #E60A14<br>RGB: 230 / 10 / 20 | - | ![danger-base](assets/danger/base@1x.png) |
| background | HEX: #FEF5F6<br>RGB: 254 / 245 / 246 | base<br>+96% white | ![danger-background](assets/danger/background@1x.png) |
| lighter | HEX: #FBD8D9<br>RGB: 251 / 216 / 217 | base<br>+84% white | ![danger-lighter](assets/danger/lighter@1x.png) |
| light | HEX: #F7B0B3<br>RGB: 247 / 176 / 179 | base<br>+68% white | ![danger-light](assets/danger/light@1x.png) |
| dark | HEX: #C10811<br>RGB: 193 / 8 / 17 | base<br>+16% black | ![danger-dark](assets/danger/dark@1x.png) |
| darker | HEX: #9C080E<br>RGB: 156 / 8 / 14 | base<br>+32% black | ![danger-darker](assets/danger/darker@1x.png) |

### Mark (Lidl yellow)

- It isn't used very often.
- It offers a low contrast ratio to a light background in the digital department.
- It's mostly used in pricing.
- To match the definition of the Lidl colors, yellow must be overlaid with Lidl red for the darker colors.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #FFF000<br>RGB: 255 / 240 / 0 | - | ![mark-base](assets/mark/base@1x.png) |
| background | HEX: #FFFEF5<br>RGB: 255 / 254 / 245 | base<br>+96% white | ![mark-background](assets/mark/background@1x.png) |
| lighter | HEX: #FFFDD6<br>RGB: 253 / 253 / 214 | base<br>+84% white | ![mark-lighter](assets/mark/lighter@1x.png) |
| light | HEX: #FFFAAD<br>RGB: 255 / 250 / 173 | base<br>+68% white | ![mark-light](assets/mark/light@1x.png) |
| dark | HEX: #FBCB03<br>RGB: 251 / 203 / 3 | base<br>+16% Lidl red | ![mark-dark](assets/mark/dark@1x.png) |
| darker | HEX: #F7A606<br>RGB: 247 / 166 / 6 | base<br>+32% Lidl red | ![mark-darker](assets/mark/darker@1x.png) |

---

## Additional colors

- These colors are associated with certain meanings and are used for different states/type of messages, sales elements & action notes (badges, ribbons, offers, …) and priceboxes.

### Info

- The info color corresponds to the blue of our brand-primary.
- You will find info in **alerts**, **badges**, **ribbons** or **pricebox highlight labels**.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #0050AA<br>RGB: 0 / 80 / 170 | - | ![info-base](assets/info/base@1x.png) |
| background | HEX: #F5F8FC<br>RGB: 245 / 248 / 252 | base<br>+96% white | ![info-background](assets/info/background@1x.png) |
| lighter | HEX: #D6E3F1<br>RGB: 214 / 227 / 241 | base<br>+84% white | ![info-lighter](assets/info/lighter@1x.png) |
| light | HEX: #ADC7E4<br>RGB: 173 / 199 / 228 | base<br>+68% white | ![info-light](assets/info/light@1x.png) |
| dark | HEX: #00438F<br>RGB: 0 / 67 / 143 | base<br>+16% black | ![info-dark](assets/info/dark@1x.png) |
| darker | HEX: #003673<br>RGB: 0 / 54 / 115 | base<br>+32% black | ![info-darker](assets/info/darker@1x.png) |

### Success

- In our case this color scheme indicates success.

| Name | Values | Concept | Color |
|---|---|---|
| base | HEX: #348553<br>RGB: 52 / 133 / 83 | - | ![success-base](assets/success/base@1x.png) |
| background | HEX: #F7FAF8<br>RGB: 247 / 250 / 248 | base<br>+96% white | ![success-background](assets/success/background@1x.png) |
| lighter | HEX: #DEEBE3<br>RGB: 222 / 235 / 227 | base<br>+84% white | ![success-lighter](assets/success/lighter@1x.png) |
| light | HEX: #BED8C8<br>RGB: 190 / 216 / 200 | base<br>+68% white | ![success-light](assets/success/light@1x.png) |
| dark | HEX: #2C7046<br>RGB: 44 / 112 / 70 | base<br>+16% black | ![success-dark](assets/success/dark@1x.png) |
| darker | HEX: #235A38<br>RGB:35 / 90 / 56 | base<br>+32% black | ![success-darker](assets/success/darker@1x.png) |

### Warning

- This color scheme has the meaning of activity, change and impact.
- In particular, it should generate attention.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #BE591D<br>RGB: 190 / 89 / 29 | - | ![warning-base](assets/warning/base@1x.png) |
| background | HEX: #FCF8F6<br>RGB: 252 / 248 / 246 | base<br>+96% white | ![warning-background](assets/warning/background@1x.png) |
| lighter | HEX: #F5E4DB<br>RGB: 245 / 228 / 219 | base<br>+84% white | ![warning-lighter](assets/warning/lighter@1x.png) |
| light | HEX: #EACAB6<br>RGB: 234 / 202 / 182 | base<br>+68% white | ![warning-light](assets/warning/light@1x.png) |
| dark | HEX: #9F4B18<br>RGB: 159 / 75 / 24 | base<br>+16% black | ![warning-dark](assets/warning/dark@1x.png) |
| darker | HEX: #813C14<br>RGB: 129 / 60 / 20 | base<br>+32% black | ![warning-darker](assets/warning/darker@1x.png) |

---

## Grayscale

- It is used to display the status and character of messages.
- Especially the grayscale stands for different states.
- The lightest shade of gray (background) is mainly reserved for the website background.
- Our basic font-color always gray-darker.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #4E5761<br>RGB: 78 / 87 / 97 | - | ![gray-base](assets/gray/base@1x.png) |
| background | HEX: #FAFAFA<br>RGB: 250 / 250 / 250 | base<br>+96% white | ![gray-background](assets/gray/background@1x.png) |
| lightest | HEX: #F1F2F3<br>RGB: 241 / 242 / 243 | base<br>+92% white | ![gray-lightest](assets/gray/lightest@1x.png) |
| lighter | HEX: #E3E4E5<br>RGB: 227 / 228 / 229 | base<br>+84% white | ![gray-lighter](assets/gray/lighter@1x.png) |
| light | HEX: #C6C9CC<br>RGB: 198 / 201 / 204 | base<br>+68% white | ![gray-light](assets/gray/light@1x.png) |
| darker | HEX: #353B42<br>RGB: 53 / 59 / 66 | base<br>+32% black | ![gray-darker](assets/gray/darker@1x.png) |

---

## Theme Colors

- The brand-primary color can be changed according to the desired project color.

### Wine

- The wine theme e.g. uses burgundy instead of blue as it's brand-primary color.
- Use this shades of red if you are designing or layouting a Lidl wine theme.

| Name | Values | Concept | Color |
|---|---|---|---|
| base | HEX: #B0082B<br>RGB: 176 / 8 / 43 | - | ![wine-base](assets/wine/base@1x.png) |
| background | HEX: #FCF5F7<br>RGB: 252 / 245 / 247 | base<br>+96% white | ![wine-background](assets/wine/background@1x.png) |
| lighter | HEX: #F2D7DD<br>RGB: 242 / 215 / 221 | base<br>+84% white | ![wine-lighter](assets/wine/lighter@1x.png) |
| light | HEX: #E6B0BB<br>RGB: 230 / 176 / 187 | base<br>+68% white | ![wine-light](assets/wine/light@1x.png) |
| dark | HEX: #940724<br>RGB: 148 / 7 / 36 | base<br>+16% black | ![wine-dark](assets/wine/dark@1x.png) |
| darker | HEX: #77051A<br>RGB: 119 / 5 / 29 | base<br>+32% black | ![wine-darker](assets/wine/darker@1x.png) |

---

## Basic

- Colors for highest contrast.

| Name | Values | Color |
|---|---|---|
| white | HEX: #FFFFFF<br>RGB: 255 / 255 / 255 | ![basic-white](assets/basic/white@1x.png) |
| black | HEX: #000000<br>RGB: 0 / 0 / 0 | ![basic-black](assets/basic/black@1x.png) |

---

## Gradients

- Gradients in the primary colors Lidl blue, red and yellow strengthen the brand personality and create value.
- By aligning light to dark, they also emphasize dynamism and modernity.
- They underline the optical character of a basic color and create a pleasant haptic feeling and a spatial impression.
- Gradients should only be used for background areas.

| Values | Brand-primary | Danger | Mark | Info | Success | Warning | Gray | Wine |
|---|---|---|
| **0%**<br>**base**<br>e.g. danger-base<br><br>**60%**<br>**base**<br>e.g. danger-base<br><br>**100%**<br>**darker**<br>e.g. danger-darker | ![gradient-brand-primary](assets/gradient/brand-primary@1x.png) | ![gradient-danger](assets/gradient/danger@1x.png) | ![gradient-mark](assets/gradient/mark@1x.png) | ![gradient-info](assets/gradient/info@1x.png) | ![gradient-success](assets/gradient/success@1x.png) | ![gradient-warning](assets/gradient/warning@1x.png) | ![gradient-gray](assets/gradient/gray@1x.png) | ![gradient-wine](assets/gradient/wine@1x.png) |

---

### Workflow in Sketch

- A color is the smallest ingredient in the library. It is integrated as a symbol in many other ingredients, doughs and pieces.
- If you want to change the color or turn it off, look into its symbols „Overrides“-function.
