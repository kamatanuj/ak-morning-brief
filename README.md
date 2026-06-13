# AK Morning Brief Dashboard

Live dashboard for AK's daily morning brief.

## URL

- **Production (ngrok)**: https://bevilled-malik-decennially.ngrok-free.dev/ak-brief.html
- **GitHub Pages**: https://kamatanuj.github.io/ak-morning-brief/ak-brief.html

## Contents

The dashboard includes:
- Daily market overview
- Key news highlights
- Exchange rates (USD/INR)
- Calendar/events for the day

## Deployment

The dashboard is served by a Python HTTP server on port 8080, tunneled via ngrok.

```bash
systemctl status ak-dashboard.service
```
