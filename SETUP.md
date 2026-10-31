# Yaswanth Kishore — GitHub Profile Setup

1. Extract this ZIP.
2. Copy everything inside `yaswanth296-profile-kit` into the root of your public `yaswanth296` repository.
3. Replace the existing `README.md` when prompted.
4. Keep the `assets/` and `.github/` folders in the repository root.
5. Commit and push to the `main` branch.

## Contribution snake

The workflow is at `.github/workflows/snake.yml`. In GitHub, open **Actions → Generate contribution snake → Run workflow**. After it succeeds, GitHub publishes `contribution-snake.svg` to the `output` branch. The README image will then load from that branch.

## Technology icons

The README uses Skill Icons for the core development stack and Shields.io marks for Gemini, OpenAI and Google Apps Script. These are externally hosted image services, so they require an internet connection to render.

## Notes

- The profile photo is stored at `assets/profile.png`.
- Update the technology list if your active stack changes.
- GitHub statistics and contribution images are provided by external services and may occasionally be rate-limited or temporarily unavailable.


## Emerald theme refresh (v2)

All custom SVG assets now use filenames beginning with `emerald-`. This intentionally changes image URLs to avoid stale cached burgundy artwork. Upload the complete `assets/` folder and the matching README together.


## Contribution graph color update (v3)

The contribution snake now uses the `github-green` palette to make activity cells green instead of the default dark/purple palette. The streak card also has explicit bright emerald labels and white numbers for readable contrast. After pushing, run **Actions → Generate contribution snake → Run workflow** once to regenerate the SVG on the `output` branch.
