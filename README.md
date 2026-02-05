# VERSE ONE - Combined Project

This is the combined project structure with all investment tier pages integrated into one deployment.

## Project Structure

```
verse-projects/
├── index.html                          (Main landing page)
├── vercel.json                         (Vercel routing configuration)
├── believer-patron/
│   └── index.html                      ($1,000-$2,499 tier)
├── community-supporter/
│   └── index.html                      ($2,500-$4,999 tier)
├── supporting-investor/
│   └── index.html                      ($5,000-$9,999 tier)
├── associate-producer/
│   └── index.html                      ($10,000-$19,999 tier)
└── executive-producer/
    └── index.html                      ($20,000+ tier)
```

## URLs After Deployment

- Main Page: `theverseprojects.com/`
- Believer Patron: `theverseprojects.com/believer-patron`
- Community Supporter: `theverseprojects.com/community-supporter`
- Supporting Investor: `theverseprojects.com/supporting-investor`
- Associate Producer: `theverseprojects.com/associate-producer`
- Executive Producer: `theverseprojects.com/executive-producer`

## What Was Changed

### Main Landing Page (index.html)
- Updated all investment tier links from external URLs to relative paths
- Changed from: `https://believer-patron.vercel.app/`
- Changed to: `/believer-patron`

### All Investment Tier Pages
- Updated "Back to Main Page" links from external URL to root path
- Changed from: `https://verse-one-landing-page.vercel.app/`
- Changed to: `/`

### Added Files
- `vercel.json` - Routing configuration for clean URLs

## Deployment Instructions

1. Delete your existing separate Vercel projects (optional, to avoid confusion):
   - believer-patron.vercel.app
   - community-supporter.vercel.app
   - supporting-investor.vercel.app
   - associate-producer.vercel.app
   - executive-producer.vercel.app

2. Deploy this combined project to your existing `verse-one-landing-page` project in Vercel

3. All pages will be accessible under your custom domain `theverseprojects.com`

## Notes

- NO code changes were made to design, content, or functionality
- ONLY links were updated to work with the new structure
- All forms, styling, and scripts remain exactly as they were
