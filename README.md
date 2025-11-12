# Untyped Documentation

User-friendly documentation for Untyped - Your AI Email Assistant.

## About

This repository contains the complete documentation for Untyped, built with [Mintlify](https://mintlify.com).

Visit the live documentation at [docs.getuntyped.ai](https://docs.getuntyped.ai)

## Local Development

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Setup

Install the Mintlify CLI:

```bash
npm i -g mint
```

### Run Locally

Navigate to the docs directory and start the development server:

```bash
mint dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the docs.

## Documentation Structure

```
/
├── index.mdx                 # Homepage
├── quickstart.mdx            # Quick start guide
├── connecting-email.mdx      # Email connection guide
├── features/                 # Feature documentation
│   ├── drafting.mdx         # AI Email Drafting (primary feature)
│   ├── agent.mdx            # AI Agent Dashboard
│   ├── labels.mdx           # Email Categorization
│   ├── prompt-editor.mdx    # Prompt Customization
│   ├── rules.mdx            # Rules Engine
│   └── knowledge.mdx        # Knowledge Base
├── settings/                 # Settings documentation
│   ├── profile.mdx          # Profile & Preferences
│   ├── mailboxes.mdx        # Mailbox Management
│   └── billing.mdx          # Billing & Plans
└── data-privacy/            # Privacy & Security
    ├── your-data.mdx        # Data Handling
    ├── security.mdx         # Security Measures
    └── export.mdx           # Data Export

```

## Configuration

All documentation configuration is in `docs.json`:

- **Branding**: Colors, logo, favicon
- **Navigation**: Page structure and organization
- **Integrations**: Social links, navbar, footer

## Contributing

When adding or updating documentation:

1. Follow the established tone: friendly, clear, non-technical
2. Use Mintlify components appropriately (Cards, Steps, Tabs, etc.)
3. Focus on user value, not implementation details
4. Test locally before committing
5. Keep content up-to-date with app features

## Deployment

Documentation is automatically deployed via Mintlify when changes are pushed to the main branch.

Monitor deployment status in the [Mintlify Dashboard](https://dashboard.mintlify.com).

## Support

- **Documentation Issues**: Open an issue in this repository
- **Product Support**: hi@getuntyped.ai
- **Mintlify Help**: [Mintlify Documentation](https://mintlify.com/docs)

## License

© 2025 Untyped. All rights reserved.
