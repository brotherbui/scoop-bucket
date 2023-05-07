# Scoop Bucket

[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-github-actions]][link-github-actions]
[![Repo Size][ico-github-repo-size]][link-github-repo-size]

A custom bucket for [Scoop][link-scoop].

# Install

Via Scoop

```powershell
scoop bucket add "brotherbui" "https://github.com/brotherbui/scoop-bucket"

# For a single package (replacing `package` with the required package)
scoop install "https://raw.githubusercontent.com/brotherbui/scoop-bucket/main/bucket/{package}.json"
```

## Credits

- [Brother Bui][link-author]


[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-github-actions]: https://img.shields.io/github/actions/workflow/status/brotherbui/scoop-bucket/auto-update.yml?branch=main&style=flat-square
[ico-github-repo-size]: https://img.shields.io/github/repo-size/brotherbui/scoop-bucket?style=flat-square

[link-github-actions]: https://github.com/brotherbui/scoop-bucket/actions
[link-github-repo-size]: https://github.com/brotherbui/scoop-bucket/tree/main/bucket
[link-scoop]: https://scoop.sh
[link-author]: https://github.com/brotherbui
