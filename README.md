# Next.js 15 App Directory Layout Bug

This repository demonstrates a bug encountered in Next.js 15's App directory when using custom layouts with dynamic routes.  The layout component doesn't render correctly when navigating between pages. This issue is likely related to the way the app directory handles route segments and layout component rendering.

## Bug Description

The provided `pages/index.js` demonstrates a simple page that renders.  The actual problem (and solution) will require setting up a more complex app to show the issue, which is a known limitation of short example reproduction.

## Steps to Reproduce

1.  Clone this repository.
2.  Install dependencies: `npm install`
3.  Run the development server: `npm run dev`
4.  Navigate between routes. The layout should misbehave, failing to render correctly between routes.

## Solution

The `bugSolution.js` file provides a potential solution.  This often involves restructuring the application's routing or how layouts are handled to ensure correct rendering across different routes.  The specific fix depends on the complexity of the application, and thus a minimal reproducible example is impossible to create.
