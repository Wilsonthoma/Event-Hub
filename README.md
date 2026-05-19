
# EventHub - Event Management & Ticketing System

A modern event management and ticketing system built with Django.

## Features

- 🔐 User Authentication (Login/Register/Password Reset)
- 🎪 Create & Manage Events
- 🎟️ Book Tickets with QR Codes
- 👤 User & Organizer Dashboards
- 💳 Payment Ready (M-Pesa/Stripe)
- 📱 Fully Responsive
- ⭐ Reviews & Ratings

## Tech Stack

- Django 5.1.4
- Tailwind CSS
- SQLite/PostgreSQL
- django-qrcode

## Full Project Tree Structure

Event-Hub/
│
├── manage.py
├── requirements.txt
├── .env.example
├── .gitignore
│
├── event_management/           # Project config
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── events/                     # Main application
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── signals.py
│   ├── context_processors.py
│   │
│   ├── migrations/
│   │   ├── __init__.py
│   │   └── 0001_initial.py
│   │
│   ├── templates/              # All HTML templates (32 files)
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── contact.html
│   │   ├── notifications.html
│   │   │
│   │   ├── admin/
│   │   │   ├── dashboard.html
│   │   │   ├── user_management.html
│   │   │   ├── event_approval.html
│   │   │   └── reports.html
│   │   │
│   │   ├── bookings/
│   │   │   ├── booking_confirmation.html
│   │   │   ├── checkout.html
│   │   │   ├── payment_success.html
│   │   │   └── payment_cancel.html
│   │   │
│   │   ├── dashboard/
│   │   │   ├── dashboard.html
│   │   │   ├── profile.html
│   │   │   ├── settings.html
│   │   │   ├── change_password.html
│   │   │   └── delete_account.html
│   │   │
│   │   ├── events/
│   │   │   ├── event_list.html
│   │   │   ├── event_detail.html
│   │   │   ├── create_event.html
│   │   │   ├── my_events.html
│   │   │   ├── my_bookings.html
│   │   │   ├── event_analytics.html
│   │   │   ├── attendees.html
│   │   │   └── checkin.html
│   │   │
│   │   ├── pages/
│   │   │   ├── about.html
│   │   │   ├── faq.html
│   │   │   ├── help.html
│   │   │   ├── privacy.html
│   │   │   ├── terms.html
│   │   │   ├── reviews.html
│   │   │   └── stories.html
│   │   │
│   │   ├── registration/
│   │   │   ├── login.html
│   │   │   ├── register.html
│   │   │   ├── email_verify.html
│   │   │   └── reset_password.html
│   │   │
│   │   ├── sections/
│   │   │   ├── hero.html
│   │   │   ├── featured_events.html
│   │   │   ├── categories.html
│   │   │   ├── how_it_works.html
│   │   │   ├── stats.html
│   │   │   ├── testimonials.html
│   │   │   └── newsletter.html
│   │   │
│   │   ├── components/
│   │   │   ├── navbar.html
│   │   │   └── footer.html
│   │   │
│   │   └── search_results.html
│   │
│   └── static/                  # CSS files (18 files)
│       └── css/
│           ├── main.css
│           ├── variables.css
│           ├── reset.css
│           ├── layout.css
│           ├── typography.css
│           ├── buttons.css
│           ├── forms.css
│           ├── cards.css
│           ├── navbar.css
│           ├── footer.css
│           ├── hero.css
│           ├── carousel.css
│           ├── messages.css
│           ├── auth.css
│           ├── pages.css
│           ├── animations.css
│           ├── responsive.css
│           └── utilities.css
│
└── static/                     # Global static files
    └── images/
        ├── .gitkeep
        ├── favicon.svg
        ├── logo-placeholder.svg
        ├── default-avatar.svg
        └── default-event.svg




## Environment Variables (.env)

SECRET_KEY=your-secret-key
DEBUG=True
EMAIL_HOST_USER=your@email.com
EMAIL_HOST_PASSWORD=your-password


## Key URLs

| Page | URL |
|------|-----|
| Home | `/` |
| Events | `/events/` |
| Event Detail | `/events/<slug>/` |
| Dashboard | `/dashboard/` |
| My Bookings | `/dashboard/bookings/` |
| My Events | `/dashboard/events/` |
| Login | `/login/` |
| Register | `/register/` |
| Admin | `/admin/` |

## Default Admin Access


python manage.py createsuperuser
# Then visit /admin/

