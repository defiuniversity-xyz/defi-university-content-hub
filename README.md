# DeFi University Content Hub

GitHub repository for the DeFi University Content Hub landing page.

This repository contains the landing page content that syncs to GitBook.

## Structure

```
defi-university-content-hub/
├── README.md                    # This file
├── content/
│   └── landing-page/
│       └── README.md            # Landing page content (syncs to GitBook)
└── .gitbook.yaml                # GitBook configuration (optional)
```

## Landing Page

The landing page content is located in `content/landing-page/README.md`.

This file syncs to the GitBook Space "Content Hub Landing Page" via GitHub integration.

## GitBook Sync

To sync this repository to GitBook:

1. Go to GitBook Space Settings → Integrations → GitHub
2. Connect this repository
3. Set root path to: `/content/landing-page`
4. Enable auto-sync for automatic updates

## Updating Content

1. Edit `content/landing-page/README.md`
2. Commit and push changes
3. GitBook will auto-sync (if enabled) or sync manually

---

© 2024 DeFi University. All rights reserved.

