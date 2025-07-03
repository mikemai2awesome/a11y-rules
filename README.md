# A11y Rules

A collection of rules (or instructions) for AI assistants to write better, more accessible HTML and CSS for your web projects. Written by designer coder [Mike Mai](https://mikemai.net).

## Key Principles

- **Accessibility First**: All code should meet WCAG 2.2 standards
- **Semantic HTML**: Use meaningful HTML elements that convey structure and purpose
- **Lightweight CSS**: Modern CSS (e.g. cascade layers, logical properties, prefers-reduced-motion, etc.) and no utility class soup
- **Responsive Design**: Use relative units and flexible layouts
- **Progressive Enhancement**: Build with vanilla JavaScript and focus on core functionality

## Usage

1. Copy the text in the `rules.txt`
2. Paste the text into the rules (or instructions) input within your AI tool of choice (e.g. Cursor, Windsurf, Claude, etc.)
3. Depending on your needs, you could re-organize the rules into user rules and project specific rules

## Tips

- Even with these specific rules, AI can still make mistakes. Always consult an accessibility expert to review your code.
- Whenever you know of a proven accessible example, try to add it as a context when prompting.
- Save WCAG and ARIA docs as PDFs and attach them as the knowledge for the AI.
- Add the [context7](https://github.com/upstash/context7) MCP for more up-to-date docs

## License

See [LICENSE](LICENSE) for details.
