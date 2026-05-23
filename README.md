# Customer Management System

A group project for Information Management 2 focused on managing customer records, authentication, user rights, and customer-related business workflows for Hope, Inc.

## Preview

![Customer Management System login and rights screen](docs/Screenshots/LoginRights.png)

## Project Overview

The Customer Management System provides a secure web-based platform for handling customer information, account access, and business records. The project uses Supabase for authentication and database services, with a React frontend built for everyday customer management tasks.

## Features

- Email and Google authentication with Supabase
- User account activation and access rights handling
- Customer creation, editing, and deactivation workflows
- Customer record views and status tracking
- Protected routes for authenticated users
- Audit and rights-related documentation
- Responsive React interface for desktop workflows

## Tech Stack

- React
- Vite
- Tailwind CSS
- Supabase
- JavaScript
- Vitest

## My Role

This was a group project. My role was **Frontend Developer**, contributing to the user interface and customer management experience.

## Team Members

- Chynna Cardona (M1) - Project Lead / Full-Stack Developer
- Jorus Junio (M2) - Frontend Developer
- Alexis Castro (M3) - Database Engineer
- John Patrick Hawac (M4) - Rights & Auth Specialist
- Lourd Allen Amante (M5) - QA & Documentation

## Screenshots

### Customer Workflow

![Add customer screen](docs/Screenshots/AddCustomer.png)

![Edit customer screen](docs/Screenshots/EditCustomer.png)

![Customer deactivation screen](docs/Screenshots/Deactivation.png)

### Authentication and Access

![Google authentication screen](docs/Screenshots/GoogleAuth.png)

![Login rights screen](docs/Screenshots/LoginRights.png)

## Local Setup

Clone the repository, install dependencies, and run the Vite development server.

```bash
npm install
npm run dev
```

Create a `.env` file in the project root:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Build

```bash
npm run build
```
