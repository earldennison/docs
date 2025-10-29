# Egregore Documentation

This directory contains the Mintlify documentation for Egregore v0.3.5a3.

## Structure

- **Total Pages**: 163 markdown files
- **Sections**: 10 main sections
- **API Reference**: 54 pages
- **Examples**: 24 pages
- **Guides**: 16 pages
- **Features**: 32 pages
- **Core Concepts**: 8 pages
- **Architecture**: 11 pages
- **Contributing**: 7 pages
- **Reference**: 5 pages
- **Migration**: 2 pages

## Setup

### Local Development

1. Install Mintlify CLI:
```bash
npm i -g mintlify
```

2. Preview documentation:
```bash
mintlify dev
```

3. The docs will be available at `http://localhost:3000`

### Building

```bash
mintlify build
```

## Configuration

- **mint.json**: Main configuration file with navigation structure
- **Logo**: `/logo/dark.svg` and `/logo/light.svg`
- **Favicon**: `/favicon.svg`
- **Colors**: Teal theme (#0D9488)

## Content Status

All pages are currently placeholders marked with `[Content coming soon]`.

### Next Steps

1. **Phase 1 (Critical)**: Fill in Getting Started pages
   - introduction.md
   - quickstart.md

2. **Phase 2 (Critical)**: Complete Core Concepts
   - All 8 core concept pages

3. **Phase 3 (High)**: Feature Documentation
   - Scaffolds, Hooks, Workflows, Tools

4. **Phase 4 (High)**: API Reference
   - Agent, Context, and other core APIs

5. **Phase 5 (Medium)**: Examples
   - Basic examples first, then advanced

6. **Phase 6 (Medium)**: Guides
   - Getting started → Basic → Advanced

7. **Phase 7 (Low)**: Architecture & Contributing
   - Deep dives for contributors

## Migration from docs_base

Original documentation is in `/docs_base` for reference during content migration.

## Content Guidelines

- Use clear, concise language
- Include code examples
- Cross-reference related pages
- Keep consistent terminology (see reference/glossary.md)
- Test all code examples before publishing

## Links

- **GitHub**: https://github.com/yourusername/egregore (update in mint.json)
- **Implementation Audit**: `/internal/reports/implementation-audit.md`
- **Migration Plan**: `/internal/reports/updated-mintlify-plan.md`
- **Structure Details**: `/internal/reports/docs-structure.md`

## Need help?

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
