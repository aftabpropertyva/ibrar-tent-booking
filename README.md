# Ibrar Tent & Catering - Mobile Booking App

A lightweight, production-ready mobile web application for booking tent and catering equipment.

## 🚀 Features
- Single-page mobile-first design (max-width 480px)
- No external dependencies or frameworks (Vanilla JS)
- Direct WhatsApp integration for booking
- Fast and responsive UI with 44px tap targets

## 🛠 Deployment Steps (GitHub Pages)
1. Go to your repository on GitHub.
2. Click on **Settings**.
3. In the left sidebar, click on **Pages**.
4. Under **Build and deployment**, select **Branch: main** and folder **/(root)**.
5. Click **Save**.
6. Your site will be live at `https://[your-username].github.io/ibrar-tent-booking/` after a few minutes.

## 💬 WhatsApp Logic
The app collects quantities for selected items and generates a pre-formatted message:
> Assalam u Alaikum! I want to book equipment:
> - [Item]: [Qty]
> ...
> Please confirm availability & pricing. JazakAllah!

It then redirects the user to WhatsApp with the encoded message.

## ⚙️ Technical Details
- **File Size:** < 30KB
- **Tech Stack:** HTML5, CSS3, Vanilla JavaScript
- **Target:** Mobile browsers (iOS/Android)
