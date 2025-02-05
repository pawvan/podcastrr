
---

# Podcastr

Podcastr is a modern podcast platform built with Next.js, React, and TailwindCSS. It provides a seamless experience for users to explore, upload, and manage podcasts. The app integrates cutting-edge technologies such as OpenAI for content generation, Clerk for authentication, and Radix UI for accessible and customizable UI components.

## Features

- **User Authentication**: Secure sign-up and login with Clerk.
- **Podcast Streaming**: Stream and manage podcasts with a responsive and modern interface.
- **File Upload**: Upload podcast episodes using `react-dropzone` with drag-and-drop functionality.
- **AI-Powered**: Use OpenAI to generate podcast descriptions, recommendations, and more.
- **Radix UI**: Accessible and customizable UI components, including dialogs, toasts, select menus, and progress bars.
- **Dynamic Carousel**: Embla Carousel with autoplay functionality for enhanced media presentation.

## Tech Stack

- **Frontend**: Next.js (v14), React (v18), TailwindCSS
- **UI Components**: Radix UI
- **Authentication**: Clerk
- **API Integration**: OpenAI, Convex
- **File Upload**: React Dropzone
- **Form Management**: React Hook Form, Zod (for validation)
- **State Management**: Class Variance Authority, clsx
- **Animations**: TailwindCSS Animate

## Installation

To run Podcastr locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/podcastrr/podcastr.git
   cd podcastr
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Start the development server:
   ```bash
   yarn dev
   ```

   Now the app will be available at `http://localhost:3000`.

## Available Scripts

In the project directory, you can run:

- **`dev`**: Starts the development server
  ```bash
  yarn dev
  ```

- **`build`**: Builds the app for production
  ```bash
  yarn build
  ```

- **`start`**: Starts the app in production mode
  ```bash
  yarn start
  ```

- **`lint`**: Lints the project with ESLint
  ```bash
  yarn lint
  ```

## Contributing

We welcome contributions! Please open an issue or submit a pull request to help improve Podcastr.

## License

This project is licensed under the MIT License.

---
