VConnect - A Decentralized Mental Well-Being Communication System Built
on the Internet Computer (ICP)

OVERVIEW VConnect is a decentralized mental well-being support platform
that combines: - Smart stress monitoring - Intelligent Busy Mode
automation - AI-powered message clarity assistant - Internet Identity
authentication - Fully decentralized backend (Motoko canister on ICP)

ARCHITECTURE Frontend (React + Vite + Tailwind) | Internet Identity (ICP
Authentication) | Backend Canister (Motoko on ICP) | Access Control +
User State + Busy Mode Logic

CORE FEATURES 1. Smart Stress Monitoring (UI Prototype) - Real-time
stress dashboard - Trusted contact alerts

2.  Smart Busy Mode
    -   Toggle availability
    -   Custom auto-reply message
    -   Restrict specific principals
    -   Contact duration estimates
3.  AI Message Clarity Assistant
    -   Sentiment scoring
    -   Tone suggestions
    -   Rewrite suggestions
4.  Decentralized Authentication
    -   Internet Identity login
    -   Principal-based user storage
    -   Role-based access control

LOCAL DEVELOPMENT SETUP

1.  Install Dependencies pnpm install

2.  Start Local ICP Network icp network start -d

3.  Create Canisters icp canister create backend icp canister create
    frontend

4.  Deploy icp deploy

5.  Run Frontend pnpm –filter ‘@caffeine/template-frontend’ start

App runs at: http://localhost:3000

TECH STACK - Internet Computer (ICP) - Motoko - React 19 - Vite -
TailwindCSS - TanStack Router - React Query - Internet Identity - pnpm

HACKATHON IMPACT VConnect focuses on preventive emotional care, smart
communication boundaries, and decentralized identity-based support
systems.

FUTURE IMPROVEMENTS - Real wearable integration - On-chain stress
history - Advanced AI sentiment model - Mobile app version

License: MIT
