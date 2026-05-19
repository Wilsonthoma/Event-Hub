# EventHub - Frontend Only

A modern, responsive event management system frontend with glassmorphic UI design. This is the complete frontend template with 44 HTML pages and 18 CSS modules ready to use with any backend.

## Description

EventHub Frontend provides a complete user interface for event management including user dashboards, event listings, booking flows, authentication pages, and admin panels. Built with modern CSS and responsive design patterns.

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styles + Glassmorphic effects
- **Django Templates** - Template inheritance system

## What to Install

For frontend only (static HTML/CSS)

# No installation needed! Just clone and open
git clone https://github.com/Wilsonthoma/Event-Hub.git
cd Event-Hub

# View any HTML file directly in browser
open events/templates/index.html

## Quick Start


git clone https://github.com/Wilsonthoma/Event-Hub.git
cd Event-Hub
python -m http.server --directory events/templates/


## All Pages (44 Files)

**Root:**
- index.html
- base.html
- contact.html
- notifications.html
- search_results.html

**Registration (4):**
- login.html
- register.html
- email_verify.html
- reset_password.html

**Events (8):**
- event_list.html
- event_detail.html
- create_event.html
- my_events.html
- my_bookings.html
- event_analytics.html
- attendees.html
- checkin.html

**Dashboard (5):**
- dashboard.html
- profile.html
- settings.html
- change_password.html
- delete_account.html

**Bookings (4):**
- booking_confirmation.html
- checkout.html
- payment_success.html
- payment_cancel.html

**Admin (4):**
- dashboard.html
- user_management.html
- event_approval.html
- reports.html

**Pages (7):**
- about.html
- faq.html
- help.html
- privacy.html
- terms.html
- reviews.html
- stories.html

**Sections (7):**
- hero.html
- featured_events.html
- categories.html
- how_it_works.html
- stats.html
- testimonials.html
- newsletter.html

**Components (2):**
- navbar.html
- footer.html

## CSS Files (18)

main.css, variables.css, reset.css, layout.css, typography.css, buttons.css, forms.css, cards.css, navbar.css, footer.css, hero.css, carousel.css, messages.css, auth.css, pages.css, animations.css, responsive.css, utilities.css

## Project Structure

```Event-Hub/
│
├── manage.py
├── requirements.txt
├── .env.example
├── .gitignore
│
├── event_management/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── asgi.py
│ └── wsgi.py
│
├── events/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── forms.py
│ ├── signals.py
│ ├── context_processors.py
│ │
│ ├── migrations/
│ │ ├── init.py
│ │ └── 0001_initial.py
│ │
│ ├── templates/
│ │ ├── base.html
│ │ ├── index.html
│ │ ├── contact.html
│ │ ├── notifications.html
│ │ ├── search_results.html
│ │ │
│ │ ├── admin/
│ │ │ ├── admin_dashboard.html
│ │ │ ├── user_management.html
│ │ │ ├── event_approval.html
│ │ │ └── reports.html
│ │ │
│ │ ├── bookings/
│ │ │ ├── booking_confirmation.html
│ │ │ ├── checkout.html
│ │ │ ├── payment_success.html
│ │ │ └── payment_cancel.html
│ │ │
│ │ ├── dashboard/
│ │ │ ├── dashboard.html
│ │ │ ├── profile.html
│ │ │ ├── settings.html
│ │ │ ├── change_password.html
│ │ │ └── delete_account.html
│ │ │
│ │ ├── events/
│ │ │ ├── event_list.html
│ │ │ ├── event_detail.html
│ │ │ ├── create_event.html
│ │ │ ├── my_events.html
│ │ │ ├── my_bookings.html
│ │ │ ├── event_analytics.html
│ │ │ ├── attendees.html
│ │ │ └── checkin.html
│ │ │
│ │ ├── pages/
│ │ │ ├── about.html
│ │ │ ├── faq.html
│ │ │ ├── help.html
│ │ │ ├── privacy.html
│ │ │ ├── terms.html
│ │ │ ├── reviews.html
│ │ │ └── stories.html
│ │ │
│ │ ├── registration/
│ │ │ ├── login.html
│ │ │ ├── register.html
│ │ │ ├── email_verify.html
│ │ │ └── reset_password.html
│ │ │
│ │ ├── sections/
│ │ │ ├── hero.html
│ │ │ ├── featured_events.html
│ │ │ ├── categories.html
│ │ │ ├── how_it_works.html
│ │ │ ├── stats.html
│ │ │ ├── testimonials.html
│ │ │ └── newsletter.html
│ │ │
│ │ └── components/
│ │ ├── navbar.html
│ │ └── footer.html
│ │
│ └── static/
│ └── css/
│ ├── main.css
│ ├── variables.css
│ ├── reset.css
│ ├── layout.css
│ ├── typography.css
│ ├── buttons.css
│ ├── forms.css
│ ├── cards.css
│ ├── navbar.css
│ ├── footer.css
│ ├── hero.css
│ ├── carousel.css
│ ├── messages.css
│ ├── auth.css
│ ├── pages.css
│ ├── animations.css
│ ├── responsive.css
│ └── utilities.css
│
└── static/
└── images/
├── favicon.svg
├── logo-placeholder.svg
├── default-avatar.svg
└── default-eent.svg

```
