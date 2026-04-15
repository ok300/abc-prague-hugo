# abc-prague-hugo

Sample Hugo blog with an initial "Hello World" post.

## Local development

```bash
hugo server -D
```

## Build

```bash
hugo --minify
```

## Deployment

GitHub Actions deploys the site to GitHub Pages:

- on each push to `main`
- on manual dispatch (`workflow_dispatch`) with optional `branch` input
