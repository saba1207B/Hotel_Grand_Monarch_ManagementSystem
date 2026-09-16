# The Grand Monarch — Luxury In-Room Dining & Kitchen Management System

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-gold?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Compatible-green?style=for-the-badge)

<p align="center">
  <strong>An Art Deco inspired, real-time in-room dining and hotel kitchen dispatch management system.</strong><br>
  Built with vanilla HTML5, CSS3, and JavaScript featuring instant dual-portal synchronization.
</p>

</div>

---

## ⚜️ Project Overview

**The Grand Monarch** system is an end-to-end luxury hotel hospitality solution designed for both guests and hotel culinary staff. The project provides an immersive, Art Deco dark-and-gold visual experience paired with real-time operational workflows for order dispatch, kitchen status messaging, delivery notifications, and post-dining guest reviews.

---

## 🌐 Live Website

**[Visit the Live GitHub Pages Website](https://saba1207B.github.io/Hotel_Grand_Monarch_ManagementSystem/)**

---

## ✨ Key Features

### 🛎️ 1. Guest In-Room Dining Portal (`index.html`)
- **Curated 24-Hour Menu**: Four categories featuring Breakfast, Mains, Beverages, and Artisanal Desserts.
- **Interactive Tray & Real-time Calculation**: Dynamic quantity selectors, add-to-tray feedback, price subtotals, and currency formatting in ₹ (INR).
- **Personalized Guest Ordering**: Room number validation, dietary preferences, custom delivery timing, and special culinary requests.
- **Live Delivery Pulse**: Real-time kitchen status ticker streaming updates directly to the guest's screen.
- **Doorstep Delivery Alert**: Interactive banner notifying guests when their order has arrived outside their room.
- **Guest Feedback & Star Rating**: Integrated post-dining rating system (1–5 stars with written culinary feedback) synced directly to management.

### 👨‍🍳 2. Staff Management & Kitchen Dispatch (`management.html`)
- **Real-Time Order Queue**: Instant visibility of incoming room orders sorted chronologically with guest details, order items, special requests, and timestamps.
- **Doorstep Notification Dispatch**: One-click dispatch alerting guests that food is outside their room.
- **Direct Room Messaging**: Custom messaging console to transmit preparation updates, wine pairings, or timing alerts to specific guest rooms.
- **Sent Updates Audit Log**: Real-time chronological audit trail of all messages sent from the kitchen.
- **Guest Reviews & Satisfaction Dashboard**: Live analytics calculating average guest satisfaction score, visual star rating distribution, and complete guest reviews.
- **Testing & Demo Controls**: Quick buttons to generate realistic sample orders (`+ Sample Order`) or reset test data (`Clear Data`).

---

## 🔄 Instant Multi-Tab Synchronization

Both portals operate on a synchronized reactive architecture:
- **`localStorage` State Persistence**: Orders, kitchen messages, delivery statuses, and guest reviews persist across page reloads.
- **`storage` Event Reactive Bus**: Actions performed in the Guest View (e.g., placing an order, submitting a review) instantly update the Staff Dashboard without waiting for polling intervals.
- **Self-Healing Polling Fallback**: Automatic intervals ensure synchronization even across different browsing contexts or devices.

---

## 📁 Repository Structure

```text
Hotel_Grand_Monarch_ManagementSystem/
├── index.html               # Primary Guest Room Service & In-Room Dining Portal
├── management.html          # Staff & Kitchen Dispatch Management Dashboard
├── Hotel_Web.html           # Guest Portal alias
├── Hotel_Management.html    # Staff Portal alias
├── Hotel_Web (1).html       # Preserved original guest file
├── Hotel_Management (1).html# Preserved original management file
├── .gitignore               # Ignored OS and editor files
└── README.md                # Project documentation and architecture guide
```

---

## 🚀 How to Run & Test Locally

No package managers, build steps, or runtime dependencies required.

### Dual-Window Testing Flow
1. Open **`index.html`** in one browser window (or tab).
2. Open **`management.html`** in a second window side-by-side.
3. In `index.html`, select items (e.g., *Butter Chicken*, *Crème Brûlée*), enter your name and Room `402`, and click **Place Order**.
4. Watch `management.html` instantly render the new order card in the queue!
5. In `management.html`, click **🚪 At Doorstep** to notify the guest.
6. In `index.html`, observe the delivery banner appear immediately.
7. In `index.html`, click **Confirm Delivery & Leave Review**, select a 5-star rating, type feedback, and submit.
8. In `management.html`, switch to the **Guest Reviews** tab to view your live review and updated average score!

---

## 🌐 Deploy to GitHub Pages

1. In your GitHub repository:
   - Navigate to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **GitHub Actions**.
   - The included GitHub Actions workflow automatically deploys the repository when changes are pushed to `main`.
2. Your site will be available at:
   ```
   https://saba1207B.github.io/Hotel_Grand_Monarch_ManagementSystem/
   ```

---

## 🎨 Design System

- **Typography**: `Cormorant Garamond` (Luxury display serif) & `Jost` (Modern minimalist sans-serif) via Google Fonts.
- **Palette**:
  - Gold: `#c9a84c` | Gold Light: `#e8d08a` | Accent: `#8b6914`
  - Dark: `#0e0c09` | Dark Surface: `#181510` | Dark Elevated: `#231f18`
  - Cream: `#f5f0e8` | Cream Dim: `#d4cfc6`
  - Success Green: `#4caf7a` | Doorstep Blue: `#4c8fcf`

---

## 📜 License

Created for **The Grand Monarch Hotel & Suites**. All rights reserved.
