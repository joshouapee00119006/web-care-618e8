# CARE233 - Home Nursing & Care Services Ghana 🇬🇭

Professional Home Nursing Platform - Book a Nurse in 2 Minutes, Earn 3% Referring.

Live App: https://joshouapee00119006.github.io/web-care-618e8/

## 🚀 3 Platforms in 1

### 1. 📋 CLIENT APP (Public)
**Link:** `index.html`
- Book Home Nurse (2 Weeks, 1 Week, 3 Days, Monthly)
- GPS & Location Capture
- **EARN 3% Tab:** Anyone enters Name + MoMo → Generates referral link with MoMo embedded → Earns 3% when someone books
- Auto WhatsApp to Admin with Referral MoMo

Features:
- Tabs: Book Nurse | Earn 3%
- Referral Banner: Shows bonus when opened via referral link
- Saves booking to localStorage + WhatsApp Admin

### 2. 👷 WORKER APP (Nurses / Caregivers)
**Link:** `worker.html`
- One-file Login (Name + Phone + MoMo) - No password
- View Available Jobs (Created by Admin)
- Accept Jobs → WhatsApp Client directly
- Track Total Earned (80% of job value)
- My Accepted Jobs history

### 3. 🔐 SUPER ADMIN (Owner Only - PIN: 1234)
**Link:** `admin.html`
- **4 Tabs:**
    - **Dashboard:** Total Bookings, Revenue, Referral to Pay (3%), Pending Payouts, Profit
    - **Bookings:** Full table with Date, Care Type, Client Phone, Location, Total, Ref Code, **Agent Name, Agent MoMo (Yellow), 3% Earn, Pay & Delete Actions** - Pay button opens WhatsApp + MoMo USSD
    - **Create Job:** Create jobs for workers (Title, Location, Type, Pay, Description) - Workers see instantly on worker.html
    - **Workers:** See all workers who logged in, jobs accepted

## 💰 Referral System - How It Works

1. Agent goes to `index.html` → Earn 3% Tab → Enters Name + MoMo → Generate Link
2. Link format: `index.html?ref=CAREXXX&agentName=John&agentMoMo=0244...`
3. Client opens link → Banner shows "3% Bonus Applied - Agent: John - 0244..."
4. Client books → Booking saved with `agentName` + `agentMoMo` + `earn`
5. Admin sees in admin.html → Yellow box: **MoMo to PAY: 0244... - GHS 42** + Pay Now button

## 🛠 Tech Stack

- Pure HTML/CSS/JS - No backend needed (localStorage demo)
- PWA Ready (manifest.json)
- GitHub Pages Hosting
- WhatsApp Integration for bookings & payouts

## 📂 File Structure - Ultra Clean
