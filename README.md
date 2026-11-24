# Date Counter

A small React app that moves a date forward or backward by a selected number of
days. The starting date is November 24, 2026.

The original Date Counter v1 used `useState`. It has since been improved in the
latest version to use React's `useReducer` for managing the counter state.

## Use the counter

- Adjust the range slider to choose a step from 0 to 10 days.
- Use the `+` and `-` buttons to move the date by that step.
- Edit the count directly to jump to a specific number of days from the start.
- Select **Reset** to return the count to 0 and the step to 1.

## Run locally

Install the dependencies and start the Vite development server:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your browser.

## Other commands

```bash
npm run build    # Create a production build
npm run preview  # Preview the production build
npm run lint     # Run ESLint
```

## Built with

- React
- Vite
