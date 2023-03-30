# github-break-glass-template

![License](https://img.shields.io/github/license/indentinc/github-break-glass-template?style=flat)

***Grant a break glass role for emergency use in order to limit GitHub admin or CODEOWNER access.***

[Read the blog post &rarr;](https://indent.com/blog/github-break-glass)

## Usage

1. Use this template to create a new repo
2. Change the `team` variable in the [`break-glass.yaml`](./.github/workflows/break-glass.yaml)
3. Create [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) that has team permission and add as `BREAK_GLASS_TOKEN` secret
4. Create an issue to get added to the team, close the issue to revoke
