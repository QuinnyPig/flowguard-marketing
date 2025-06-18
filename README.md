# FlowGuard Marketing Site

Static marketing site for FlowGuard that lives at flowguard.dev.

## Quick Start

```bash
npm install
npm run dev
```

Visit http://localhost:3000

## Deployment

This site is deployed to Vercel:

- **Production**: [flowguard.dev](https://flowguard.dev) (from `main` branch)
- **Staging**: [staging.flowguard.dev](https://staging.flowguard.dev) (from `staging` branch)  
- **Development**: [dev.flowguard.dev](https://dev.flowguard.dev) (from `dev` branch)

### Automatic Deployment

Push to the appropriate branch:
- `main` → Production
- `staging` → Staging
- `dev` → Development

### Manual Deployment

```bash
vercel --prod  # Deploy to production
vercel         # Deploy preview
```

## Structure

- `index.html` - Main landing page
- `css/style.css` - All styles
- `vercel.json` - Vercel configuration

## OAuth Integration

The "Sign in with GitHub" buttons automatically link to the appropriate app subdomain based on the current environment:

- `flowguard.dev` → `app.flowguard.dev`
- `staging.flowguard.dev` → `app.staging.flowguard.dev`
- `dev.flowguard.dev` → `app.dev.flowguard.dev`
- `localhost` → `localhost:3000`

## Related Repositories

- [flowguard](https://github.com/yourusername/flowguard) - Main application repository

## License

Copyright © 2025 FlowGuard. All rights reserved.