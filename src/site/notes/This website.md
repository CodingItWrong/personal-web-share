---
{"dg-publish":true,"permalink":"/this-website/","dg-note-properties":{}}
---

I opted for a [[Hypermedia\|hypermedia]] structure for this website because by this time in my life I’ve realized I can’t describe myself in a linear way.

It's currently published in the following way:

- Markdown files written on any of my devices in [Obsidian](https://obsidian.md/) synced via [Obsidian Sync](https://obsidian.md/sync) (Plus to support multiple vaults, to keep the site separate from my personal notes vault)
- Published to GitHub via [Obsidian Digital Garden](https://docs.forestry.md/)
- This git repo has two branches:
	- `main`
	- `live`
- Two separate [Vercel](https://vercel.com)  projects: one pointing to each of the `main` and `live` branches, which automatically publish any changes
- So my workflow is:
	- Write changes in Obsidian
	- Publish to the main branch via Obsidian Digital Garden
	- Vercel deploys to the preview domain
	- I review the deployed changes and make any corrections needed
	- When I’m happy with the changes I run a [GitHub Actions workflow](https://github.com/CodingItWrong/digitalgarden-me/blob/main/.github/workflows/deploy.yml) which merges them to the `live` branch where they’re then deployed to the live domain

It’s not a perfect setup; I may still someday revive an old project TypeLink for live editing of a personal wiki web site. But the Obsidian ecosystem does provide a lot of advantages.

Goals:

- Sourced from Markdown files
- Good UX to edit on macOS, Linux, iPad, and iPhone
- Reliable deploys. It doesn’t need to be perfect as it’s a personal web site. But if things are regularly breaking I will be disincentivized to post
- Minimal steps to deploy from mobile
- No or low cost