# python38-runner

Run custom python library in the container

#### Environment Variables

- PACKAGE_NAME: Your package name from global pypi (required)
- PACKAGE_VERSION: Your package version (optional)
- REQUIREMENTS_PACKAGES: Your needs packages with space sperator (optional)
- OS_DEPENDENCIES: For installing debian packages (optional)
- STARTUP_COMMAND
- REPOSITORY_URL (without trailing slash)
- REPOSITORY_HOST: Hostname of repository.
- PRE_START_SCRIPT: Path of pre start script
- POST_START_SCRIPT: Path of post start script
