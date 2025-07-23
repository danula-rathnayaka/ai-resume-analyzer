# 🧠 AI Resume Analyzer

An AI-powered web application that analyzes resumes and matches them to job descriptions using advanced AI models. Built using React, TypeScript, Puter.js, and Tailwind CSS, this tool offers custom feedback, ATS scores, and seamless resume management in a modern and responsive UI.

## Introduction

The **AI Resume Analyzer** helps users evaluate how well their resumes match a specific job description. It provides an ATS (Applicant Tracking System) score, tailored suggestions, and AI-based feedback. Resumes are uploaded, stored securely, and analyzed directly in the browser—no backend setup required.

## Tech Stack

- **React** – Component-based UI library  
- **React Router v7** – Routing and navigation  
- **TypeScript** – Static type-checking for JavaScript  
- **Tailwind CSS** – Utility-first CSS framework  
- **Zustand** – Lightweight state management  
- **Vite** – Fast development server and build tool  
- **Puter.js** – Client-side SDK for serverless auth, storage, and AI APIs  

## Features

- **Authentication** – Handle user sign-in directly in the browser using Puter.js  
- **Resume Upload** – Upload and store resumes with secure cloud access  
- **AI Matching** – Match resumes to job listings with tailored ATS scoring and feedback  
- **Reusable UI Components** – Clean, modular code structure with reusable components  
- **Responsive Design** – Fully responsive layout for desktop, tablet, and mobile  
- **Modern UI/UX** – Built with Tailwind CSS and `shadcn/ui` for sleek visuals  
- **Code Reusability** – Designed with scalability and reusability in mind

## Quick Start

### Prerequisites

Make sure the following are installed on your machine:

- Git  
- Node.js (>= 16)  
- npm  

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```
