## Development 💻

### Farcaster Replicator

This project depends on the Farcaster PosgreSQL database. Follow the instructions at [replicate-data-postgres](https://github.com/farcasterxyz/hub-monorepo/tree/main/packages/hub-nodejs/examples/replicate-data-postgres) to set up an instance.

### Local

1. `yarn`

1. Copy the `.env.sample` file to `.env` and fill in the database connection details.

1. `yarn dev`

## Todo

- [ ] Feed
  - [x] Reverse chronological feed
  - [x] Pagination
  - [x] Number of likes, comments, and reposts
  - [ ] Recasts
- [x] Cast detail
  - [x] Number of likes, comments, and reposts
  - [x] Paginated replies
- [x] User profiles
  - [x] Casts
  - [ ] Casts with replies
  - [ ] Media
  - [ ] Likes
- [x] Auth
- [x] Engagement actions
- [x] Post creation
- [x] Post deletion
- [ ] Search
- [x] Channels (now called Topics)
  - [x] Channel detail
  - [x] Channel discovery
  - [ ] Index channels
- [ ] Rebrand

...

## Tech 🛠

- [Next.js](https://nextjs.org)
- [TypeScript](https://www.typescriptlang.org)
- [Tailwind CSS](https://tailwindcss.com)
- [SWR](https://swr.vercel.app)
- [Headless UI](https://headlessui.com)
- [React Hot Toast](https://react-hot-toast.com)
- [Framer Motion](https://framer.com)
