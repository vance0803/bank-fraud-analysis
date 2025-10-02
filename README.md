# Bank Fraud Analysis Website

A modern web application for bank fraud analysis, prevention, alerting, and security.  
Built with HTML, CSS, and Supabase for user authentication.

## Features

- **User Registration & Login** (Supabase backend)
- **Responsive Design**
- **Fraud Prevention Information**
- **Email Alerts (concept)**
- **Secure Data Handling**

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vance0803/bank-fraud-analysis.git
   cd bank-fraud-analysis
   ```

2. **Open `index.html` in your browser.**

3. **Supabase Setup:**
   - Add your Supabase project URL and anon key in `login.html` and `about.html` JavaScript sections.

## File Structure

- `index.html` — Landing page
- `login.html` — User login
- `about.html` — User registration (sign up)
- `welcome.html` — Post-login welcome (optional)
- `style.css` — (if separated) Styles

## Technologies Used

- HTML5
- CSS3
- [Supabase](https://supabase.com/) (for authentication & database)
- JavaScript

## How Authentication Works

- **Sign Up:** User details are saved to Supabase `users` table.
- **Login:** Credentials are checked against Supabase.

> **Note:** For production, always hash passwords before storing.

## License

MIT

## Author

[vance0803](https://github.com/vance0803)
