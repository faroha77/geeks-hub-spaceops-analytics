# Geeks Hub — SpaceOps Booking & Operations Analytics Dashboard

Responsive Booking & Operations Analytics Dashboard developed for the Geeks Hub Software Engineering Internship Placement (ECU Level 3) under the supervision of Eng. Mohamed Raslan.

## Overview
This application ingests raw space reservation logs, validates and normalizes records, detects booking conflicts, and aggregates key operational metrics across workspace tiers (**Shared Area**, **Meeting Room**, and **Office**).

## Key Features
- **Mock REST & State Simulator:** Simulates API network latency and `Loading`, `Error`, and `Empty` states.
- **Data Cleaning & Analytics Pipeline:** Handles missing fields, normalizes date/time formats, flags overlapping bookings, and calculates Occupancy Rate, Cancellation Rate, Peak Utilization Hours, revenue totals, and booking counts by space tier.
- **Interactive UI & Charts:** Includes live KPI summary cards, interactive SVG trend/category charts, and a searchable/filterable Reservation Log Data Table.
- **Built-in Unit Tests:** Verifies core data cleaning, conflict detection, and metric calculation routines directly in the browser.

## Branching Workflow
Organized following `main`, `dev`, and `feature/*` branches.

## How to Run
Open `index.html` directly in any modern web browser (such as Chrome or Edge).
