<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Availability badges

Availability badges are mainly used to show the availability status of articles in both online store and in retail store.
They are usually positioned on product tiles and on the product detail page.<br>
If there is a need to display retail store availability on a map then use [store-locator-pins](https://www.cake.schwarz/Lidl/Web/Design/General/Icon/Icon.html#store-locator-pin).

---

## Versions

- There exist **5** availability badge versions for online and retail store.

Type | In stock | Low stock | Out of stock | No data | Info
---------|----------|---------|---------|---------|---------
 online store | ![in stock](assets/versions/online-deliverable@1x.png) | ![low stock](assets/versions/online-low-stock@1x.png) | ![out of stock](assets/versions/online-out-of-stock@1x.png) | - | ![soon available](assets/versions/online-soon-available@1x.png)
 retail store | ![in stock](assets/versions/retail-available@1x.png) | ![low stock](assets/versions/retail-low-stock@1x.png) | ![out of stock](assets/versions/retail-out-of-stock@1x.png) | ![no data available](assets/versions/no-data-available@1x.png) | ![also in retail](assets/versions/retail-also-in-retail@1x.png) <br> ![from date in retail](assets/versions/retail-dd-mm-retail@1x.png)

---

## Usage rules

- Don't show more than **two badges** on product tile or product detail page.
- The availability badges are displayed side by side on one line.
- The order of the availability badges starts with the retail store badge, followed by the online store badge.
- If the content inside the badges is too big for the space available, the badges are then placed right-aligned one below the other.
- If text inside the badge is too large for the space available within the product tile, it breaks into two lines.

---

## Overall styling

- The text-style is [small](../../General/Typography/Typography.md#small).
- The line-height is set to **120%**.
- The text-color is always **gray-darker**.
- It always has **12px rounded corners** and this includes the case when the badge has two lines of text.

### Online store

Title | In stock | Low stock | Out of stock | Info 
---------|----------|---------|---------|---------
 Preview | ![in stock](assets/versions/online-deliverable@1x.png) | ![low stock](assets/versions/online-low-stock@1x.png) | ![out of stock](assets/versions/online-out-of-stock@1x.png) | ![soon available](assets/versions/online-soon-available@1x.png)
 Attributes | background: success-lighter <br> dot: success-base | background: mark-light <br> dot: mark-darker | background: danger-lighter <br> dot: danger-dark | background: gray-lighter

### Retail store

 Title | In stock | Low stock | Out of stock | No data | Info
---------|----------|---------|---------|---------|---------
Preview | ![in stock](assets/versions/retail-available@1x.png) | ![low stock](assets/versions/retail-low-stock@1x.png) | ![out of stock](assets/versions/retail-out-of-stock@1x.png) | ![no data available](assets/versions/no-data-available@1x.png) | ![also in retail](assets/versions/retail-also-in-retail@1x.png) <br> ![also in retail](assets/versions/retail-dd-mm-retail@1x.png)
 Attributes | background: success-lighter <br> dot: success-base | background: mark-light <br> dot: mark-darker| background: danger-lighter <br> dot: danger-dark | background: gray-lighter <br> dot: gray-base | background: gray-lighter

---

## Spacing & measurements

### Online store

| Types | Attributes | Preview |
|---|---|---|
| LG vertical spacing | icon and text are vertically centered | ![horizontal-spacing](assets/spacings/online-vertical-LG@1x.png) |
| LG horizontal spacing | LG padding: 8px | ![horizontal-spacing](assets/spacings/online-horizontal-LG@1x.png) |
| MD-XS vertical spacing | icon and text are vertically centered | ![vertical-spacing](assets/spacings/online-vertical-MD-XS@1x.png) |
| MD-XS horizontal spacing | MD-XS padding: 8px | ![horizontal-spacing](assets/spacings/online-horizontal-MD-XS@1x.png) |
|dot | size: 12x12px | ![horizontal-spacing](assets/dot-size@1x.png) |

### Retail store

| Type | Attributes | Preview |
|---|---|---|
| LG vertical spacing | icon and text are vertically centered | ![horizontal-spacing](assets/spacings/retail-vertical-LG@1x.png) |
| LG horizontal spacing | LG padding: 8px | ![horizontal-spacing](assets/spacings/retail-horizontal-LG@1x.png) |
| MD-XS vertical spacing | icon and text are vertically centered | ![vertical-spacing](assets/spacings/retail-vertical-MD-XS@1x.png) |
| MD-XS horizontal spacing | MD-XS padding: 8px | ![horizontal-spacing](assets/spacings/retail-horizontal-MD-XS@1x.png) |
| dot | size: 12x12px | ![horizontal-spacing](assets/dot-size@1x.png) |

### Two lines of text

- Icon size and horizontal spacings remain the same as in badges with one line of text, only the vertical spacings change.

| Type | Behavior | Preview |
|---|---|---|
| LG vertical spacing | icon remains in the same place as in the one-line badge and text is vertically centered within the badge shape | ![horizontal-spacing](assets/two-lines-LG@1x.png) |
| MD-XS vertical spacing | icon remains in the same place as in the one-line badge and text is vertically centered within the badge shape | ![vertical-spacing](assets/two-lines-MD-XS@1x.png) |

### Distances between availability badges (LG-XS) and their surroundings

- Horizontally and vertically availability badges have 8px paddings between themselves and 16px distance to all other objects or edges around them.

Type | Preview |
---------|----------|
 distances when badges are next to each other | ![distances-horizontal](assets/distances-horizontal@1x.png)
 distances when badges are below each other | ![distances-vertical](assets/distances-vertical@1x.png)
