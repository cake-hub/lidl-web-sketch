<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Teaser

Use the teaser component to attract attention and build excitement and expectations through curiosity.

It consists of an image and a text to underline the visual meaning.

---

## Recommendations

- **Always use the text in a single line scenario.**
- If you select a teaser with text, look at it’s contrast to the picture – i.e. choose gray for an image with a bright subject and vice versa.
- Try to keep the 4:3 ratio for teasers to guarantee the right display in each breakpoint.
- Otherwise it’s ratio is completely free adjustable.

---

## Overall styling

- The components has **rounded corners of 2px**.
- It uses the **shadow-default**.

| Types | Gray | White |
|---|---|---|
| title | ![title: gray](assets/types/gray/title@1x.png) | ![title: white](assets/types/white/title@1x.png) |
| With subhead | ![with-subhead: gray](assets/types/gray/with-subhead@1x.png)  | ![with-subhead: white](assets/types/white/with-subhead@1x.png) |


### States

- The change of state is mainly shown in the bar and overlay of the image.
- The title gets **underlined** and the image gets an **overlay of basic-white with 50% opacity**.

| States | Gray | White |
|---|---|---|
| Default | ![default: gray](assets/states/gray/default@1x.png) | ![default: white](assets/states/white/default@1x.png) |
| Hover / focus | ![hover/focus: gray](assets/states/gray/hover-focus@1x.png)  | ![hover/focus: white](assets/states/white/hover-focus@1x.png) |

### Bars

- The title uses the text-style **large-bold**.
- The subhead comes in the text-style **small**.
- The background-color always has an **opacity of 90%**.

| Types | Attributes | Preview |
|---|---|---|
| Gray | text-color: basic-white<br>background: gray-darker  | ![bar gray](assets/bars/gray@1x.png) |
| White |  text-color: gray-darker<br>background: basic-white | ![bar white](assets/bars/white@1x.png) |

---

## Spacing & Measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px | ![Horizontal spacing](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 16px<br>distance: 2px | ![Vertical spacing](assets/measurements/vertical-spacing@1x.png) |
| Spacing | margin-bottom: 16px | ![Spacing](assets/measurements/distance@1x.png) |
| Size | default size of 4:3 | ![Spacing](assets/measurements/size@1x.png) |


---

## What can be modified?

- Override the text and bars.
- Adjust the ratio to any size but please try to stick to a 4:3-ratio.

### Our workflow in Sketch

- Use the "Overrides" function to customize the teaser in the three possible variants (for example, select "None" for the bar element to display just an image teaser).
