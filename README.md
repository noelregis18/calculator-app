# Modern Calculator App

![Modern Calculator](https://img.shields.io/badge/Modern-Calculator-blue)
![Next.js](https://img.shields.io/badge/Next.js-14-black)
![React](https://img.shields.io/badge/React-18-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-38B2AC)

## Overview

A sleek, modern calculator web application built with Next.js and React. This project was developed as part of the InternPe Week 1 assignment, featuring a responsive design with a beautiful gradient UI and dark mode support.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Additional Functions**: Percentage calculation, positive/negative toggle, decimal support
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Gradient borders, clean interface with dark mode support
- **Real-time Display**: Shows current calculation and previous operation
- **Error Handling**: Prevents division by zero and handles invalid inputs

## Technologies Used

- **Next.js**: React framework for production-grade applications
- **React**: JavaScript library for building user interfaces
- **TypeScript**: For type-safe code and better developer experience
- **TailwindCSS**: Utility-first CSS framework for styling
- **React Hooks**: For state management (useState)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm, yarn, pnpm, or bun package manager

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd calculator-app
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. Run the development server
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the calculator app.

## Usage

- **Basic Calculations**: Click on number buttons followed by operation buttons
- **Clear Display**: Press 'C' to clear all calculations
- **Delete Last Digit**: Press '⌫' to remove the last entered digit
- **Percentage**: Press '%' to convert the current number to a percentage
- **Positive/Negative Toggle**: Press '+/-' to change the sign of the current number
- **Decimal Point**: Press '.' to add a decimal point
- **Calculate Result**: Press '=' to perform the calculation

## Project Structure

```
calculator-app/
├── public/            # Static assets
├── src/
│   ├── app/           # Next.js app directory
│   │   ├── layout.tsx # Root layout component
│   │   └── page.tsx   # Home page component
│   └── components/    # React components
│       └── Calculator.tsx # Main calculator component
├── package.json       # Project dependencies
└── README.md         # Project documentation
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## Author

Noel Regis - Week 1 InternPe Project
