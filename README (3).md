# LimoRome

LimoRome is a luxury chauffeur booking and fleet management platform built with Next.js, TypeScript, Firebase, Stripe, PayPal, and NCCGEST. The platform includes dynamic pricing, multilingual support, secure booking management, automated refunds, admin dashboards, and real-time transportation workflows.

---

# Features

## Customer Features

### Luxury Transfer Booking
- Airport transfers
- Point-to-point rides
- Hourly chauffeur services
- Round trips
- Multi-stop bookings

### Smart Route System
- Real-time distance calculation
- Route optimization
- Duration estimation
- Google Maps integration
- OSRM routing support

### Dynamic Pricing Engine
- Distance-based pricing
- Hourly pricing
- Vehicle-based pricing
- VAT calculations
- Multi-stop pricing
- Server-side price validation

### Vehicle Categories
- Sedan
- Mercedes V-Class
- Mercedes Vito
- Mercedes S-Class

### Booking Management
- Secure booking editing
- Booking cancellation
- Automatic refunds
- Booking history
- Guest & authenticated flows

### Multilingual Support
- Localized routes
- International formatting
- Multi-language booking experience

---

# Admin Dashboard

The platform includes a complete admin management system for handling bookings, customers, pricing, and payments.

## Admin Features

### Booking Management
- View all bookings
- Search & filter bookings
- Edit booking details
- Cancel bookings
- Track booking statuses
- View refund history

### Payment Management
- Stripe payment tracking
- PayPal payment tracking
- Refund monitoring
- Failed payment handling

### Customer Management
- Customer history
- Guest booking tracking
- Registered user management

### Service Management
- Fleet management
- Vehicle pricing control
- Route pricing adjustments
- Service synchronization

### Dispatch Integration
- NCCGEST synchronization
- External service updates
- Chauffeur dispatch management

### Email Management
- Booking confirmations
- Edit notifications
- Cancellation emails
- Refund emails

---

# Payment System

## Stripe Integration
- Stripe Checkout Sessions
- Secure payment workflows
- Additional payment collection
- Partial refunds
- Webhook handling

## PayPal Integration
- Order creation
- Payment capture
- Refund processing
- Multi-capture support

---

# Security Features

- Secure edit tokens
- Secure cancellation tokens
- Server-side validation
- Protected API routes
- Duplicate booking prevention
- Webhook verification
- Firestore validation

---

# Tech Stack

| Category | Technology |
|---|---|
| Frontend | Next.js, React, TypeScript |
| Styling | Tailwind CSS |
| Backend | Node.js, Next.js API Routes |
| Database | Firebase Firestore |
| Cache | Redis |
| Authentication | NextAuth.js |
| Payments | Stripe, PayPal |
| Routing | OSRM, Google APIs |
| Email Service | Nodemailer |
| Deployment | Vercel |

---

# Project Structure

```bash
/app
/components
/lib
/utils
/hooks
/styles
/public
/firebase
/api
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/limorome.git
cd limorome
```

## Install Dependencies

```bash
npm install
```

## Setup Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_BASE_URL=
NEXTAUTH_URL=
NEXTAUTH_SECRET=

GOOGLE_MAPS_API_KEY=

STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

PAYPAL_CLIENT_ID=
PAYPAL_CLIENT_SECRET=

EMAIL_USER=
EMAIL_PASS=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=

REDIS_URL=

NCCGEST_API_URL=
NCCGEST_API_KEY=
```

---

# Run Development Server

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

---

# Production Build

```bash
npm run build
npm start
```

---

# Main System Modules

## Booking System
Handles:
- Booking creation
- Booking editing
- Cancellation workflows
- Price recalculations

## Payment System
Handles:
- Stripe payments
- PayPal payments
- Refund automation
- Webhook processing

## Admin System
Handles:
- Booking management
- Customer management
- Payment monitoring
- Dispatch synchronization

## Dispatch System
Handles:
- NCCGEST service creation
- Service updates
- Service cancellation

---

# API Features

- Secure booking APIs
- Payment APIs
- Admin APIs
- Webhook handlers
- Refund workflows
- Booking synchronization

---

# Email System

Automated emails include:
- Booking confirmations
- Booking updates
- Refund notifications
- Cancellation emails

### Features
- HTML email templates
- PDF booking attachments
- Responsive email layouts

---

# Future Improvements

- Driver mobile application
- Live chauffeur tracking
- AI route optimization
- Analytics dashboard
- Loyalty system
- Invoice automation
- Multi-company support

---

# Deployment

Recommended platforms:
- Vercel
- Firebase
- Node.js VPS hosting

---

# License

This project is licensed under the MIT License.

---

# Author

Developed by Jalil Khan
