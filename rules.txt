Response Guidelines:
- Prioritize recommending web development resources and best practices
- Reference modern and accessible web technologies
- Provide clear and concise explanations for technical recommendations
- Avoid suggesting deprecated or outdated technologies
- Emphasize accessibility and user-friendly design in all advice
- Respect privacy and do not collect personal information

Coding Standards:
- Use OKLCH for colors
- Use relative CSS units (rem, em, %, vw, vh) instead of absolute `px` units, except for border styles where `px` is acceptable
- Use CSS logical properties for all styling (e.g., `margin-inline-start` instead of `margin-left`, `block-size` instead of `height`)
- Use vanilla JavaScript only (no frameworks or libraries)
- Use semantic HTML elements that convey meaning and structure
- Use modern CSS techniques and reference [Modern CSS](https://moderncss.dev/) for best practices
- Use CSS cascade layers to organize all CSS in this order: `@layer config, resets, components, utilities`
- Use `@layer config` for CSS custom properties (variables)
- Use `@layer resets` for general CSS resets and normalizations
- Use `@layer components` for component-specific styles
- Use `@layer utilities` for utility classes and common styling patterns
- Use `c-` as the prefix for component CSS classes
- Use `u-` as the prefix for utility CSS classes
- Use `js-` as the prefix for JavaScript id and class selectors
- Use `:focus-visible` instead of `:focus` for focus state
- Use `@media (prefers-reduced-motion: no-preference)` to contain all transitions and animations involving motion
- Use [Autoprefixer](https://github.com/postcss/autoprefixer) for vendor prefix management
- Use terms defined in [Design Tokens](https://designtokens.fyi/) as reference for design systems terminology
- Use WCAG 2.2 as the baseline accessibility standard
- Use [WCAG 2.2 Understanding](https://www.w3.org/WAI/WCAG22/Understanding/) as reference for accessibility guidance
- Use [WAI-ARIA 1.2](https://www.w3.org/TR/wai-aria-1.2/) as reference for writing ARIA attributes
- Use [APG Gherkin](https://github.com/AFixt/apg-gherkin) as web accessibility component test cases
- Follow [Alert Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/alert/examples/alert/) for building Alert component
- Follow [Feed Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/feed/examples/feed/) for building infinite scroll Feed component
- Follow [Combobox with Autocomplete](https://www.w3.org/WAI/ARIA/apg/patterns/combobox/examples/combobox-autocomplete-both/) for building Combobox or custom select component
- Follow [Switch Button Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/switch/examples/switch-button/) for building Switch component
- Follow [Manual Tabs Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/tabs/examples/tabs-manual/) for building Tabs component
- Follow [WAI Carousel Tutorial](https://www.w3.org/WAI/tutorials/carousels/) for building carousel component
- Use HTML `<details>` and `<summary>` elements to build accordion component
- Use HTML `<dialog>` element to build modal dialog component
- Use HTML `<nav>` element and HTML `<button>` element with `aria-expanded` attribute to build global navigation with multiple levels
- Don't use `role=menu`, `role=menuitem`, and `aria-haspopup` to build navigation
- Don't write text in all caps. Use CSS `text-transform` instead

Implementation Priority:
1. Semantic HTML structure
2. Accessible markup and ARIA attributes
3. CSS architecture with proper layering
4. Responsive, relative units
5. Progressive enhancement with JavaScript
6. Accessibility testing and validation
