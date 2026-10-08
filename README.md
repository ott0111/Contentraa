# Contentra

Contentra is an AI-powered creator growth workspace designed to connect brand intelligence, opportunity discovery, content creation, planning, and performance insights.

## Product direction

- **Understand:** Build a reusable Brand Brain around a workspace's audience, positioning, voice, and goals.
- **Discover:** Research relevant topics and content opportunities.
- **Create:** Develop original scripts, posts, briefs, and variations with brand context.
- **Organize:** Keep ideas, drafts, assets, and planned work in one place.
- **Improve:** Use available performance data to inform the next action.

The marketing site is built on Astro and Tailwind CSS, adapted from the open-source Pinwheel Astro theme. The public site should communicate the product vision without presenting planned integrations, analytics, or AI capabilities as live unless they are actually connected.

## Local development

Requires a supported Node.js LTS version and pnpm.

```bash
pnpm install
pnpm dev
```

## Build and validate

```bash
pnpm check
pnpm build
pnpm preview
```

## Current implementation notes

- The homepage, feature overview, workflow page, pricing page, site navigation, and footer are branded for Contentra.
- Plan prices are Free ($0), Pro ($19.99/month), Business ($49.99/month), and Agency ($129.99/month proposed).
- Social publishing, live analytics, account authentication, billing, and AI generation require their respective backend services and platform integrations before they can be treated as production functionality.

## License

This project started from the Pinwheel Astro theme. Review the upstream theme's MIT license and preserve its attribution requirements. Do not redistribute the upstream demo imagery unless its image license permits it.
