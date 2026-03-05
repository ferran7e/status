# Service Status

This repository powers the status page for our services.

**Status Page:** https://ferran7e.github.io/status

## Monitored Services

### ManageMySTR

- Platform website
- API endpoints

### External Dependencies

- Clerk Authentication
- Stripe Payments
- Vercel Hosting
- Census API

## How It Works

- [Upptime](https://upptime.js.org) monitors all endpoints every 5 minutes
- GitHub Actions runs the checks
- GitHub Pages hosts the status page
- Incidents are tracked via GitHub Issues

## Configuration

Edit `.upptimerc.yml` to:

- Add/remove monitored sites
- Change status page settings
- Configure notifications

## Adding a New Site

```yaml
sites:
  - name: My New Site
    url: https://example.com
```

Then push to main - monitoring starts automatically.
