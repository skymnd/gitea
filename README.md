# Gitea in a homelab

This repo is my personal configuration for using gitea
on my homelab.
Gitea is an all-in-one software development service.
The
[Gitea docs](https://docs.gitea.com/)
are pretty good and can explain a bit more about what that
means.

## Environment Variables

I've added some extra environment variables to:
1. Enable Prometheus metrics
2. Configure Gitea for use behind a reverse proxy
3. Keep email addresses private

I set up SSO via authentik through the UI by following
the [docs](https://integrations.goauthentik.io/development/gitea/).

## Backup

I've selected some repos to be pushed to GitHub
every so often as a backup. See the docs on
[Repository Mirrors](https://docs.gitea.com/usage/repo-mirror#setting-up-a-push-mirror-from-gitea-to-github).