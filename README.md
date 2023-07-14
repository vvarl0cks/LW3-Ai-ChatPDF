## Build an AI Chatbot to chat with any PDF

In this lesson, we are going to be building a chatbot that you can use to talk to any PDF (or even multiple PDFs). You, the user, can upload any PDFs you like on the app we will build, and the AI will learn the contents of that PDF file, allowing you to ask it questions about that file.  

📂 `demo` https://warlocsk-ai-chatpdf.netlify.app   

## Our Stack

We will use Next.js, TypeScript, Tailwind CSS, and Langchain for this project. We will also use Vercel’s new ai SDK.  

If you don’t have it already, make sure you download and install Node.js on your machine. Use the LTS version (18.x.x) - not the beta version.  

## Prerequisites

You need an OpenAI API Key to build this application. If you don’t have one already, you can sign up at https://openai.com to get one. While it is paid, it will not cost you even a single dollar for everything we’re about to do - yes, it’s that cheap.  

## Getting Started  

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).  

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
