# Run in Dev

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Clone `env.template` and rename it to `.env`.
4. Start the database with `docker-compose up -d`.
5. Generate the Prisma client with `npx prisma generate`.
6. Run the project with `npm run start:dev`.
