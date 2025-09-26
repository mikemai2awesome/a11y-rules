![og-image](https://github.com/user-attachments/assets/e766f3f0-1ba9-41f8-b77c-d23d5db8372b)

# A11y Rules

A collection of rules (or instructions) for AI assistants to write better, more accessible HTML and CSS for your web projects. Written by designer coder [Mike Mai](https://mikemai.net).

## Key Principles

- **Accessibility First**: All code should meet WCAG 2.2 standards
- **Semantic HTML**: Use meaningful HTML elements that convey structure and purpose
- **Lightweight CSS**: Modern CSS (e.g. cascade layers, logical properties, prefers-reduced-motion, etc.) and no utility class soup
- **Responsive Design**: Use relative units and fluid layouts
- **Progressive Enhancement**: Build with vanilla JavaScript and focus on core functionality

## Usage

1. Copy the text in the [rules.txt](rules.txt)
2. Paste the text into the rules (or instructions) input within your AI tool of choice (e.g. Cursor, Windsurf, Claude, etc.)
3. Depending on your needs, you could re-organize the rules into user rules and project specific rules
4. You also don't have to agree with every rule, they are my opinions after all. Treat this like a CSS reset, remove what you don't need.

## Example Prompt

Ask the agent to conform to the accessibility rules (or whatever you decide to name your rules) along with your prompt.

```
Build an accordion component by conforming to the accessibility rules.
```

## Tips

- Always consult an accessibility expert to review your code because AI will make mistakes
- Whenever you know of a proven accessible example, add it as a context when prompting
- Save WCAG and ARIA docs as PDFs and attach them as the knowledge for the AI
- Add the [context7](https://github.com/upstash/context7) MCP for more up-to-date docs

## FAQ

### Why focus on OKLCH?
I believe OKLCH gives a wider range of colors but it will also depend on whether your monitor supports it. So this is experimental now, feel free to change to your preferred colors.

### What's wrong with Tailwind CSS, Radix and Shadcn?
If you are vibe coding, you don't need to overcomplicate your project with frameworks. These frameworks might come with accessibility and performance issues that will get in your way.

### Do I have to use every rule?
These rules are intended for users who do not know how to code, let alone accessibility. If you are a seasoned dev, you should just pick the ones you agree with.

### How can I be involved?
Submit issues!

## License

See [LICENSE](LICENSE) for details.
