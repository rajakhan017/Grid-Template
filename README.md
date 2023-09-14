# Grid-Template
# Assignment

## [Live Website Link!]https://rajakhan017.github.io/Grid-Template/

### Structure of the web page

![image](https://github.com/rajakhan017/Grid-Template/assets/135150598/30d61900-0e49-4789-a34f-db88708ce9b0)


### @import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@500&display=swap');

**Import Explanation:** This line imports the 'Barlow Semi Condensed' font with a weight of 500 from Google Fonts and applies it to the entire stylesheet as the primary font family with a weight of 500.

### \*

| Property      | Value                                 | Description                                                                                                                            |
| ------------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `box-sizing`  | `border-box`                          | Specify the box-sizing model as "border-box," which includes padding and borders in the element's total width and height calculations. |
| `margin`      | `0`                                   | Set the margin for all elements to 0.                                                                                                  |
| `padding`     | `0`                                   | Set the padding for all elements to 0.                                                                                                 |
| `font-family` | `'Barlow Semi Condensed', sans-serif` | Set the default font family for all elements to 'Barlow Semi Condensed' and the fallback to sans-serif.                                |
| `font-weight` | `500`                                 | Set the default font weight for all elements to 500.                                                                                   |

**Selector Explanation:** The `*` selector targets all elements on the page.

### body

| Property           | Value     | Description                                                        |
| ------------------ | --------- | ------------------------------------------------------------------ |
| `display`          | `grid`    | Set the body element to use a grid layout.                         |
| `place-content`    | `center`  | Center the content of the body both horizontally and vertically.   |
| `min-height`       | `100vh`   | Set the minimum height of the body to 100% of the viewport height. |
| `background-color` | `#ecf2f8` | Set the background color of the body to #ecf2f8 (light gray).      |

**Selector Explanation:** The `body` selector targets the `<body>` element.

### .main

| Property              | Value                                                      | Description                                                                                                    |
| --------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `display`             | `grid`                                                     | Set the element with the class "main" to use a grid layout.                                                    |
| `grid-template-areas` | Specifies the placement of grid items in named grid areas. |
| `width`               | `min(95%, 70rem)`                                          | Set the width of elements with the class "main" to a minimum of 95% or a maximum of 70rem (responsive design). |
| `gap`                 | `1.5rem`                                                   | Set the gap between grid items to 1.5rem.                                                                      |
| `grid-auto-columns`   | `1fr`                                                      | Define the default width of grid columns as 1fr (equal width).                                                 |
| `padding-block`       | `2rem`                                                     | Add padding to the top and bottom (2rem) of elements with the class "main."                                    |
| `margin-inline`       | `auto`                                                     | Center-align the element horizontally.                                                                         |

**Selector Explanation:** The `.main` selector targets elements with the class "main."

### .testimonial

| Property        | Value                                 | Description                                                                                            |
| --------------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| `padding`       | `2rem`                                | Add padding to the top, bottom, left, and right (2rem) sides of elements with the class "testimonial." |
| `border-radius` | `0.5rem`                              | Add rounded corners (0.5rem) to elements with the class "testimonial."                                 |
| `box-shadow`    | `2.5rem 3.75rem 3rem -3rem #48556a40` | Apply a box shadow to elements with the class "testimonial."                                           |

**Selector Explanation:** The `.testimonial` selector targets elements with the class "testimonial."

### .t1, .t2, .t3, .t4, .t5

| Property              | Value                                                                    | Description                                                                  |
| --------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| `grid-area`           | Specifies the grid area in which elements with these classes are placed. |
| `background-image`    | `url(...)`                                                               | Set a background image for elements with these classes.                      |
| `background-repeat`   | `no-repeat`                                                              | Prevent the background image from repeating.                                 |
| `background-position` | `top right 10%`                                                          | Set the background image's position to the top right, with an offset of 10%. |
| `background-color`    | Sets the background color of elements with these classes.                |

**Selector Explanation:** The `.t1`, `.t2`, `.t3`, `.t4`, and `.t5` selectors target elements with these specific classes.
![image](https://github.com/rajakhan017/Grid-Template/assets/135150598/a0384df3-dc9a-4f41-9ab2-c8e637687ebf)

### .light, .dark

| Property | Value                                                   | Description |
| -------- | ------------------------------------------------------- | ----------- |
| `color`  | Defines the text color for elements with these classes. |

**Selector Explanation:** The `.light` and `.dark` selectors target elements with the classes "light" and "dark," respectively.

### .desc-heading

| Property     | Value  | Description                                                          |
| ------------ | ------ | -------------------------------------------------------------------- |
| `font-size`  | `20px` | Set the font size of elements with the class "desc-heading" to 20px. |
| `margin-top` | `18px` | Add margin to the top of elements with the class "desc-heading."     |

**Selector Explanation:** The `.desc-heading` selector targets elements with the class "desc-heading."
![image](https://github.com/rajakhan017/Grid-Template/assets/135150598/3f02bdf8-dca5-4517-b03d-0ebf5dc2a6e4)

### .desc

| Property      | Value  | Description                                                                      |
| ------------- | ------ | -------------------------------------------------------------------------------- |
| `opacity`     | `0.7`  | Set the opacity of elements with the class "desc" to 0.7 (slightly transparent). |
| `font-size`   | `13px` | Set the font size of elements with the class "desc" to 13px.                     |
| `line-height` | `1.5`  | Set the line height of elements with the class "desc" to 1.5.                    |
| `margin-top`  | `1em`  | Add margin to the top of elements with the class "desc."                         |

**Selector Explanation:** The `.desc` selector targets elements with the class "desc."

### .name

| Property  | Value  | Description                                                                  |
| --------- | ------ | ---------------------------------------------------------------------------- |
| `display` | `flex` | Set the element to use flexbox layout.                                       |
| `gap`     | `1rem` | Set the gap between child elements within the element with the class "name." |

**Selector Explanation:** The `.name` selector targets elements with the class "name."

### .name img

| Property        | Value  | Description                                                                        |
| --------------- | ------ | ---------------------------------------------------------------------------------- |
| `border-radius` | `50%`  | Add rounded corners (50%) to `img` elements within elements with the class "name." |
| `width`         | `28px` | Set the width of `img` elements within elements with the class "name" to 28px.     |

**Selector Explanation:** The `.name img` selector targets `img` elements that are descendants of elements with the class "name."
![image](https://github.com/rajakhan017/Grid-Template/assets/135150598/6ac177a4-8c8b-46c4-890c-6d6245a4b33d)

### .name h2

| Property    | Value  | Description                                                                       |
| ----------- | ------ | --------------------------------------------------------------------------------- |
| `font-size` | `13px` | Set the font size of `h2` elements within elements with the class "name" to 13px. |

**Selector Explanation:** The `.name h2` selector targets `h2` elements that are descendants of elements with the class "name."

### .name p

| Property    | Value  | Description                                                                                      |
| ----------- | ------ | ------------------------------------------------------------------------------------------------ |
| `font-size` | `11px` | Set the font size of `p` elements within elements with the class "name" to 11px.                 |
| `opacity`   | `0.5`  | Set the opacity of `p` elements within elements with the class "name" to 0.5 (semi-transparent). |

**Selector Explanation:** The `.name p` selector targets `p` elements that are descendants of elements with the class "name."
