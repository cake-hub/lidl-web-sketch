<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Effects

Effects can be used to highlight individual elements.

Shadows visualize a spatial impression. They mark elements from their environment. They can also be used to display interactivity.

Overlays emphasize the contents above it and further hide not relevant information.

The browser focus shows the element what is currently focused.

---

## Usage

- Mainly the effects are used for picture-text compositions. But it can also be used as a highlight element.

---

## Shadows

### Default

- This shadow should be used for all elements that are displayed with a better recognition in contrast to the website background.

| Attributes | Preview |
|---|---|
| HEX: #000000<br>rgba: 0, 0, 0, 0.15<br>settings: 0px 2px 4px 0px | ![shadow: default](assets/shadow-default@1x.png) |

### Flyout

- This shadow can only be used with superimposed elements.
- They create a spatial effect  which clearly overlay the page, e.g. layers, lightboxes, flyouts.

| Attributes | Preview |
|---|---|
| HEX: #000000<br>rgba: 0, 0, 0, 0.15<br>settings: 0px 3px 3px 0px | ![shadow: flyout](assets/shadow-default-flyout@1x.png) |

---

## Overlays

- This overlay covers the website in the background and highlights important content.
- The overlay **extends across the entire page**.
- The content box placed over the overlay can have a **free ratio**.
- The content box should have rounded corners with **2px radius**.

| Attributes | Preview |
|---|---|
| color: basic-black <br> opacity: 72% | ![overlay](assets/overlay@1x.png) |

---

## Browser focus

- The browser focus shows the element what is currently focused.
- Use the given focus for a consistent experience.

| Attributes | Preview |
|---|---|
| color: brand-primary base <br> opacity: 50% <br> outline (outside): 3px <br> radius: 2px | ![browser focus default](assets/browser-focus-default@1x.png) |
| **Exception!** <br> The error state has the <br> color: danger-base | ![browser focus error](assets/browser-focus-error@1x.png) |
