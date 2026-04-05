---
layout: default
title: Asset Curator User Guide
description: Help and documentation for Asset Curator
permalink: /user-guide/
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css?v=1' | relative_url }}">

<div class="sv-nav">
  <a class="sv-btn" href="{{ '/' | relative_url }}">Home</a>
  <a class="sv-btn" href="https://peacheybyte.github.io/">Peacheybyte Studios Home</a>
</div>

## Introduction

Asset Curator is an asset management application designed to track, manage, and analyse physical assets using QR codes, structured data, maintenance tracking, and reporting.

It is built to answer practical questions:
- What is this item?
- Where should it be?
- Where is it now?
- Is it serviceable?
- Is it due for maintenance?

The system works best when records are consistent and up to date.

---

## 📄 Download Full Manual

👉 [Download PDF User Manual](../assets/Asset_Curator_User_Manual.pdf)

---

## Getting Started

When first opened, the app runs in **Local Mode**, storing all data on the device.

### Free Version

- Local database only
- Immediate use without setup
- No sync features

### Paid Versions

- Connect to a **Master Database**
- Create shared databases
- Sync across devices

This allows multi-user environments without rebuilding data.

---

## Main Screen

Displays all assets with:

- Title and Asset ID  
- Current and Home Location  
- Status  
- Optional image  

### Actions

- Scan Label  
- Add Item  
- Print Label  

### Tools

- Search (Title-based)
- Filter by Tag
- Filter by Location
- Toggle image / no-image view

Filtering becomes important as asset volume grows.

---

## Adding and Managing Assets

Each asset is a structured record.

### Core fields

- Asset ID (auto-generated)
- Title
- Description
- Home Location
- Current Location
- Status
- Tags

### Optional fields

- Image
- Serial / Part numbers
- Pricing + purchase/sale data
- Dates and record tracking

Asset ID is critical — it ties together:
- QR codes
- Labels
- Scanning behaviour

---

## Status Options

- Serviceable  
- Unserviceable  
- On Loan  
- Missing  
- Disposed  

These define operational state — not just storage.

---

## Locations and Tags

### Locations

- **Home Location** = where it belongs  
- **Current Location** = where it is  

This allows tracking of:
- misplaced items
- loans
- movement

### Tags

Used for:
- grouping
- filtering
- reporting

You can:
- Add
- Rename
- Deactivate
- Delete (if unused)

---

## QR Codes and Labels

Each asset generates a QR code.

You can:
- Print labels
- Scan to open asset instantly
- Use Avery / Dymo formats

Purpose:
- eliminates manual searching
- reduces identification errors

---

## Dashboard

Quick summary view:

- Correct Location
- Out of Place
- Serviceable
- Missing
- Total assets

Designed for fast situational awareness.

---

## Reporting Module

Provides deeper insight:

- Totals by status
- Totals by location
- Location/status matrix
- Misplaced assets
- Coverage metrics

Advanced tier expands this further.

---

## Maintenance Module

Tracks servicing using:

- Date
- Hours
- Cycles
- Distance

### Features

- Maintenance profiles (R1, R2, R3)
- Counter tracking
- Overdue detection
- Forecasting

Purpose:
Turn asset records into **lifecycle management tools**

---

## Database Synchronisation

### Local Mode
- Device-only storage

### Master Database
- Shared dataset
- Multi-device sync

Each device keeps a local copy and syncs changes.

Conflict handling uses:
- timestamps
- device identifiers

---

## Settings

Includes:

- Upgrade info
- Label size selection
- Open PDF after print
- Tag management
- Location management
- Database tools

Settings define how the app fits your workflow.

---

## Pricing Overview

### Free
- Limited assets
- Local only
- Dashboard

### Premium
- Unlimited assets
- Sync
- Basic reporting

### Advanced
- Expanded reporting

### Pro
- Maintenance + full reporting

---

## Troubleshooting

If something isn’t working:

- Restart app
- Check permissions
- Confirm correct database
- Verify plan supports feature
- Check maintenance setup

---

## Final Notes

The system is only as good as the data:

- Keep locations updated
- Use clear titles
- Apply tags consistently
- Label assets early

Done properly, Asset Curator becomes:
a working system — not just a list.
