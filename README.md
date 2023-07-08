# Conventional commits

Conventional commits is a specification for giving meaning to commits messages.

This is a document I will post a basic guide based on the [conventionalcommits](https://www.conventionalcommits.org/en/v1.0.0/) page of how to create specific commits based on the PR that is being created.

## feat

Adding new features or enhancements. New functionalities, implementing new user interface, etc.

```
git commit -m "feat: Add user registration form with validation"
```

## fix

Fixing bugs.

```
git commit -m "fix: Resolve issue with navigation bar not displaying correctly"
```

## chore

Focus on keeping the project organized. Updating dependencies, managing configuration files, cleaning up code, removing unused files.

```
git commit -m "chore: Update dependencies to the latest version"
```

## test

Changes related to testing.

```
git commit -m "test: Write unit test for the login component"
```

## docs

Updates or addition to documentation.

```
git commit -m "docs: Update README with installation instructions"
```

## build

Changes to the build system or process. Updating webpack for instance.

```
git commit -m "build: Update webpack configuration for production build"
```

## ci

Changes to the continuous integration configuration or setup.

```
git commit -m "ci: Configure continuous integration for automated testing"
```

## style

Changes related to code style or visual enhancements.

```
git commit -m "style: Apply consistent color scheme to buttons"
```

## refactor

Code refactoring or restructuring.

```
git commit -m "refactor: Extract function for date formatting"
```

## perf

Performance improvements.

```
git commit -m "perf: Optimize image loading for faster page rendering"
```

## revert

Reverting previous changes.

```
git commit -m "revert: Revert previous commit that introduced login form"
```
