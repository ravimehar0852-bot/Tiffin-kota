# TiffinKota Product Requirements Document

## Project Overview
TiffinKota is a specialized tiffin/meal booking platform designed for the Kota region, connecting students and professionals with local tiffin service providers. It features distinct interfaces for Customers, Tiffin Service Owners, and Admins.

## Screen Inventory

### Phase 1: Landing & Auth
1. **Landing Page (Mobile/Web):** Hero section with animations, 'Order Tiffin' vs 'Register Service' CTAs, popular providers, and how it works.
2. **Unified Auth Screen:** Multi-tab login for Customer and Owner (Email, Phone/OTP, Google).

### Phase 2: Customer Experience
3. **Customer Dashboard:** Search bar, category filters (Veg/Non-Veg, Price, Rating), and nearby kitchen listings.
4. **Tiffin Service Detail:** Daily menu, monthly plan selection, shop photos, and reviews.
5. **Checkout & Payment:** Address selection, plan duration, and simulated payment integration (Razorpay/UPI UI).
6. **Live Order Status:** Real-time tracking of the current meal delivery with chat link.
7. **Customer Profile:** Subscription management, order history, and wallet.

### Phase 3: Owner Experience
8. **Owner Onboarding/Shop Setup:** Form for shop name, address, menu items, and pricing.
9. **Owner Dashboard:** Overview of active subscriptions, today's orders, and earnings analytics.
10. **Order Management:** Accept/Reject interface and status updater.

### Phase 4: Administration
11. **Admin Panel:** User/Provider management, listing approval queue, and platform-wide analytics.

## Technical Specifications
- **Framework:** React/Next.js (Web) and React Native (Mobile layout concepts).
- **Styling:** Tailwind CSS with custom design system tokens.
- **Components:** Glassmorphic cards, animated transitions, responsive layouts.
