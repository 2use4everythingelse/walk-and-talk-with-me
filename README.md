# Walk & Talk with Me

Official website for Walk & Talk with Me — a welcoming community walking group.

## Preview on your computer (beginner guide)

This branch is a foundation for review. Nothing has been published and no deployment is configured.

1. Install the LTS version of Node.js (22.12 or later).
2. On GitHub, select the `codex/astro-foundation` branch. Choose **Code → Download ZIP**, then extract the ZIP.
3. Open the extracted project folder in VS Code. Select **Terminal → New Terminal**.
4. Run `npm install` once to install the project's dependencies.
5. Run `npm run dev`.
6. Open the Local address printed in the terminal, usually **http://localhost:4321**. Keep the terminal running while you preview. Press Ctrl+C to stop.

To check the mobile layout in Chrome or Edge, press F12, then Ctrl+Shift+M and select a phone size. The page stacks into one column on small screens; navigation wraps without a hidden menu.

For a production-style preview: run `npm run build`, then `npm run preview`, and open the printed local address. These commands do not publish the website.

## What's included

- Astro static website with cream, olive green, and navy styling.
- Responsive navigation, skip link, keyboard focus styles, semantic headings, and reduced-motion support.
- Exactly eight homepage sections: welcome, All Are Welcome, Long Story Short, The Game Plan, What to Bring, Where We Meet, Behind the Walk, and invitation.
- Clearly labeled HTML artwork placeholders; no generated images, external fonts, or image downloads.
- Footer reserves the original circular logo, with “Come as you are.” on the left and “There’s room for you.” on the right. It stacks on mobile.
- Existing blog titles with clearly labeled text placeholders. Schedule details and new supporting copy should be reviewed before launch.

## Where to edit

- `src/pages/index.astro`: eight sections and homepage text.
- `src/layouts/BaseLayout.astro`: navigation, page metadata, and footer.
- `src/styles/global.css`: colors, typography, spacing, and mobile styles.
- `src/components/ArtworkPlaceholder.astro`: reusable labeled artwork space.
- `public/artwork/README.md`: instructions for inserting approved artwork.

## Checks

`npm run check` checks Astro and TypeScript. `npm run build` generates the static site in `dist/`.

The initial foundation passed both commands with zero diagnostics. A desktop browser preview and navigation link were checked. Mobile CSS is included; a device-sized visual check remains recommended before launch.

No registration form, tracking, publishing workflow, or live hosting is configured.
