# Career Craft AI

Welcome to **Career Craft AI**, an innovative career development platform built to empower individuals with personalized guidance and AI-driven tools. Our mission is to simplify, accelerate, and enhance your career journey by providing smarter recommendations and resources tailored to your unique goals and aspirations .

## Table of Contents

1. [Introduction](#introduction)
2. [Preview](#Preview)
3. [Problem Statements & Solutions](#-problem-statements--solutions)
4. [Features](#-features)
5. [Promptrepo](#Promptrepo)
6. [Tech Stack & Tools](#-tech-stack--tools)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [License](#license)
11. [Contact](#contact)

## Introduction

**Career Craft AI** is a powerful, AI-driven platform that transforms how individuals approach career growth. Whether you're a student, a professional, or a creative like a photographer or designer looking to showcase your work, Career Craft AI’s all-in-one suite of tools—including an AI Career Advisor, personalized Roadmap for Success, AI-powered Interview Prep bot, and Portfolio Website Generator—empowers you to make informed decisions, create a stunning portfolio in seconds, and ace your career goals with ease.

## Preview

[![Imgur](https://imgur.com/KV7fQ5S.gif)](https://career-craft-ai.vercel.app/)

[Live Demo](https://drive.google.com/file/d/1wKXjPixlj3xqicU3jSDNli_BhRgGd0ta/view?usp=sharing)


## 🚀 Problem Statements & Solutions

### 1. Lack of Career Guidance

**Problem:** When starting a career, we often seek guidance from experienced professionals who can offer insights and recommendations. However, finding a knowledgeable mentor is not always easy.

**Solution:** Career Craft AI offers an **AI Career Advisor** that provides personalized career recommendations based on your skills, interests, and market trends, helping you make informed decisions about your career path.

### 2. Difficulty in Building a Portfolio

**Problem:** A professional portfolio acts as proof of work and increases the chances of career opportunities. However, creating a well-structured portfolio from scratch can be time-consuming and challenging.

**Solution:** Our **AI-Powered Portfolio Generator** allows users to instantly generate a professional portfolio website with just a single prompt, making it easier than ever to showcase work and achievements.

### 3. No Clear Roadmap for Skill Development

**Problem:** When entering a new field or learning a new skill, we often struggle to find a well-structured, step-by-step roadmap that outlines what to learn and how to progress.

**Solution:** Career Craft AI provides a **Roadmap for Success**, a customized learning and skill development plan that guides users through acquiring the necessary skills and certifications for their desired career.

### 4. Ineffective Interview Preparation

**Problem:** Preparing for an interview requires practice, role-specific questions, and constructive feedback, which are not always readily available.

**Solution:** Our **AI Interview Prep Chatbot** simulates real interview scenarios, asks tailored questions based on the role, and provides instant feedback, helping users refine their responses and boost confidence.

## 🔥 Features

- **AI Career Advisor** – Get personalized career recommendations tailored to your skills and interests.
- **Roadmap for Success** – Follow a structured plan to develop the right skills for your chosen career.
- **AI-Powered Portfolio Generator** – Instantly create a professional portfolio website.
- **AI Interview Prep Chatbot** – Practice for interviews with real-time AI feedback and role-specific questions.

## Promptrepo

We have used **Promptrepo** to extract the user's details for generating portfolio

[Promptrepo data set](https://docs.google.com/spreadsheets/d/1WNmaCnpeqgD8aNMgVALb3MiVv2MbQvJFx7twd4-uy-A/edit?usp=sharing)

## 🛠 Tech Stack & Tools
- **Frontend:** Next.js, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB  
- **AI & NLP:**  Promptrepo, Mistral AI, Gemini AI, Google Cloud Speech-to-Text
- **Authentication:** Clerk Authentication - Google, LinkedIn, Email
- **Deployment:** Vercel (Frontend), Vercel (Backend)  
- **Other Tools:** Framer Motion (UI Animations), Aceternity UI, Magic UI, Shadcn

## 🌍 Domain  
Career Craft AI is a **Full-Stack AI Development** project, integrating AI-driven career guidance with modern web technologies. 

## 🚀 Live Deployment
Frontend Deployed Link: https://career-craft-ai.vercel.app/

## 📄License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Installation

To get started with **Career Craft AI**, follow these steps:

### Prerequisites
- Node.js (v14 or later)
- npm (or yarn)

### Steps to Install

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Yagna123k/CAREER-CRAFT-AI.git
   cd CAREER-CRAFT-AI
   ```

2. Install the dependencies:

   ```bash
   cd client
   npm install
   ```
   ```bash
   cd server
   npm install
   ```

3. Set up environment variables for API keys, database configurations, etc.
   ```
   cd server
   // ceate .env file
   
   PORT = 
   MongoURI =
   CLIENT_URL=
   ```
   ```
   cd client
   // ceate .env.local file
   
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   MISTRAL_API_KEY=
   NEXT_PUBLIC_GEMINI_API_KEY=
   NEXT_PUBLIC_BACKEND_URL=
   ```

5. Run the app locally:

   ```bash
   cd client
   npm run dev
   ```
   ```bash
   cd server
   npm run dev
   ```

6. Visit `http://localhost:3000` in your browser to explore the platform.

## Usage

Once installed, you can access the following features from the **Career Craft AI** dashboard:

1. **AI Career Advisor** – Complete a brief survey about your skills and interests to receive personalized career recommendations.
2. **Roadmap for Success** – View your tailored career roadmap and access resources to build your skills.
3. **Portfolio Generator** – Use the easy-to-use interface to create and customize your portfolio website.
4. **AI Interview Prep** – Practice interview questions and receive feedback on your responses.

## Contributing

We welcome contributions to **Career Craft AI**! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your fork (`git push origin feature/your-feature`).
5. Open a Pull Request.

For any bug reports, feature requests, or suggestions, please open an issue in the repository.

## Contact

For any questions or inquiries, feel free to reach out to us at:

- Email: kusumanchi.yagna@kalvium.community
- GitHub: https://github.com/Yagna123k/CAREER-CRAFT-AI
- Figma: https://www.figma.com/design/Vtjpu6WFRcNrWBlCgzRkqx/Career-craft-AI?node-id=0-1&t=6DTPj6AIhhXD0ulr-1a
- Website: [Career Craft AI](https://career-craft-ai.vercel.app/)
