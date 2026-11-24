# Traxa Demo

**Live demo:** [traxa-employment-system.vercel.app](https://traxa-employment-system.vercel.app)

Traxa is an employee and work management application built to help teams coordinate people, attendance, projects, tasks, leave, and daily reports.

## Demo architecture

- **Frontend:** Next.js, hosted on Vercel
- **Backend API:** FastAPI, hosted on Render
- **Database:** PostgreSQL on Supabase

The frontend communicates with the API through a server-side proxy. Database credentials and signing secrets stay on the hosting services and are not included in this repository.

## Notes

This is a portfolio demo. The Render free service may take a little time to wake up after inactivity. Please use synthetic demo data only; this deployment is separate from production data.
