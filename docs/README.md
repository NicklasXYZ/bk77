# bk77

The website deploys to [bk77.dk](bk77.dk) and [https://nicklasxyz.github.io/bk77/](https://nicklasxyz.github.io/bk77/) for testing.

# build & deploy

Build and deploy using:

```bash
mkdocs build && scp -r site/* {username}@{website}:/www
```