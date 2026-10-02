# 🥬 Pantry

A shared grocery and to-do list with smooth animations. Add items, tick them off, and delete them. Everyone with the link sees the same list.

**Live demo:** https://pantry-six-mu.vercel.app/

> The backend runs on a free server that sleeps when idle, so the first load can take up to a minute.
<img width="1887" height="1022" alt="image" src="https://github.com/user-attachments/assets/5afe4def-d897-4530-9214-5cac5f80655c" />


## Features

- Add groceries and to-dos, tag them by category, and filter by All, Groceries, To-dos or Done
- Check items off, delete them, or clear everything that's done
- Progress bar showing how much of the list is complete
- Shared list stored in a database, refreshing every 10 seconds so changes from other people appear
- Responsive layout for phone and desktop

## Animations and micro-interactions

- Items spring in and slide out, and the list reflows smoothly
- Checkbox pops, the tick draws itself, and a strike-through sweeps across the text
- Sliding pill indicators on the filter tabs and category toggle
- Animated progress bar
- Hover and tap feedback on buttons, plus a rotating delete icon
- Bobbing empty-state illustration

## Tech stack

| Area | Tools |
| --- | --- |
| Frontend | React, TypeScript, Vite |
| Styling | styled-components |
| Animation | Framer Motion |
| Backend | Node.js, Express, TypeScript |
| Database | MongoDB Atlas (Mongoose) |
| Hosting | Vercel (frontend), Render (API) |

## Architecture

```
Browser (React app on Vercel)
        │  REST API (JSON)
        ▼
Express API on Render ──► MongoDB Atlas
```

## Source code

The source code is private. If you'd like to see it or talk about the project, get in touch:

- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)
- Email: YOUR-EMAIL
