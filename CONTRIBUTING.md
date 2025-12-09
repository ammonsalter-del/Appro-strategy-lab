# Contributing to Appropriation Strategy Lab

Thank you for your interest in contributing to the Appropriation Strategy Lab! This educational game aims to help students understand how firms capture value from their innovations.

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue with:
- A clear description of the problem
- Steps to reproduce the issue
- Expected vs actual behaviour
- Browser and device information

### Suggesting New Scenarios

We welcome suggestions for new scenarios! Good scenarios should:
- Represent a realistic product, service, or innovation
- Have a clear "best" protection strategy that can be justified
- Cover concepts from Teece's appropriability framework
- Be distinct from existing scenarios

Please open an issue with:
- The product/service description
- Key characteristics (imitability, visibility, complementary assets needed)
- Suggested protection options with reasoning
- Educational value / concepts illustrated

### Suggesting Improvements

For feature requests or improvements, please open an issue describing:
- The proposed change
- Why it would improve the educational experience
- Any implementation ideas you have

### Code Contributions

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Test thoroughly in multiple browsers
5. Commit with clear messages
6. Push to your fork
7. Open a Pull Request

## Code Style

- Use consistent indentation (2 spaces)
- Comment complex logic
- Keep the single-file HTML structure for easy distribution
- Ensure changes work offline
- Test on mobile devices

## Scenario Format

If adding scenarios, follow this structure:

```javascript
{
  id: [unique number],
  title: "Product/Service Name",
  what: "Brief description of the innovation",
  description: "Detailed context including market, competitors, and constraints",
  imitability: "How easy is it to copy?",
  visibility: "What can competitors observe?",
  complementaryAssets: "What else is needed to profit?",
  options: [
    {
      label: "Strategy Name",
      description: "What this strategy involves",
      isOptimal: true/false,
      protection: [1-10],
      cost: [1-10],
      payoff: [calculated value],
      feedback: "Explanation of why this works or doesn't",
      concepts: ["Concept1", "Concept2"]
    },
    // ... more options
  ]
}
```

## License

By contributing, you agree that your contributions will be licensed under the same CC BY-NC-SA 4.0 license that covers the project.

## Questions?

Feel free to open an issue for any questions about contributing.

Thank you for helping improve innovation education! 🧪
