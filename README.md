# Next.js 15 App Router: RSC Component Issue in Layout

This repository demonstrates a bug encountered when utilizing React Server Components (RSC) within a layout in Next.js 15's App Router.  The issue manifests as unexpected rendering behavior, potentially related to data fetching and component hydration.

## Problem

When an RSC component is placed within a layout, it may not correctly re-render when its props change. This often leads to stale data being displayed on subsequent page navigations or interactions.

## Reproduction Steps

1. Clone this repository.
2. Navigate to the `pages` directory.
3. Run `npm install`.
4. Run `npm run dev`.
5. Observe the behavior, and compare with the solution.

## Potential Solutions (Explore the `bugSolution.js` file for implementation details)