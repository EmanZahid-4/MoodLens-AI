# Issue Finder

Find beginner-friendly open source issues on GitHub, by language, in seconds. Built for Hacktoberfest.

**Live demo:** https://YOUR-USERNAME.github.io/issue-finder

## What it does
- Searches GitHub live for open issues that nobody is assigned to
- Filters by language, issue type (good first issue, help wanted, documentation, hacktoberfest) and keyword
- Sorts by newest, recently active, or most discussed
- Shows how old each issue is and how many comments it has, so you can spot ones that are still free
- Lets you save issues in your browser to work on later
- Light and dark theme, works on phones

## Why
Many beginners want to join Hacktoberfest but do not know where to start. Finding a good, free issue is the hardest step. This tool does that step for you.

## Run it
1. Download or clone this repository.
2. Open `index.html` in a browser. No build step, no API key, no account.

To publish: **Settings → Pages → Deploy from a branch → main / (root)**.

## Tech
HTML, CSS, vanilla JavaScript, the GitHub Search API, and browser `localStorage`.

## Good to know
GitHub allows about 10 unauthenticated searches per minute. If you hit the limit, the app tells you when to try again. Results come from GitHub's public data, so always read the project's CONTRIBUTING.md and comment on an issue before you start work.

## Contributing
Contributions are welcome. Ideas for first issues:
- Show repository stars and description
- Add a "my saved issues" export
- Add Urdu interface text
- Add keyboard shortcuts
- Add tests

Fork the repo, create a branch, make one focused change, and open a pull request.

## License
MIT
