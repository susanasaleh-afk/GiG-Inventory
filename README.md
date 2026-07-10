# GIG Inventory Management System

A web-based inventory management system for GIG (Gaming Innovation Group) to track furniture, equipment, and appliances across multiple office locations.

## Features

- ✅ Add, edit, and delete inventory items
- ✅ Filter by category, location, and disposition
- ✅ Track item status: Available, Sale, or Gift
- ✅ Export inventory to CSV
- ✅ Real-time sync with Google Sheet backend
- ✅ Dynamic categories and locations from Config sheet

## Setup

### Google Sheet Requirements

1. Create two sheets in your Google Sheet:
   - **Inventory**: Contains all inventory items
   - **Config**: Contains categories and locations

2. Google Apps Script deployment URL is embedded in `index.html`

### Deploy to Vercel

1. Push this repository to GitHub
2. Go to vercel.com → Import → Select repository
3. Deploy

## How It Works

- **Frontend**: Single HTML file with vanilla JavaScript
- **Backend**: Google Apps Script connected to your Google Sheet
- **API**: RESTful endpoints via Apps Script `doGet()` and `doPost()` functions

## File Structure

```
.
├── index.html      # Main app (with embedded deployment URL)
├── vercel.json     # Vercel config
└── README.md       # This file
```

## Built With

- Vanilla HTML/CSS/JavaScript (no dependencies)
- Google Apps Script
- Vercel (hosting)
