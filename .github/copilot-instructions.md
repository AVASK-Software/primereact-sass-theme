# GitHub Copilot Instructions

## Branch Workflow

All development work should be based off the `develop` branch.

### Before Starting Any Work

1. **Switch to the develop branch:**
   ```bash
   git checkout develop
   ```

2. **Pull the latest changes:**
   ```bash
   git pull origin develop
   ```

3. **Create your feature branch from develop:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Branch Naming Convention

- Feature branches: `feature/<description>`
- Bug fixes: `bugfix/<description>`
- Hotfixes: `hotfix/<description>`

### Development Workflow

1. Make your changes on your feature branch
2. Test your changes thoroughly
3. Create a Pull Request targeting the `develop` branch
4. After review and approval, your changes will be merged to `develop`

## Important Notes

- **Always base your work on `develop`**, not `main` or any other branch
- Keep your feature branch up to date with develop by regularly pulling changes
- Ensure all tests pass before creating a pull request
