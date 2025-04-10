# Antora Documentation Site

This is a documentation site built with [Antora](https://antora.org/), the multi-repository documentation site generator.

## Project Structure

```
antora-docs/
├── antora-playbook.yml      # Main Antora configuration
├── docs/
│   ├── antora.yml          # Component descriptor
│   └── modules/
│       └── ROOT/
│           ├── nav.adoc    # Navigation
│           └── pages/      # Documentation pages
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Build the site:
   ```bash
   npx antora antora-playbook.yml
   ```

3. View the site by opening `build/site/index.html` in your browser.

## Contributing

Feel free to contribute to this documentation by submitting pull requests or creating issues.
