# Imaginify

Imaginify is a full-stack SaaS application for AI-powered image generation and transformation. It supports user authentication, a credit-based system using Stripe, and image processing through Cloudinary AI.

## Features

- AI-based image enhancement and generation
- Credit system with Stripe integration
- User authentication and management via Clerk
- Image storage and transformation with Cloudinary
- Responsive and optimized UI built with Next.js and Tailwind CSS

## Tech Stack

- Next.js
- Stripe (payments and credits)
- Clerk (authentication)
- Cloudinary (AI image handling)
- Tailwind CSS

\`\`\`bash

Create a .env.local file and add:

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

#CLERK URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLERK WEBHOOK SECRET
WEBHOOK_SECRET=
#MongoDB
MONGODB_URL=

#Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

#Other
NEXT_PUBLIC_SERVER_URL=

\`\`\`
