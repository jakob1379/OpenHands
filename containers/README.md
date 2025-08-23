# Docker Containers

Each folder here contains a Dockerfile, and a config.sh describing how to build
the images and where to push them. These images are built and pushed in GitHub Actions
by the `ghcr.yml` workflow.


Note: During migration to uv, the app and runtime images will prefer `uv sync` when `uv.lock` is present, and fall back to Poetry installs otherwise. Ensure `uv.lock` and `poetry.lock` are both present in the build context while the migration is in progress.

## Building Manually

```bash
docker build -f containers/app/Dockerfile -t openhands .
docker build -f containers/sandbox/Dockerfile -t sandbox .
```
