# SpendWise Dashboard Shell

This project is a static, responsive dashboard shell for SpendWise.

## Files

- `index.html` contains the dashboard structure and realistic financial content.
- `style.css` contains the page styling, layout, theme variables, responsiveness, and micro-interactions.

## Layout

- The overall page uses CSS Grid: a sidebar column and a flexible main-content column.
- The sidebar, header, budget summary, navigation items, and category cards use Flexbox to arrange their content.
- The category section uses a responsive CSS Grid with three columns on larger screens and one column below 768px.
- The stylesheet uses CSS custom properties on `:root` for brand, accent, surface, background, and text colors.

## Interactions and Accessibility

Each category card is keyboard focusable. It has a 250ms or shorter transform and box-shadow transition for hover and keyboard focus states.

The navigation links and action buttons include visible keyboard focus styles. The sidebar and layout adapt for small screens, and the page also provides a dark theme through `@media (prefers-color-scheme: dark)`.
