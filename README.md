# Bifrost - DevDependencies

This project includes the basic list of dependencies needed in a project. In this list we include:

- Mocha
- Chai
- Sinon
- NYC
- Nock

There are several motivations behind this project:

- Keep a *standard set* of `devDependencies` used across different projects
- Keep latest versions up to date, specially for security fixes, in a centralized way
- The cost and responsibility of reviewing and updating this library could fall to single team instead of the large number of separate teams across your company
- Reduces "decision fatigue", as you use recommended practices defined by your company
- Helps defining base dependencies for new projects (scaffolding)

## Maintaining versions

Use `npm outdated` to check for newer versions, suggested migration version, etc. Analyze if necessary or desired (e.g. security fixes vs new features).

Then, maintain semantic versioning and update release notes with the changes collected from the different packages.