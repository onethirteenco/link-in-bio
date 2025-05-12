# Contributing to Link-in-Bio

Thank you for your interest in contributing to Link-in-Bio! This document provides guidelines and instructions for contributing to this project.

## Forking the Repository

When you fork this repository, there are a few important things to note:

### Custom Domain Setup

This repository includes a CNAME file that points to `bio.one13.me`. When you fork the repository, you'll need to:

1. **Remove or Update the CNAME File**
   - Delete the CNAME file if you don't plan to use a custom domain
   - Or update it with your own custom domain if you have one

2. **GitHub Pages Configuration**
   - Go to your fork's Settings > Pages
   - If you removed the CNAME file, your site will be available at `username.github.io/link-in-bio`
   - If you added your own CNAME, make sure to configure your domain's DNS settings

### Local Development

1. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/link-in-bio.git
   ```

2. Add the original repository as upstream:
   ```bash
   git remote add upstream https://github.com/onethirteenco/link-in-bio.git
   ```

3. Keep your fork up to date:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

## Making Changes

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit them:
   ```bash
   git commit -m "Description of your changes"
   ```

3. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

4. Create a Pull Request from your fork to the original repository

## Code Style

- Follow the existing code style and formatting
- Use meaningful commit messages
- Comment your code where necessary
- Keep changes focused and minimal

## Questions?

If you have any questions about contributing, please open an issue in the repository. 