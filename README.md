This is a [Next.js](https://nextjs.org/) portfolio project.

## Getting Started

### 1. Install Dependencies

First, install the project dependencies:

```bash
npm install
```

### 2. Configure Environment Variables (Optional)

This project uses Notion API for the Journal page. If you want this feature to work, you'll need to configure the environment variables:

1. Copy the `.env.example` file to `.env.local`:
   ```bash
   cp .env.example .env.local
   ```

2. Fill in your API keys in `.env.local`:
   - `NOTION_API_KEY`: Get from [Notion Integrations](https://www.notion.so/my-integrations)
   - `NOTION_TASKS_ID`: Your Notion tasks database ID
   - `NEXT_PUBLIC_MAPBOX_API_KEY`: Get from [Mapbox](https://account.mapbox.com/)

**Note:** The project will build and run without these variables. The Journal page will simply be empty if not configured.

### 3. Run the Development Server

First, run the development server...

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
