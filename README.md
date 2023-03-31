# github-break-glass-template

![License](https://img.shields.io/github/license/indentinc/github-break-glass-template?style=flat)

***Grant a break glass role for emergency use in order to limit GitHub admin or CODEOWNER access.***

[Read the blog post &rarr;](https://indent.com/blog/github-break-glass)

## Usage

1. Use this template to create a new repo
2. Change the `team` variable in the [`break-glass.yaml`](./.github/workflows/break-glass.yaml)
3. Create [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) that has team permission and add as `BREAK_GLASS_TOKEN` secret
4. Create an issue to get added to the team, close the issue to revoke

## What does it look like?

<img width="938" alt="Screenshot of a GitHub Issue containing an access request" src="https://user-images.githubusercontent.com/1026125/229153384-a9afebfe-6ae0-4c3d-aae8-0c2de4e1c323.png">
