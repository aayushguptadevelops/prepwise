# Prepwise: AI-Driven Job Interview Preparation

Prepwise is an innovative platform designed to transform the way you prepare for job interviews. By leveraging Vapi AI Voice agents alongside Google Gemini, Prepwise provides an interactive, voice-based practice environment that simulates real interview scenarios. Whether you’re refining your answers, improving your communication skills, or seeking instant, data-driven feedback, Prepwise delivers a seamless, personalized experience powered by a modern tech stack.

## Tech Stack

- **Frontend & Backend:** Next.js
- **Authentication & Storage:** Firebase
- **Styling:** Tailwind CSS & shadcn/ui
- **AI Voice Agents:** Vapi AI
- **Generative AI:** Google Gemini
- **Validation & Schema:** Zod

## Features

- **Secure Authentication:** Email/password sign-up and sign-in via Firebase.
- **Interview Generation:** Create custom interview sessions with the help of AI voice agents and Google Gemini.
- **Real-Time Practice:** Conduct full mock interviews with voice-based interactions.
- **Instant Feedback:** Receive detailed, AI-generated feedback on performance and communication.
- **Comprehensive Dashboard:** Track and manage all your past interviews in one place.
- **Responsive Design:** Optimized for desktops, tablets, and mobile devices.

## Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/)
- [pnpm](https://pnpm.io/)

### Installation

```bash
git clone https://github.com/aayushguptadevelops/prepwise.git
cd prepwise
pnpm install
```

### Environment Variables

Create a `.env.local` file in the root directory and add your credentials:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

### Run the Development Server

```bash
pnpm dev
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to explore Prepwise.

