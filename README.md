# EL's Shelf (dev)

This is the dev environment for creating and testing content on reading blog

## URL

https://ayeryn.github.io/els-shelf-dev/

## Technologies

Jekyll, GitHub (Git Pages), GitHub Action

### GitHub Action

#### deploy-to-live.yml

Trigger a deployment to `deploy` branch in `els-shelf-live` repository when there's a push onto `main` branch here.

- Ignore files:
  - `README.md`
  - GitHub config files (`.github/`)
