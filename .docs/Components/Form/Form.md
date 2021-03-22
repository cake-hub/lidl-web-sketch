<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Forms

Forms are used to accept the user's input. They can be displayed in many different ways: input- or select-fields, check boxes or radio buttons.

They are an important element in online shops, so it is even more essential that they are designed to be user-friendly. They serve to get information and guide the user through each task with minimal effort.

---

## Possible use cases

- Login and registration (check-in, check-out)
- Transaction (orders, payment)
- Contact (support, callbacks, requests)
- Data collection (lotteries, newsletters, surveys)
- Contribution (blogs, comments, posts)

---

## Recommendations

- Always try to keep the form and the text as short as possible! <br> A short form helps the user to get a fast overview and he recognizes easy what is required.
- If you use an input field as a single row or with a fixed height, demonstrate an overflow text (clipping) by an ellipse.
- If there is more than one option but only one can be selected, use a radio button instead of a checkbox.
- The open list of options in a select-field is always the native list of the browser.

---

## Overall styling

- Text-style is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- Corners have a **2px** radius.
- Borders have a **1px** thickness.
- Hover or focus states are always shown with a border in **brand-primary-base**.
- Icon size is **24x24px**.
- **Important!** The colors of the icons follow the basic rules for icons.
- The background color is **basic-white**, except for the disabled state displayed in **gray-background**.

---

## Checkbox

- Choose a checkbox if the user must make one or more decisions about a particular element.
- Each checkbox in a group represents a separate and independent choice.
- Checked checkboxes use an embedded element as icon which isn't included in the icon sprite.


| States | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker<br>border: gray-base | ![checkbox: default](assets/checkbox/default@1x.png) |
| Hover / Focus | text-color: brand-primary-base<br> border: brand-primary-base  | ![checkbox: hover-focus](assets/checkbox/hover-focus@1x.png) |
| Disabled | text-color: gray-base<br>border: gray-light | ![checkbox: disabled](assets/checkbox/disabled@1x.png) |
| Error | text-color: danger-base<br>border: danger-base | ![checkbox: error](assets/checkbox/error@1x.png) |
| Checked: Default | text-color: brand-primary-base<br>border: gray-base<br>icon-color: brand-primary-base | ![checkbox: checked-default](assets/checkbox/checked/default@1x.png) |
| Checked: Hover / Focus | text-color: brand-primary-base<br>border: brand-primary-base<br>icon-color: brand-primary-base | ![checkbox: checked-hover-focus](assets/checkbox/checked/hover-focus@1x.png) |
| Checked: Disabled | text-color: gray-base<br>border: gray-light<br>icon-color: gray-light | ![checkbox: checked-disabled](assets/checkbox/checked/disabled@1x.png) |
| Checked: Error | text-color: danger-base<br>border: danger-base<br>icon-color: danger-base | ![checkbox: checked-error](assets/checkbox/checked/error@1x.png)|

---

## Radio button

- Choose a radio button if the user needs to select a single option from multiple options, or if you want the user to carefully consider the options and see all available ones.
- Selected radio buttons use our "bullet.svg" as icon.

| States | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker<br>border: gray-base | ![radiobutton: default](assets/radiobutton/default@1x.png) |
| Hover / Focus | text-color: brand-primary-base<br>border: brand-primary-base | ![radiobutton: hover-focus](assets/radiobutton/hover-focus@1x.png) |
| Disabled | text-color: gray-base<br>border: gray-light | ![radiobutton: disabled](assets/radiobutton/disabled@1x.png) |
| Error | text-color: danger-base<br>border: danger-base | ![radiobutton: error](assets/radiobutton/error@1x.png) |
| Selected: Default | text-color: brand-primary-base<br>border: gray-base<br>icon-color: brand-primary-base | ![radiobutton: selected-default](assets/radiobutton/selected/default@1x.png) |
| Selected: Hover / Focus | text-color: brand-primary-base<br>border: brand-primary-base<br>icon-color: brand-primary-base | ![radiobutton: selected-hover-focus](assets/radiobutton/selected/hover-focus@1x.png) |
| Selected: Disabled | text-color: gray-base<br>border: gray-light<br>icon-color: gray-light | ![radiobutton: selected-disabled](assets/radiobutton/selected/disabled@1x.png) |
| Selected: Error | text-color: danger-base<br>border: danger-base<br>icon-color: danger-base | ![radiobutton: selected-error](assets/radiobutton/selected/error@1x.png)|

