# Topstar Legacy Learning Centre

A modern school website built with React, Vite, and Tailwind CSS.

## Getting Started

1.  **Install dependencies**:
    ```bash
    npm install
    ```

2.  **Start development server**:
    ```bash
    npm run dev
    ```

## Changing Images

You can change images in two ways:

### 1. Using Web URLs
Find the `<img>` tag in the relevant file (e.g., `src/pages/Home.tsx`) and replace the `src` URL.

### 2. Using Local Files
1.  Place your images in the `public/images/` folder.
2.  Reference them in your code using an absolute path:
    ```tsx
    <img src="/images/your-image.png" alt="Description" />
    ```

## Project Structure

- `src/`: React source code.
- `public/`: Static assets (images, icons, etc.).
- `firebase-blueprint.json`: Firestore data structure.
- `firestore.rules`: Security rules for Firestore.
