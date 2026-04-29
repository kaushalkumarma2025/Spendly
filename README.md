# Spendly - Personal Expense Tracker

A clean, modern web application for tracking personal expenses built with Flask.

## Features

- User registration and authentication (in progress)
- Add, edit, and delete expenses
- Categorize expenses (Bills, Food, Health, Transport, etc.)
- View spending patterns and summaries
- Filter by date range
- Responsive design

## Tech Stack

- **Backend:** Flask (Python 3.11+)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (via Flask's built-in support)

## Prerequisites

- Python 3.11 or higher
- pip (Python package installer)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Spendly.git
   cd Spendly
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

1. **Start the Flask development server:**
   ```bash
   python app.py
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:5001
   ```

## Project Structure

```
expense-tracker/
├── app.py                 # Main Flask application with routes
├── requirements.txt       # Python dependencies
├── database/             # Database files (created automatically)
├── static/
│   ├── css/
│   │   ├── style.css    # Global styles
│   │   └── landing.css  # Landing page specific styles
│   └── js/
│       └── main.js      # Client-side JavaScript
└── templates/
    ├── base.html        # Base template with navbar and footer
    ├── landing.html     # Landing page with hero section
    ├── login.html       # Login page
    ├── register.html    # Registration page
    ├── terms.html       # Terms and Conditions page
    └── privacy.html     # Privacy Policy page
```

## Current Status

- ✅ Landing page with modern hero design
- ✅ Terms and Conditions page
- ✅ Privacy Policy page
- ✅ Video modal (placeholder)
- ⏳ User authentication (in progress)
- ⏳ Expense management features (next steps)

## Development Notes

- The app runs in debug mode during development (auto-reload enabled).
- Uses SQLite for data persistence (no setup required).
- All templates extend `base.html` for consistent layout.
- Custom styles for the landing page are in `static/css/landing.css`.

## Future Enhancements

- Full user authentication with Flask-Login
- Expense CRUD operations with database models
- Dashboard with charts and statistics
- Category management
- Export data to CSV/PDF
- Mobile responsive improvements

## License

MIT

---

**Built with Flask** 🚀
