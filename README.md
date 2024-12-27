# Tailwind CSS Purge Configuration Error

This repository demonstrates a common error encountered when using Tailwind CSS with frameworks like Next.js or Nuxt.js.  The problem arises from an incorrectly configured `purge` option (or `content` in newer Tailwind versions), causing styles to be unexpectedly removed from the final CSS output.

The `bug.js` file shows an example of a Next.js project with an incomplete purge configuration.  The `bugSolution.js` provides the corrected configuration.

## Setup

1. Clone this repository.
2. Run `npm install`.
3. Start the development server (instructions may vary depending on your framework).

## Bug Reproduction

Run the project with the `bug.js` configuration.  You'll observe that some elements lack the expected Tailwind CSS styles.

## Solution

Switch to the `bugSolution.js` configuration file to see the corrected implementation.  The solution involves ensuring that all relevant component and page files are included in the `purge` (or `content`) option.