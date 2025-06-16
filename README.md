# LetsMeetAI

1st Step:


2nd Step Database setup:

- Add a PostgreSQL database (Neon)
- https://console.neon.tech/app/projects/blue-mouse-29727917?database=neondb

- Add DrizzleORM => npm i drizzle-orm@0.43.1 @neondatabase/serverless@1.0.0 dotenv@16.5.0 --legacy-peer-deps
                 => npm i -D drizzle-kit@0.31.1 tsx@4.19.4 --legacy-peer-deps

- Add Schema
- Push schema => npx drizzle-kit push
- Verify changes in Neon
- Verify changes in Drizzle Studio =>  npx drizzle-kit studio

Key features:
🤖 AI-powered video calls
🧠 Custom real-time agents
📞 Stream Video SDK
💬 Stream Chat SDK
📝 Summaries, transcripts, recordings
📂 Meeting history & statuses
🔍 Transcript search
📺 Video playback
💬 AI meeting Q&A
🧠 OpenAI integration
💳 Polar subscriptions
🔐 Better Auth login
📱 Mobile responsive
🌐 Next.js 15 + React 19
🎨 Tailwind v4 + Shadcn/ui
⚙️ Inngest background jobs
🧑‍💻 CodeRabbit PR reviews
