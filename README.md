![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shadcn-ui](https://img.shields.io/badge/Shadcn--ui-000000?style=for-the-badge&logo=shadcn&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-000000?style=for-the-badge&logo=zod&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=zustand&logoColor=white)
![Nuqs](https://img.shields.io/badge/Nuqs-000000?style=for-the-badge&logo=nuqs&logoColor=white)
![Auth.js](https://img.shields.io/badge/Auth.js-000000?style=for-the-badge&logo=auth0&logoColor=white)
![Tanstack Tables](https://img.shields.io/badge/Tanstack_Tables-000000?style=for-the-badge&logo=tanstack&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-000000?style=for-the-badge&logo=reacthookform&logoColor=white)
![kbar](https://img.shields.io/badge/kbar-000000?style=for-the-badge&logo=kbar&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Husky](https://img.shields.io/badge/Husky-000000?style=for-the-badge&logo=husky&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-000000?style=for-the-badge&logo=prettier&logoColor=white)

# Softleo CRM Lite

## Overview

Softleo CRM Lite is a free and open-source CRM for small businesses. It has three major modules: Sales, Marketing, and Customer Support. Each module is designed to help businesses streamline their operations and enhance customer satisfaction.

- **Sales**: Manage your sales pipeline with features like accounts, contacts, leads, opportunities, and contracts. Track your sales progress and close deals more efficiently.
- **Marketing**: Boost your marketing efforts with tools for social marketing, email marketing with customizable templates, and campaign management. Reach your target audience and measure the effectiveness of your campaigns.
- **Customer Support**: Provide exceptional customer service with features like 1:1 chat with support agents and an AI-based chatbot. Resolve customer issues quickly and improve customer satisfaction.

### Sales

The Sales module includes:

- Accounts
- Contacts
- Leads
- Opportunities
- Contracts

### Marketing

The Marketing module includes:

- Social Marketing
- Email Marketing with email templates
- Campaign Management

### Customer Support

The Customer Support module includes:

- Agents for 1:1 chat with customers
- AI-based chatbot

## Technologies

This is a starter template using the following stack:

- Framework - [Next.js 14](https://nextjs.org/13)
- Language - [TypeScript](https://www.typescriptlang.org)
- Styling - [Tailwind CSS](https://tailwindcss.com)
- Components - [Shadcn-ui](https://ui.shadcn.com)
- Schema Validations - [Zod](https://zod.dev)
- State Management - [Zustand](https://zustand-demo.pmnd.rs)
- Search params state manager - [Nuqs](https://nuqs.47ng.com/)
- Auth - [Auth.js](https://authjs.dev/)
- Tables - [Tanstack Tables](https://ui.shadcn.com/docs/components/data-table)
- Forms - [React Hook Form](https://ui.shadcn.com/docs/components/form)
- Command+k interface - [kbar](https://kbar.vercel.app/)
- Linting - [ESLint](https://eslint.org)
- Pre-commit Hooks - [Husky](https://typicode.github.io/husky/)
- Formatting - [Prettier](https://prettier.io)

_If you are looking for a React admin dashboard starter, here is the [repo](https://github.com/deepakkamboj/softleo-crm-lite)._

## Pages

| Pages | Specifications |
| :---- | -------------- |

```plaintext
.
├── app
│   ├── (auth)
│   │   ├── _components
│   │   │   ├── user-auth-form.tsx
│   │   │   └── sigin-view.tsx
│   │   └── (signin)
│   │       └── page.tsx
│   ├── dashboard
│   │   ├── _components
│   │   │   ├── overview.tsx
│   │   │   └── recent-sales.tsx
│   │   └── page.tsx
│   └── layout.tsx
├── components
│   ├── date-range-picker.tsx
│   ├── icons.tsx
│   ├── layout
│   │   ├── app-sidebar.tsx
│   │   └── page-container.tsx
│   └── ui (shadcn ui components)
│       ├── button.tsx
│       ├── card.tsx
│       └── tabs.tsx
├── constants
│   └── index.ts
├── context
│   └── auth-context.js
├── firebase
│   ├── config.ts
│   └── firebase.ts
├── hooks
│   └── useAuth.ts
├── lib
│   └── utils.ts
├── types
│   └── index.ts
├── styles
│   └── globals.css
├── .env
├── README.md
└── package.json
```

### Explanation

1. **Project Structure**: Added a `Project Structure` section that outlines the directory structure of the project. This helps users understand the organization of the project files and directories.
2. **Technologies Section**: Kept the technologies section with badges as it is.
