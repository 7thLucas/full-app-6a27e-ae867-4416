# BloomOps — Product Overview

## What Is It
BloomOps is an all-in-one operations platform for independent florist shop owners. It unifies flower inventory management, bouquet order tracking, and delivery scheduling into a single dashboard — with the primary goal of minimizing perishable waste and ensuring every arrangement reaches its recipient fresh and on time.

## Tagline
"Every Petal Counts."

## Target Users

| Persona | Role |
|---------|------|
| **Shop Owner** | Primary user. Manages all operations: inventory purchasing, order oversight, delivery coordination, and analytics. |
| **Shop Staff** | Handles day-to-day order intake, inventory updates, and bouquet preparation status. |
| **Delivery Driver** | Views assigned deliveries, updates delivery status in real time. |

## The Problem It Solves
Florists operate under a brutal triple constraint:
1. **Perishable inventory** — flowers expire within days; over-ordering causes spoilage and wasted spend, under-ordering means lost sales and unhappy customers.
2. **Unpredictable demand** — order volume spikes around holidays and events, making stock planning difficult without historical data.
3. **Fragmented operations** — most shops rely on paper order books, spreadsheets, or disconnected tools that don't link inventory to orders, or orders to deliveries.

This fragmentation leads to spoilage (industry average: 15–25% of perishable inventory is wasted), missed deadlines, and overworked staff.

## The Solution
BloomOps brings inventory, orders, and deliveries into one coherent system:
- **Freshness-first inventory** with per-variety arrival dates, estimated freshness windows, and automatic spoilage-risk alerts before flowers go to waste.
- **Order lifecycle management** from intake through preparation, dispatch, and confirmed delivery — with every step tracked.
- **Delivery scheduling** with calendar views, driver assignments, and area-grouped routing for efficient runs.
- **Spoilage intelligence** that surfaces at-risk stock proactively and recommends same-day use to recover value instead of writing off waste.
- **Inventory-order reservation** so committed stock is instantly visible and separate from available stock across the team.

## Core Features

### 1. Smart Inventory Management
Track every flower variety by stock quantity, arrival date, and estimated freshness window. Automatic low-stock and spoilage-risk alerts. FIFO usage guidance to ensure oldest stock ships first. Supplier reorder tracking to avoid gaps.

### 2. Order Management Pipeline
Capture bouquet orders with customer details, special instructions, target delivery date, and flower requirements linked directly to inventory. Status pipeline: **Intake → Preparation → Ready → Dispatched → Delivered**.

### 3. Delivery Scheduling
Calendar-based delivery schedule with time-slot booking, driver assignment, area-grouped routing, and real-time delivery status updates visible to owners and staff.

### 4. Spoilage Intelligence Dashboard
At-a-glance view of at-risk inventory with days-to-expiry counters, waste history tracking, and actionable recommendations — use oldest stock first, surface same-day specials to move near-expiry flowers quickly.

### 5. Inventory-Order Reservation
When an order is created, required flower quantities are soft-reserved from inventory, giving the whole team real-time visibility into what is available vs. committed for pending orders.

### 6. Waste Analytics
Track spoilage history and demand patterns over time to sharpen purchasing decisions, right-size order quantities, and measure the ROI of running BloomOps.

## Key Metrics & Value Targets
- **Spoilage reduction**: 30%+ decrease in perishable waste through freshness alerts and FIFO guidance.
- **On-time delivery**: 95%+ target delivery success rate through structured scheduling and proactive dispatch alerts.
- **Time saved**: 2+ hours per day reclaimed from manual inventory checks and order coordination.
- **Current waste benchmark**: 15–25% of perishable inventory is lost in the average florist shop — eliminating this waste directly improves shop profitability.

## Positioning
BloomOps sits between a simple notes app and a heavyweight ERP — purpose-built for the florist context, approachable enough for a solo-owner shop, capable enough for a multi-staff operation. It is the system of record for every flower that comes into the shop and every bouquet that leaves it.

## Brand & Tone
- **Aesthetic**: Clean, calm, modern — professional without being cold; warm without being impersonal.
- **Voice**: Direct and practical. Florists are craftspeople, not technology operators — keep UI and language approachable.
- **Primary color**: Emerald green — connotes freshness, nature, and growth.
- **Supporting palette**: Warm off-white backgrounds, deep slate for body text, soft emerald tints for accents and chips, amber highlights for spoilage warnings.

## Scope & Tech
- Web application — admin dashboard model
- RBAC roles: Owner, Staff, Driver
- Stack: Remix + TypeScript + Tailwind CSS + shadcn/ui (frontend); Express + MongoDB / Mongoose + Typegoose (backend)
