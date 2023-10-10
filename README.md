
This is a custom nextjs starter template project being developed by Dustin Schiffer for use in a variety of projects. It is being developed using pnpm, but the other package managers should work. It is a work in progress in active development.

This project utilizes Prisma and Prisma Studio. You will need to configure the database URL in the .env file and ensure the schema.prisma file is configured correctly. The project uses mysql, but you can use postgresql easily through Prisma if needed.

```bash
npx prisma db:push

# then

npx prisma generate

```

## Getting Started

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

