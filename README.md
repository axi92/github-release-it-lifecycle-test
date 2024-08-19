# github-release-it-lifecycle-test
This repo only serves the purpose to test the release-it lifecycle on github with actions.

## Requirements

- An account that got access to the repo to push commits
- GPG key that got the same username and mail from that said account, this key will be used to sign commits and tags when the release is commited
- GITHUB Token (Classic) from that account created from the [github Settings/Developer Settings/Tokens](https://github.com/settings/tokens) with __all__ the permissions for "__repo__"
- NPM token that got access to the already published package (release-it can only publish updates and is not able to publish  the first version to npm)
