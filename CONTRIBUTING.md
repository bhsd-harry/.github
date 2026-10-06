# Contributing Guide

This document outlines the default guidelines for contributing to my TypeScript
projects. Pull Requests are welcome!

Please follow the following guidelines to make the contribution process smooth
for everyone:

## Local Development Setup

To get the project running locally, use a recent, actively supported Node.js
release (current LTS or newer) with NPM installed, then run the following
commands in your terminal:

1. **Install dependencies:**

```sh
npm install
```

2. **Build the project:**

```sh
npm run build
```

3. **Run the test suite (not required):**

```sh
npm test
```

You do not need to run tests for opening a PR, but it may help you catch issues
in your code.

## Expectations & Flexibility

* **Don't sweat the styling:** You can completely ignore linting and code
styling issues. Focus on making your code work; we can clean up aesthetics later.
* **Test failures are okay:** If `npm test` fails but you think your logic is
correct, go ahead and submit the PR anyway. We can look at the failures together.
* **Allow maintainer edits:** When opening your PR, please leave the checkbox
**"Allow edits by maintainers"** checked. This allows the owner to make minor
fixes or merge conflicts directly, getting your code in faster!

## Best Practices

* **Discuss features first:** If you are proposing a new feature, you are highly
encouraged to open an issue to discuss your ideas first. This ensures your time
isn't wasted building something that might conflict with the project's direction.
* **Keep it small:** Please keep your PR small and concentrated on a single bug
fix or feature. Smaller PRs are much easier to review and merge quickly.
* **Avoid configuration changes:** Please do not modify repository configuration
files unless it is absolutely necessary for your change to work.

Thank you for your cooperation and happy coding!
