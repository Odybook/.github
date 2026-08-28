# Odybook

<div align="center">
  <img src="odybook_banner_sketchbook.png" alt="Odybook Paris" width="480" style="border-radius: 12px; margin-bottom: 16px;" />
  <p><strong>The modern operating system and white-label storefronts for tour operators and travel agencies.</strong></p>
  <p>
    <a href="https://odybook.com"><img src="https://img.shields.io/badge/Website-odybook.com-black?style=flat-square" alt="Website" /></a>
    <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-16.1-black?style=flat-square&logo=next.js" alt="Next.js" /></a>
    <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19.2-blue?style=flat-square&logo=react" alt="React" /></a>
    <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind-4.0-38bdf8?style=flat-square&logo=tailwindcss" alt="Tailwind CSS" /></a>
    <a href="https://supabase.com/"><img src="https://img.shields.io/badge/Supabase-Auth%20%26%20Data-3ecf8e?style=flat-square&logo=supabase" alt="Supabase" /></a>
    <a href="https://stripe.com/"><img src="https://img.shields.io/badge/Stripe-Connect%20Billing-635bff?style=flat-square&logo=stripe" alt="Stripe" /></a>
    <a href="https://odybook.com"><img src="https://img.shields.io/badge/License-Proprietary-red.svg?style=flat-square" alt="License" /></a>
  </p>
</div>

---

## Ecosystem

| Repository | Role | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[`odybook-web`](https://github.com/Odybook/odybook-web)** | Multi-tenant ERP, booking engine, Stripe Connect payouts, CRM & MCP API | Next.js 16, PostgreSQL, Knex, Supabase | `Core Platform` |
| **[`odybook-sites`](https://github.com/Odybook/odybook-sites)** | High-performance white-label storefront engine with dynamic OKLCH theming | Next.js 16, React 19, Tailwind 4, MDX | `Storefront Engine` |
| **[`odybook-ops`](https://github.com/Odybook/odybook-ops)** | Autonomous operations, AI copilot, and agent task dispatching pipelines | TypeScript, Shell, AI Harness | `Operations` |
| **[`odybook-mcp`](https://github.com/Odybook/odybook-mcp)** | Model Context Protocol (MCP) server for agentic commerce and AI booking tools | MCP SDK, TypeScript, Node.js | `Agentic API` |
| **[`odybook-docs`](https://github.com/Odybook/odybook-docs)** | Developer documentation, API reference, and architecture guides | Mintlify, MDX | `Documentation` |

---

## Platform Architecture Highlights

- **Direct Booking Engine**: Real-time availability, schedule rules, 2-step mobile checkout, and direct-charge Stripe Connect payouts.
- **White-Label Storefronts**: Instant subdomains (`{guide}.odybook.com`) and custom domains with server-side theme injection and zero layout shift.
- **Agentic Commerce**: Native MCP tool server enabling autonomous AI coding agents and travel copilots to check availability and place reservations.
- **Global & Multilingual**: Built-in 5-language localization (EN, FR, ES, DE, IT) and real-time multi-currency exchange rates.
- **Two-Way Channel Sync**: Automatic calendar reconciliation with Viator, TripAdvisor, Airbnb Experiences, and Google Calendar.

---

<div align="center">
  <p>Based in Paris, France 🇫🇷 &bull; <a href="https://odybook.com">odybook.com</a></p>
</div>
