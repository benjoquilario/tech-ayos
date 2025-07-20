This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Code Quality & Git Hooks 🐕

This project uses **Husky** to maintain code quality and consistency through automated Git hooks:

### What happens when you commit:

- ✅ **Linting**: ESLint automatically fixes code style issues
- ✅ **Formatting**: Prettier formats your code consistently
- ✅ **Commit Message**: Validates commit message format

### What happens when you push:

- ✅ **Type Checking**: TypeScript validates all types
- ✅ **Build Test**: Ensures your code builds successfully

### Commit Message Format

Use this format for commit messages:

```
type(scope): description

Examples:
feat(auth): add user login functionality
fix(ui): resolve button alignment issue
docs: update README with setup instructions
```

**Types**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

### Available Scripts

- `npm run lint` - Check for linting issues
- `npm run lint:fix` - Fix linting issues automatically
- `npm run type-check` - Run TypeScript type checking

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
