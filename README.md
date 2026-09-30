# Ansible Role: mise

This role installs [`mise`](https://mise.jdx.dev/) on Debian/Ubuntu systems using the `extrepo` package source and `apt`.

## What this role does

- Ensures `extrepo` is installed.
- Enables the `mise` repository with `extrepo` (if not already enabled).
- Refreshes APT metadata when needed.
- Installs the `mise` package.

## What is mise?

- Official documentation: <https://mise.jdx.dev/>
- GitHub repository: <https://github.com/jdx/mise>
- Project overview: <https://mise.jdx.dev/about.html>
