# App Repository

This repository contains the application code and deployment configurations.

## Project Structure

```
├── src/             # App code
├── deploy/
│   ├── build.yaml   # Builds Docker images
│   ├── tag.yaml     # Tags images (e.g., v1.0-dev, v1.0-stage, v1.0-prod)
└── README.md
```

## Development

The `src/` directory contains the application source code.

## Deployment

The `deploy/` directory contains the configuration files for building and tagging Docker images:

- `build.yaml`: Configuration for building Docker images
- `tag.yaml`: Configuration for tagging images for different environments (dev, stage, prod)
