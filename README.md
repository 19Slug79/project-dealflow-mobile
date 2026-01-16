# project-dealflow-mobile

**AI-powered mobile app for sourcing, pricing, and resale decisions**

---

## Overview

Project Dealflow Mobile is a mobile-first resale intelligence platform built for resellers, flippers, and arbitrage operators who buy and sell on platforms like eBay, Mercari, Facebook Marketplace, Amazon, and local marketplaces.

The app acts as a real-time field intelligence tool that helps users:

- Identify products instantly
- Determine safe offer prices
- Estimate resale profit
- Assess risk and confidence
- Generate negotiation strategies
- Track inventory and performance
- Improve decision accuracy over time

This is a mobile-only product optimized for real-world sourcing environments such as thrift stores, estate sales, retail clearance aisles, garage sales, and marketplace meetups.

Web dashboards and advanced analytics will be added later as a secondary platform.

---

## Product Vision

> Every buy decision should be confident, profitable, and intentional.

Most resellers lose money because of:
- Overpaying
- Underestimating fees and shipping
- Ignoring risk
- Buying low-demand items
- Misjudging condition

Project Dealflow replaces guesswork with intelligence.

---

## Core Principles

1. **Decision Accuracy First**  
   Every recommendation includes confidence scoring and verification flags.

2. **Deterministic Pricing Logic**  
   All pricing and offer numbers come from math-based engines, not LLM guesses.

3. **AI as an Intelligence Layer**  
   LLMs generate insights, explanations, and language — never final prices.

4. **Mobile-First Field Tool**  
   The app is designed for real-world sourcing, not desk-based analysis.

5. **Trust & Transparency**  
   Every output shows assumptions, inputs, and risk factors.

---

## Core User Loop

1. User opens the app while sourcing
2. Scans barcode or takes photos
3. App identifies the item
4. App computes offer price and profit
5. App shows confidence score
6. User taps: BUY, SKIP, or MAYBE

This entire flow should take under 15 seconds.

---

## Feature Overview

### 1. Item Analysis Engine

Analyzes any resale item and determines:

- Market price range
- Recommended list price
- Expected net profit
- Platform fees
- Shipping assumptions
- Market risk
- Competition level
- Buyer expectations

Includes:
- Confidence score (0–100%)
- Verification flag (YES / NO)
- Risk classification (Low / Medium / High)

---

### 2. Offer Price Engine (Buy Decision System)

Determines whether an item should be purchased and at what price.

Inputs:
- Expected resale price or sold range
- Platform fees
- Shipping estimate
- Risk buffer
- Supplies and refurb cost
- Target profit
- Target ROI

Outputs:
- Target offer price (starting anchor)
- Maximum offer (walk-away)
- Profit at target and max
- ROI at target and max

This engine is fully deterministic and configurable.

---

### 3. Negotiation Strategy Generator

Generates real-world negotiation scripts based on engine outputs.

Outputs:
- Opening messages
- Counter-offer ladder
- Concession strategies
- Walk-away scripts
- What-not-to-say warnings

Tones:
- Friendly
- Firm
- Fast-close

The LLM is restricted to only use engine-generated numbers.

---

### 4. Barcode Product Lookup

Instantly identifies retail products via UPC/EAN scanning.

- Camera barcode scanning
- Product metadata lookup
- Title, brand, model, category
- Images and identifiers

Used for:
- Faster sourcing
- Reduced model ambiguity
- Higher confidence scoring

---

### 5. Computer Vision Item Analysis

Analyzes photos of items to assess condition and risk.

Detects:
- Wear and scratches
- Missing accessories
- Packaging condition
- Labels and serials
- Authenticity risk

Vision outputs feed into:
- Confidence scoring
- Risk buffering
- Verification flags
- Offer engine

---

### 6. Inventory Management

Tracks items from purchase to sale:

- Purchase cost
- Listing price
- Platform
- Sale price
- Fees
- Shipping
- Net profit

Statuses:
- Draft
- Purchased
- Listed
- Sold
- Returned

Includes:
- ROI tracking
- Time-to-sale metrics
- Category performance

---

### 7. Performance Dashboard

Business-level insight into reseller performance:

Metrics:
- Total profit
- ROI
- Accuracy score
- Win rate
- Sell-through rate
- Inventory velocity

Charts:
- Profit over time
- ROI trend
- Confidence vs outcome

---

### 8. Confidence Scoring System

Provides trust and transparency for every decision.

Inputs:
- Market data quality
- Item specificity
- Condition clarity
- Platform risk
- Category risk
- Vision signals
- Barcode certainty

Outputs:
- Confidence score (0–100)
- Verification flag
- Risk notes

---

### 9. Gamification & Engagement

Makes reselling habit-forming and engaging.

Features:
- XP points
- Levels
- Badges
- Streaks
- Challenges
- Weekly goals
- Achievement cabinet

Examples:
- Accuracy Master
- Profit Hunter
- Fast Flip
- Negotiation Pro
- Inventory King

---

### 10. PWA / Offline Sourcing Mode

Mobile field tool for real-world sourcing.

Features:
- Offline capture
- Draft syncing
- Barcode scanning
- Photo capture
- Instant offer computation
- Buy / Skip / Maybe decisions

---

### 11. Notifications

High-value, low-noise notifications:

- Weekly recap
- Challenge completion
- Free limit warnings
- Maybe reminders
- Inventory follow-ups

---

### 12. Subscriptions & Monetization

Plans:
- Free
- Launch Pro ($9.99 intro)
- Pro ($24)

Gating:
- LLM usage quotas
- Vision runs
- Negotiation scripts
- History depth
- Advanced analytics

---

## Architecture Overview

### Mobile App

- React Native + Expo
- TypeScript
- Camera & barcode scanning
- Offline storage
- Push notifications
- OTA updates

### Backend

- Node.js
- Express
- PostgreSQL
- Deterministic pricing engines
- AI orchestration layer

### AI Layer

- OpenAI (LLM reasoning & language)
- Vision model (condition analysis)
- Barcode product APIs

### Data

- Inventory
- Offer history
- Confidence tracking
- Performance metrics
- User profiles
- Gamification stats

---

## Security & Observability

- Authentication system
- Stripe billing
- Usage metering
- Sentry error tracking
- Analytics and event tracking
- Abuse protection

---

## Target Users

- Resellers
- Flippers
- Arbitrage operators
- Side hustlers
- Small business sellers
- Estate sale buyers
- Thrift store buyers
- Amazon sellers
- eBay power sellers

---

## Positioning

This is not:
- A listing tool
- A price scraper
- A generic AI chatbot

This is a decision intelligence system for resale professionals.

---

## Roadmap

### Phase 1 — Mobile MVP
- Sourcing mode
- Offer engine
- Barcode scanning
- Vision analysis
- Negotiation assistant
- Offline mode
- Inventory lite
- Gamification

### Phase 2 — Power Features
- Advanced analytics
- Tax exports
- Team mode
- Playbooks
- Vision history
- Profit simulations

### Phase 3 — Web Platform
- Desktop dashboard
- Deep analytics
- Business reporting
- Multi-user accounts

---

## North Star

"Every buy decision should be confident, profitable, and intentional."

---

## Status

This repository is under active development.

The current name "Project Dealflow" is a temporary codename.
Branding and product name will be finalized prior to public launch.

---

## License

Proprietary — All rights reserved.
