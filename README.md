# Next.js Admin Panel

Implement the admin App for your Product Catalog with abilities to:
- add, modify and delete products
- upload photos to Amazon S3
- manage orders
- favorites (optional)
- Any other functionality you want to add
  - Add Auth to the Shop
  - Implement Profile page
  - Implement admin part to manage translations
  - Implement Admin dashboard with some order statistics
  - ...

Steps:
- Create new Next.js App with TypeScript and Tailwind
- Setup ESLint and Pretties
- Setup deployment to Vercel with PostgreSQL
- Use Prisma to create DB schema
- Use [Shadcn/ui](https://ui.shadcn.com/) as a component framework. It includes:
  - [Data Table](https://ui.shadcn.com/docs/components/data-table) (with @tanstack/react-table)
  - [Form](https://ui.shadcn.com/docs/components/data-table) (with React Hook Form and Zod)
  - ...
- Use [NextAuth](https://next-auth.js.org/) for Auth.
