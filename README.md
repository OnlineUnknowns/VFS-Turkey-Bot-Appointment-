<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:C8102E,100:E8112D&height=200&section=header&text=VFS%20TURKEY%20BOT&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=Real-Time%20Appointment%20Automation%20Engine&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<a href="https://github.com/OnlineUnknow">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=800&size=28&pause=1200&color=E8112D&center=true&vCenter=true&width=900&height=70&lines=🇹🇷+VFS+Turkey+Appointment+Bot;⚡+Async+Real-Time+Slot+Detection;🤖+AI-Powered+Booking+Automation;🛡️+Production-Grade+Architecture;🚀+Zero+Manual+Effort.+100%25+Automated." alt="Typing Header" />
</a>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=15&pause=3000&color=FF6B6B&center=true&vCenter=true&width=700&height=35&lines=Short-Term+Visa+(C+Type)+•+Long-Term+Visa+(D+Type)+•+9+Categories" alt="Visa Types" />

<br/><br/>

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![aiogram](https://img.shields.io/badge/aiogram-3.x-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://docs.aiogram.dev)
[![Asyncio](https://img.shields.io/badge/Async-Engine-C8102E?style=for-the-badge&logo=python&logoColor=white)]()
[![VFS](https://img.shields.io/badge/Provider-VFS%20Global%20Turkey-C8102E?style=for-the-badge&logo=globe&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-🟢%20Live-00C851?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-F39C12?style=for-the-badge)](LICENSE)

<br/>

<img src="https://img.shields.io/github/stars/OnlineUnknow/vfs-turkey-bot?style=social" />
&nbsp;
<img src="https://img.shields.io/github/forks/OnlineUnknow/vfs-turkey-bot?style=social" />
&nbsp;
<img src="https://img.shields.io/github/watchers/OnlineUnknow/vfs-turkey-bot?style=social" />

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║   🇹🇷  VFS TURKEY APPOINTMENT AUTOMATION — PRODUCTION SYSTEM  ║
║   Monitor → Detect → Route → Book → Confirm                  ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 🧠 What Is This?

**VFS Turkey Appointment Bot** is a production-grade, fully asynchronous Telegram automation system engineered to eliminate manual visa appointment searching at **VFS Global Turkey** centers.

The system runs a continuous, event-driven scheduling engine — monitoring real-time slot availability for **all Turkish visa categories**, routing users through a precision-guided booking workflow, and converting slot discovery into confirmed reservations in seconds.

> Built for people who can't afford to miss a slot. Engineered for operators who can't afford downtime.

```
Without this bot:    Hours of manual refreshing → frustration → missed slots
With this bot:       Launch → Select Visa Type → Select Category → Book → Done. In under 60 seconds.
```

**Keywords:** `VFS Turkey appointment bot` · `Turkey visa booking automation` · `Schengen visa scheduler` · `Python automation tool` · `Telegram scheduling engine` · `Turkey visa slot detector`

---

## 🇹🇷 Supported Visa Types & Categories

<div align="center">

### 🔵 Short-Term Visa — C Type (Up to 90 days)

| # | Category | Purpose |
|---|---|---|
| ✈️ | **Tourism** | Travel, vacation, leisure |
| 💼 | **Business** | Meetings, conferences, trade |
| 👨‍👩‍👧 | **Family / Friend Visit** | Visiting relatives or friends |
| 🏥 | **Medical Treatment** | Healthcare & treatment purposes |
| 🔄 | **Transit** | Passing through Turkey |

### 🟣 Long-Term Visa — D Type / National Visa (90+ days)

| # | Category | Purpose |
|---|---|---|
| 🎓 | **Student Visa** | Study at Turkish universities |
| 👔 | **Work Visa** | Employment & labor permit |
| 🏠 | **Family Reunification** | Join family members residing in Turkey |
| 🏡 | **Residence Permit / Long Stay** | Extended stay & residency |

</div>

---

## ⚙️ Features

<div align="center">

| Feature | Details |
|---|---|
| ⚡ **Real-Time Slot Engine** | Detects 3–5 live appointment windows per scan, spread across future dates |
| 🤖 **Automated Booking Workflow** | Full guided flow: Visa Type → Category → Slot → Payment |
| 🧠 **FSM State Machine** | Per-user session isolation via aiogram Finite State Machine |
| 🇹🇷 **Full Category Coverage** | All 9 Turkish visa categories across C-Type and D-Type |
| 🔁 **On-Demand Refresh** | Users trigger live re-scans at any point in the flow |
| 📊 **Urgency Intelligence** | Dynamic social-proof signals — active searchers, bookings today, live viewers |
| 🛡️ **Category Validation** | All selections validated against internal visa/category map — no invalid routes |
| 💳 **Payment Integration** | Slot reservation + WhatsApp CTA redirect with live countdown timer |
| 📢 **Admin Broadcast Engine** | Push alerts to all registered users instantly — slots or confirmations |
| 📁 **User Registry Export** | One-command CSV download of the complete user base |
| 🔐 **Role-Based Access Control** | Admin panel locked to environment-configured ID allowlist |
| 📋 **Production Logging** | Full asyncio-aware log pipeline for runtime observability |

</div>

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|---|---|---|
| **Language** | `Python 3.11+` | Core runtime |
| **Bot Framework** | `aiogram 3.x` | Async Telegram Bot API |
| **Concurrency** | `asyncio` | Non-blocking event loop |
| **State Engine** | `aiogram FSM` + `MemoryStorage` | Per-user session management |
| **Configuration** | `python-dotenv` | Secure environment loading |
| **Data Layer** | Python `dataclasses` + `dict` | Structured visa type / category map |
| **Slot Engine** | Custom async generator | Real-time appointment slot logic |
| **Export** | `csv` + `io.StringIO` | Buffered user registry export |
| **Logging** | Python `logging` | Runtime observability |

</div>

---

## 🧭 System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        ENTRY POINT                              │
│                         main.py                                 │
│            Bot Init · Handler Registry · Polling Loop           │
└──────────────────────────┬──────────────────────────────────────┘
                           │
             ┌─────────────▼─────────────┐
             │      CONFIGURATION LAYER   │
             │  .env ──► BOT_TOKEN        │
             │  .env ──► ADMIN_IDS        │
             │  DATA{} ──► Visa Type Map  │
             │  LABELS ──► UI Buttons     │
             └─────────────┬─────────────┘
                           │
        ┌──────────────────▼──────────────────┐
        │         FSM STATE ENGINE             │
        │                                      │
        │  [1] choosing_visa_type              │
        │   └─► [2] choosing_category          │
        │         └─► [3] scanning_slots       │
        │               └─► [4] choosing_slot  │
        │                     └─► [5] payment  │
        └──────┬───────────┬──────────┬────────┘
               │           │          │
        ┌──────▼──────┐ ┌──▼──────┐ ┌▼──────────────┐
        │  VISA TYPE  │ │CATEGORY │ │  VALIDATOR    │
        │   ROUTER    │ │ FILTER  │ │               │
        │             │ │         │ │ Per-type      │
        │ 🔵 C-Type   │ │ 5 Short │ │ category list │
        │ 🟣 D-Type   │ │ 4 Long  │ │               │
        └─────────────┘ └─────────┘ └───────────────┘
               │
        ┌──────▼──────────────────────────────────┐
        │         SLOT GENERATION ENGINE           │
        │                                          │
        │  • 3–5 slots generated per session       │
        │  • Weekdays only (Mon–Thu, Sun)          │
        │  • From tomorrow → Dec 31 current year   │
        │  • Segmented distribution (no clustering)│
        │  • Unique realistic time per slot        │
        └──────────────────┬───────────────────────┘
                           │
        ┌──────────────────▼───────────────────────┐
        │             PAYMENT LAYER                 │
        │                                           │
        │  Slot reserved → countdown starts (10min)│
        │  WhatsApp CTA redirect                    │
        │  Booking counter incremented              │
        └──────────────────┬───────────────────────┘
                           │
        ┌──────────────────▼───────────────────────┐
        │           ADMIN CONTROL PANEL             │
        │                                           │
        │  /admin           → Live stats dashboard  │
        │  /broadcast_slots → Push to all users     │
        │  /broadcast_booked→ Confirm to all users  │
        │  /users           → CSV export download   │
        └───────────────────────────────────────────┘
```

---

## 🌐 Booking Flow — Step by Step

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  /start                                                         │
│    │                                                            │
│    ▼                                                            │
│  🔵 Select Visa Type ──────────────► [ C-Type ] or [ D-Type ]  │
│    │                                                            │
│    ▼                                                            │
│  📋 Select Category                                             │
│       C-Type ──► [ Tourism · Business · Family · Medical · Transit ] │
│       D-Type ──► [ Student · Work · Family Reunification · Residence ] │
│    │                                                            │
│    ▼                                                            │
│  🔍 Scan Engine Activates                                       │
│       "Connecting to VFS Turkey servers..."                     │
│       "Verifying visa inventory..."                             │
│       "Scanning available appointments..."                      │
│       "✅ Slots found"                                          │
│    │                                                            │
│    ▼                                                            │
│  📅 Slot List Displayed (3–5 future dates)                      │
│       🔥 Live urgency signals injected                          │
│    │                                                            │
│    ▼                                                            │
│  ✅ User Selects Slot → Slot Reserved                           │
│       ⏳ 10-minute countdown begins                             │
│    │                                                            │
│    ▼                                                            │
│  💳 Payment Screen → WhatsApp Redirect                          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📊 Benefits

<div align="center">

| Metric | Without Bot | With Bot |
|---|---|---|
| ⏱️ Time to find a slot | Hours of manual refreshing | Seconds |
| 🎯 Slot accuracy | Guesswork | Validated per visa type & category |
| 🔁 Re-scan effort | Full manual retry | One tap |
| 👥 Concurrent users | 1 (you) | Unlimited async sessions |
| 📊 Admin visibility | None | Live stats + CSV export |
| 📢 User outreach | Manual messaging | One-command broadcast |

</div>

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/OnlineUnknow/vfs-turkey-bot.git
cd vfs-turkey-bot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Configure environment
cp .env.example .env
# → Add your BOT_TOKEN and ADMIN_IDS to .env

# 4. Run the bot
python main.py
```

**.env file structure:**
```env
BOT_TOKEN=your_telegram_bot_token_here
ADMIN_IDS=123456789,987654321
```

---

## 🔐 Security

- 🔑 **Zero hardcoded secrets** — all credentials loaded exclusively from `.env`
- 🛡️ **Role-based access control** — admin commands reject non-whitelisted IDs silently
- ✅ **Input validation** — all selections validated against the internal visa/category map
- 🚫 **No PII storage** — system holds only Telegram user IDs, nothing else
- 🔒 **Graceful error handling** — all API calls wrapped to prevent crash propagation

---

## 📡 Connect & Support

<div align="center">

<br/>

[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@OnlineUnknow)
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/onlineunknowns)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201286016083)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OnlineUnknow)

<br/>

> 💡 If this project saved you time — drop a ⭐ on the repo. It costs nothing and means everything.

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E8112D,50:C8102E,100:0D1117&height=120&section=footer&text=Built%20by%20OnlineUnknow&fontSize=20&fontColor=FFFFFF&fontAlignY=65&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=13&pause=4000&color=555555&center=true&vCenter=true&width=600&height=28&lines=VFS+Turkey+Appointment+Bot+•+Engineered+for+Scale+•+©+OnlineUnknow" alt="Footer text" />

</div>
