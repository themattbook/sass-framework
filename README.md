# Sass Framework

Sass Framework is a lightweight CSS framework that provides a set of utility classes to streamline your web development process. It is designed to be easy to use and customizable, allowing you to quickly build responsive and well-designed web applications. Below is a list of the classes provided by Sass Framework along with their use cases.

## Typography
This framework uses the fonts Outfit and Questrial from Google Fonts. You can change both the `@import` tag and the font families in the `_fonts.scss` partial.

### Font Sizes
- `.text-base`: Base font size.
- `.text-sm`: Small font size.
- `.text-lg`: Large font size.
- `.text-xl`: Extra-large font size.
- `.text-2xl` to `.text-7xl`: Additional extra-large font sizes.

### Headings
- `h1` to `h5`: Headings with increasing font sizes.
- `h1`: Largest heading.
- `h2`: Second-largest heading.
- `h3` to `h5`: Subsequent headings.

### Font Weight
- `.text-base`, `h1` to `h5`: Default font weight.
- `h1`, `h2`, `h3`, `h4`, `h5`: Bold headings.

## General Styling

### Margin
- `.m-1` to `.m-15`: Margin of various sizes.
- `.mt-1` to `.mt-15`: Margin-top of various sizes.
- `.mr-1` to `.mr-15`: Margin-right of various sizes.
- `.mb-1` to `.mb-15`: Margin-bottom of various sizes.
- `.ml-1` to `.ml-15`: Margin-left of various sizes.
- `.mx-1` to `.mx-15`: Horizontal margin of various sizes.
- `.my-1` to `.my-15`: Vertical margin of various sizes.

### Padding
- `.p-1` to `.p-15`: Padding of various sizes.
- `.pt-1` to `.pt-15`: Padding-top of various sizes.
- `.pr-1` to `.pr-15`: Padding-right of various sizes.
- `.pb-1` to `.pb-15`: Padding-bottom of various sizes.
- `.pl-1` to `.pl-15`: Padding-left of various sizes.
- `.px-1` to `.px-15`: Horizontal padding of various sizes.
- `.py-1` to `.py-15`: Vertical padding of various sizes.

## Responsive Design

### Media Queries
- `@media(max-width: 650px)`: Adjust font sizes for small screens.
- `@media(max-width: 576px)`: Further adjust font sizes for extra small screens.

## Grid System

### Container
- `.container`: Container with a maximum width of 1200px and centered.

### Row
- `.row`: Flex container for a horizontal row layout.
- `.row-col`: Flex container for a vertical column layout.

### Column Classes
- `.col-1-xs` to `.col-12-xs`: Responsive column classes for extra small screens.
- `.col-1-sm` to `.col-12-sm`: Responsive column classes for small screens.
- `.col-1-md` to `.col-12-md`: Responsive column classes for medium screens.
- `.col-1-lg` to `.col-12-lg`: Responsive column classes for large screens.
- `.col-1-xl` to `.col-12-xl`: Responsive column classes for extra-large screens.
- `.col-1-xxl` to `.col-12-xxl`: Responsive column classes for extra-extra-large screens.

## Layout

### Heights
- `.height-screen`: Full viewport height.
- `.height-full`: Full height within the parent container.

## Spacing and Gaps

### Gap Classes
- `.gap-0` to `.gap-3`: Adjust padding for various gap sizes.

## Flexbox Alignment

### Justify Content
- `.justify-flex-start`: Justify content at the start.
- `.justify-flex-end`: Justify content at the end.
- `.justify-center`: Center justify content.
- `.justify-space-between`: Justify content with space between items.
- `.justify-space-around`: Justify content with space around items.
- `.justify-space-evenly`: Justify content with space evenly between items.

### Align Content
- `.align-content-flex-start`: Align content at the start.
- `.align-content-flex-end`: Align content at the end.
- `.align-content-center`: Center align content.
- `.align-content-space-between`: Align content with space between items.
- `.align-content-space-around`: Align content with space around items.
- `.align-content-space-evenly`: Align content with space evenly between items.

### Align Items
- `.align-items-flex-start`: Align items at the start.
- `.align-items-flex-end`: Align items at the end.
- `.align-items-center`: Center align items.
- `.align-items-space-between`: Align items with space between.
- `.align-items-space-around`: Align items with space around.
- `.align-items-space-evenly`: Align items with space evenly between.

Feel free to customize and combine these classes to suit the needs of your project!