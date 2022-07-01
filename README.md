# tauOS Flatpak Platform

The Flatpak Platform for tauOS apps.

## Publishing

This repository has CI/CD set up. Building and publishing is handled automatically with the help of some amazing GitHub
actions, and takes no human interaction.

### Daily

Every push to the `main` branch will start a build and publish it to our repository under the `daily` branch. This
branch is built frequently and is **not recommended for production**.

### Stable

To release a new stable version of the platform, simply run the Release CI.
