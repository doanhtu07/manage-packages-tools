# manage-packages-tools

Tools to help managing and updating packages

## Prompt

Given a set of projects

For Expo repos, use `pnpm epc` for Expo managed packages

For Expo managed packages, I allow bypassing `minimumReleaseAgeExclude`

But for other packages, ONLY update to the latest version THAT is not violating minimum release age
