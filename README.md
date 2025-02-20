# Full-Stack Coding Challenge

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

# Task Management Application

A modern task management application built with React, TypeScript, and Supabase. Features include user authentication, task creation, editing, completion tracking, and real-time updates.

## Database Setup

### Prerequisites
- Supabase account
- Access to Supabase project dashboard

### Environment Variables
Create a `.env` file in the root directory with the following variables:
```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Database Migrations
The project uses Supabase migrations for database schema management. The migrations are located in `supabase/migrations/` directory.

To apply migrations:
1. Install Supabase CLI
2. Link your project
3. Run migrations:
```bash
supabase migration up
```

## Running the Application

### Frontend Development
1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Production Build
```bash
npm run build
npm run preview
```

## Testing

### Manual Testing Checklist
- User Authentication
  - [ ] Registration with email and password
  - [ ] Login with registered credentials
  - [ ] Sign out functionality
  - [ ] Protected routes

- Task Management
  - [ ] Create new tasks
  - [ ] Edit existing tasks
  - [ ] Mark tasks as complete/incomplete
  - [ ] Delete tasks
  - [ ] Real-time updates

### Security Testing
- [ ] Authentication flow
- [ ] Protected routes
- [ ] Row Level Security policies
- [ ] API endpoint security

## Technical Stack

### Frontend
- React 18
- TypeScript
- Vite
- TailwindCSS
- React Router DOM
- Lucide React (icons)
- React Hot Toast (notifications)

### Backend
- Supabase (Backend as a Service)
  - PostgreSQL database
  - Authentication
  - Row Level Security
  - Real-time subscriptions

## Salary Expectations
- Range: 25$ TO 30$ per hour

*Note: Salary ranges may vary based on location, company size, and specific requirements.*
