
## <a name="tech-stack">⚙️ The Stack</a>

- OpenAI API
- TypeScript
- Tailwind CSS
- Next.js

## <a name="features">🔋 Functions </a>

👉 **Revenue & Cost Register**: Users can input their income and expenses.

👉 **Money Administration**: Enables those manage their cash flow efficiently.

👉 **Customized Financial guide**: OpenAI's GPT-4 model combines user-specific data to provide accurate financial advise.

👉 **Adaptable Planning**: offers an enjoyable interface across multiple platforms.


## <a name="quick-start">🤸 Brief description </a>

**Req**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)


**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=p
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_OPENAI_API_KEY=

NEXT_PUBLIC_DATABASE_URL=

```

Replace the placeholder values with your actual OpenAI credentials. You can obtain these credentials by signing up on the [OpenAI website](https://openai.com/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.


