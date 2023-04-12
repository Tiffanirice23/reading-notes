## CSS Layout

### Learn CSS - Flexbox

#### Flexbox is designed for one-dimensional content. Explain what this means.
> Flexbox is a layout model in CSS that is designed to help with the arrangement and alignment of items within a container. It is primarily used for one-dimensional layout, meaning it focuses on either the horizontal or vertical axis of the container.
One dimensional simply means that the items being laid out are arranged along a single axis

#### Explain the difference between the main axis and cross axis.
> the main axis and cross axis refer to the two primary axes used for layout. The main axis is the primary axis along which flex items are arranged, while the cross axis is the secondary axis perpendicular to the main axis. The direction of the main axis is determined by the `flex-direction` property, while the cross axis.

#### How can using certain properties of flexbox negatively impact accessibility?
1. Lack of proper ordering: When using the `order` property in flexbox, it's important to ensure that the visual order of elements on the page still matches the logical order of the content.

2. Insufficient spacing: When using the `justify-content` and `align-items` properties to position elements on the page, it's important to ensure that there is sufficient spacing between elements to avoid cluttered and confusing layouts.

3. Inaccessible flexbox navigation: Developers may use flexbox to create navigation menus, but if they're not coded correctly, they can be inaccessible to keyboard-only users

#### What are some advantages of using flexbox over float?

> Flexbox offers several advantages over float when it comes to creating modern, responsive layouts. Its one-dimensional layout, better alignment control, flexible sizing, and easier item reordering.


*Source*
- [Learn CSS- Flexbox](https://web.dev/learn/css/flexbox/)
- [CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Learn CSS- Layout](https://web.dev/learn/css/layout/)

## Things I want to know more about
