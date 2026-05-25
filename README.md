# Apex Advisory

A clean, responsive feedback platform built for **Apex Advisory** — a financial and strategic consulting firm dedicated to helping businesses grow, scale and make smarter decisions. Apex Advisory works with clients across a range of industries, offering expert guidance in areas such as business strategy, financial planning and operational efficiency.

The platform was built to give Apex Advisory a simple and professional way to collect customer feedback. Rather than relying on scattered reviews across WhatsApp or Google, clients can visit a dedicated page, leave a star rating and write a comment in under 30 seconds. The business owner can then log into a private dashboard to view all reviews, track the average rating and monitor how many responses have been positive — all in one place.

---

## Overview

Most small businesses have no centralized place to collect and read customer feedback. Reviews get lost on WhatsApp, Google, or never get left at all. This platform solves that by giving customers a dedicated, easy-to-use form and giving the business owner a clean dashboard to track it all in one place.

---

## Pages

| Page | File | Description |
|---|---|---|
| Customer Form | `index.html` | Customers leave their name, star rating and written feedback |
| Thank You | `thankyou.html` | Confirmation screen shown after submitting feedback |
| Business Dashboard | `dashboard.html` | Displays all reviews, average rating, total reviews and positive percentage |

---

## Built With

- **HTML5** — semantic page structure
- **Tailwind CSS** — utility-first CSS framework for styling and responsive design

---

## Features

- Clean, minimal customer feedback form
- Star rating display
- Business dashboard with key stats — average rating, total reviews, positive percentage
- Responsive design — works on mobile, tablet and desktop
- Navigation between pages using anchor links

---

## Responsive Design

The site is built mobile-first using Tailwind CSS breakpoints:

- **Mobile** — single column layout, full width form
- **Tablet** — wider card with more padding
- **Desktop** — centered content with max width container

---

## Project Structure

```
apex-feedback/
├── index.html        # Customer feedback form
├── thankyou.html     # Thank you confirmation screen
├── dashboard.html    # Business reviews dashboard
└── README.md         # Project documentation
```

---

## Getting Started

To run this project locally:

1. Clone the repository
```bash
git clone https://github.com/tuhamaina-blip/apex-feedback.git
```

2. Open the project folder
```bash
cd apex-feedback
```

3. Open `index.html` in your browser — no installs or setup needed

---

## Future Improvements

- Add a database to store real submitted reviews
- Make the star rating interactive
- Add a login page to protect the business dashboard
- Send an email notification when a new review is submitted