---

## Input field

- Use input fields in the various states to show the user that he can enter data.<br>They typically appear in forms and dialogs.

| States | Attributes | Preview |
|---|---|---|
| Placeholder | text-color: gray-base<br>border: gray-base | ![input-field: placeholder](assets/input-field/placeholder@1x.png) |
| Placeholder-Hover | text-color: gray-base<br>border: brand-primary-base | ![input-field: placeholder-hover](assets/input-field/placeholder-hover@1x.png)|
| Focus (text input) | text-color: gray-darker<br>border: brand-primary-base | ![input-field: focus (text input)](assets/input-field/focus@1x.png) |
| Default | text-color: brand-primary-base<br>border: gray-base |![input-field: default](assets/input-field/default@1x.png) |
| Default-Hover | text-color: brand-primary-base<br>border: brand-primary-base|![input-field: default-hover](assets/input-field/default-hover@1x.png) |
| Disabled | text-color: gray-base<br>border: gray-light | ![input-field: disabled](assets/input-field/disabled@1x.png) |
| Error | text-color: danger-base<br>border: danger-base | ![input-field: error](assets/input-field/error@1x.png) |
| Success | text-color: brand-primary-base<br>border: brand-primary-base | ![input-field: success](assets/input-field/success@1x.png) |

---

## Select field

- The select field is part of forms and opens a list of options.
- The consistent appearance of a select field compared to other form elements (input field, checkbox, etc.) is important and also refers to the different states.
- Select fields use our "arrow-down.svg" as icon.

| States | Attributes | Preview |
|---|---|---|
| Default | text-color: brand-primary-base<br>border: gray-base<br>icon-color: gray-darker | ![select-field: default](assets/select-field/default@1x.png) |
| Hover / Focus | text-color: brand-primary-base<br>border: brand-primary-base<br>icon-color: gray-darker | ![select-field: hover-focus](assets/select-field/hover-focus@1x.png) |
| Disabled | text-color: gray-base<br>border: gray-light<br>icon-color: gray-base | ![select-field: disabled](assets/select-field/disabled@1x.png) |
| Error | text-color: danger-base<br>border: danger-base<br>icon-color: gray-darker | ![select-field: error](assets/select-field/error@1x.png) |
| Success | text-color: brand-primary-base<br>border: brand-primary-base<br>icon-color: gray-darker | ![select-field: success](assets/select-field/success@1x.png) |

---

## Labels

- Labels are part of the input- or select field.
- They use **basic-bold** as label- and **basic** as optional-text.
- Give each form element a unique label.
- The **(optional)** part is fixed and is used for labels where user input isn't mandatory.

| States | Attributes | Preview | Combinations |
|---|---|---|---|
| Default | text-color: gray-darker | ![label: default](assets/label/default@1x.png) | ![label: default](assets/label/combinations/default@1x.png) |

---

## Spacing & Measurements

| Type | Attributes | Preview
|---|---|---|
| Horizontal  | 8px margin between radiobutton (or checkbox) and optional text <br> 8px margin between label and optional text <br> 16px padding| ![spacing radiobutton](assets/measurements/radiobutton/spacing@1x.png) <br> ![spacing checkbox](assets/measurements/checkbox/spacing@1x.png)  <br>  ![spacing input field](assets/measurements/input-field/spacing@1x.png) |
| Height | LG: 48px<br>MD-XS: 40px<br>Width depends on device and usage | ![measurements: height](assets/measurements/input-field/height@1x.png) |
| Distance | 8px between form and label<br>32px between form blocks | ![spacing: forms](assets/measurements/input-field/forms@1x.png) |

---

## Our workflow in Sketch

- Use the "Overrides"-function to enter text.
- Fill in "space" to show an empty input-or select field.
- Demonstrate the different states by changing the predefined layer-style.
- If you don't want to show an icon, just select "Default" in the "Overrides"-function from the checkbox layer-styles.
- Pick the label symbol out of the library.
