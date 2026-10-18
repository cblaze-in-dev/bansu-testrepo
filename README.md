# Bansū spike 002 — GitHub test repository

Throwaway content for a public test repository used by spike 002 part 2.
TEST

1. Create a public repository on GitHub (any name), default branch `main`.
2. Copy `.github/` from this folder into it and push.
3. Settings → Environments → New environment `production` → Required reviewers: yourself.
4. Open one pull request from any branch (a one-line README change is enough).
5. Create a fine-grained token: Resource owner you, Repository access "Only select repositories" → this one; Repository permissions read-only: Actions, Contents, Deployments, Metadata, Pull requests. Save it to `~/.config/bansu-spike/github.token` and `chmod 600` it.
