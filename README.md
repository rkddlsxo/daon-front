# Daon Frontend Client

The web client for the **Daon** volunteer platform. Built with **Next.js (App Router)** and **Tailwind CSS** for a modern, responsive user interface.

## 🛠 Tech Stack

- **Framework**: [Next.js 14+](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Language**: TypeScript
- **State Management**: React Hooks

## 📂 Key Features

- **Volunteer Hub**: Browse (`/volunteer/list`) and create (`/volunteer/create`) volunteer opportunities.
- **Community Reviews**: Read and write reviews for volunteer activities (`/reviews`).
- **User Authentication**: Login and Sign-up pages (`/login`).
- **Responsive Design**: Optimized for both desktop and mobile views.

## 🚀 Getting Started

### 1. Installation

```bash
# Clone the repository
git clone <your-repo-url>

# Navigate to the frontend directory
cd daon-front

# Install dependencies
npm install
```

2. Environment Configuration
Create a .env.local file in the root directory to connect to your backend:

```bash
# Backend API URL

NEXT_PUBLIC_API_URL=http://localhost:8080
```

3. Running the Development Server
```bash
npm run dev
```

### 📁 Project Structure
src/app: Application routes and pages (Next.js App Router).

volunteer/: Pages related to volunteer posts.

reviews/: Pages for reading/writing reviews.

login/: Authentication pages.

src/lib: Utility functions and API wrappers.
Open http://localhost:3000 with your browser to see the result.
