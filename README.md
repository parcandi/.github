# Parcandi `.github` Repository

The `.github` repository is a special fallback repository for all other repositories in the Parcandi organization. GitHub uses it to provide certain defaults wherever an individual repository does not define its own. A good real-world example is GitHub's own setup: [github/.github](https://github.com/github/.github).

Typical contents of such a repository include default community health files like `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md` and `SUPPORT.md`, as well as issue and pull request templates. These files are applied automatically to every repository in the organization that does not have its own version. See the GitHub documentation on [creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for the full list of supported files and their rules (for example, the repository generally needs to be public for the defaults to take effect).

Beyond that, the `.github` repository can host a `profile/README.md`, which is shown on the organization's public GitHub page ([customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)), and a `workflow-templates/` folder with reusable GitHub Actions starter workflows for all teams ([creating workflow templates for your organization](https://docs.github.com/en/actions/sharing-automations/creating-workflow-templates-for-your-organization)).

At Parcandi, this repository is currently not in use: it contains no active defaults, templates or profile content, so it has no effect on any other repository. We could therefore delete it without side effects, but we keep it as a placeholder in case organization-wide defaults are introduced later.

If you have questions about this repository or would like to propose organization-wide defaults, please contact the Parcandi development team.
