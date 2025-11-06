# Leaderboard

A simple, client-side leaderboard web application for tracking and displaying player names and scores.

## Overview

This is a lightweight leaderboard system that runs entirely in your browser using localStorage. No backend server, database, or authentication required. Perfect for small projects, local competitions, or demonstrations.

## Features

- **Public Leaderboard Display**: Shows the top 10 players sorted by score
- **Admin Panel**: Easy-to-use interface for adding, editing, and deleting entries
- **Real-time Updates**: Changes in the admin panel automatically reflect on the leaderboard
- **Responsive Design**: Clean, modern UI with purple gradient styling
- **Rank Highlights**: Special colors for top 3 positions (gold, silver, bronze)
- **No Dependencies**: Self-contained HTML files with inline CSS and JavaScript

## Usage

### Running the Application

**Development Mode:**
```bash
npm install
npm start
```
This starts a local server at `http://localhost:8080`

**Production:** Deploy the HTML files to any static file hosting service (GitHub Pages, Netlify, Vercel, etc.)

**Local Use:** Simply open `index.html` in your browser (no server needed)

### Using the Leaderboard

1. Open `index.html` to view the leaderboard
2. Open `admin.html` to manage entries
   - Add new players and scores
   - Edit existing entries
   - Delete entries

## Technical Details

- **Storage**: Browser localStorage (data persists across sessions)
- **Data Format**: JSON array stored under the key `'leaderboard'`
- **Client-Side Only**: No backend or database required
- **Limitations**:
  - Data is stored locally per browser/device
  - Clearing browser data will delete all entries
  - Storage typically limited to 5-10MB

## Files

- `index.html` - Main leaderboard display (public view)
- `admin.html` - Administration panel for managing entries
- `CLAUDE.md` - Technical documentation for AI assistants
- `README.md` - This file

## Security Note

This application has no authentication or authorization. The admin panel is accessible to anyone who knows the URL. It's designed for trusted environments and learning purposes, not production systems requiring security.
