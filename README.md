# manage-packages-tools

Tools to help managing and updating packages

## Prompt

Given a set of projects

For Expo repos, use `pnpm epc` for Expo managed packages

For Expo managed packages, I allow bypassing `minimumReleaseAgeExclude`

But for other packages, ONLY update to the latest version THAT is not violating the minimum release age
- Please check all packages carefully (either in NPM, POM, or something else)

Be careful! Some projects are explicitly using old Expo versions for a reason
