# Truno — Embodied Intelligence Portfolio

Website portfolio + engineering journal built with Astro.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown by Astro, normally:

`http://localhost:4321`

## Build

```bash
npm run build
npm run preview
```

## Add a project

Edit `src/data/projects.js` and add another object.

## Add videos

Put local videos in:

`public/videos/`

Then use the `video` field in a project, for example:

```js
video: "/videos/my-robot.mp4"
```

You can also use an external video URL if desired.

## Deploy

Push the project to GitHub and import the repository into Vercel.
