# Social Desk

A local-first AI social media manager dashboard built with Next.js App Router, TypeScript and Tailwind CSS. The interface follows the supplied Stitch Precision Slate & Indigo design system.

## Requirements

- Node.js 18.17+ (Node 20 LTS recommended)
- npm

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Production build

```bash
npm run build
npm start
```

## What is included

- Overview, Research, Composer, Calendar, Analytics and Connections sections.
- All seed content in `src/data/mock.ts`.
- Replaceable simulated AI functions in `src/lib/ai.ts` (trend research, per-platform copy drafts and image placeholder generation).
- Approval gate: generated posts enter **Needs approval**; approve first, then schedule.
- Sample connection dialogs only. No real sign-in, passwords, tokens or social API calls.
- Responsive sidebar, loading feedback, empty states and error feedback.

## Configuration

No environment variables or API credentials are required. `.env.example` is intentionally empty apart from an explanatory comment.

## Notes

This is a front-end demo. Changes are held in React state and reset on refresh. Trend, post and analytics values are sample data; publishing, scheduling and account connections do not contact external services.
