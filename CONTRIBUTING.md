# Contribution Guide

## Workflow

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

## Development

```bash
git clone https://github.com/<your-username>/expressgen.git
cd expressgen
npm install
npm link  # Makes command available globally
```

## Testing

```bash
# Create test project
expressgen test-project
cd test-project && node index.js
```

## Style Guide

- Bash: Follow [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html)
- Markdown: Use semantic line breaks
- Commits: Conventional commits format
