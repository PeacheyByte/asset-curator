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

## Getting Started

When you first open the app, it operates in **Local Mode** by default.

### Free Version

- You can immediately begin adding and managing assets using a **local database stored on your device**
- Sync features are **not available** in the free tier

### Paid Versions

Once upgraded, additional options become available:

- Connect to an existing **Master Database**
- Create a **Shared Master Database**
- Create a local database linked to a master database
- Sync between local and master databases

This allows multiple users and devices to work with the same shared asset dataset.

## Main Screen

The main screen displays all assets with:

- Title and Asset ID
- Current Location and Home Location
- Status
- Optional image

### Main actions

- Scan Label
- Add Item
- Print Label

### Main tools

- Search by title, ID, or tags
- Filter by Tag
- Filter by Location
- Switch between List and List - No Images view

## Adding and Managing Assets

Each asset can include:

### Core fields

- Asset ID
- Title
- Description
- Home Location
- Current Location
- Status
- Tags

### Optional fields

- Image
- Serial Number
- Part Number
- Bought Price
- Date Bought
- Sale Price
- Sold Price
- Sold Date
- Record Last Update

Assets can be edited and updated at any time.

## Status Options

The app currently supports these core status values:

- Serviceable
- Unserviceable
- On Loan
- Missing
- Disposed

## Locations and Tags

Locations and tags are managed centrally.

### Locations

Locations define where assets belong and where they are currently stored.

### Tags

Tags are used for grouping, filtering, and reporting.

You can:

- Add new entries
- Rename entries
- Deactivate entries
- Delete entries if they are not in use

Locations and tags can also be added directly from the item edit screen.

## QR Codes and Labels

Each asset includes a QR code.

You can:

- Print labels for assets
- Scan a label to open the matching asset
- Use supported Avery and Dymo label formats

## Dashboard

The dashboard provides quick visual summaries, including:

- Correct Location
- Out of Place
- Serviceable
- Missing
- Asset Summary totals

## Reporting Module

The reporting module provides operational summaries and deeper reporting insights.

Examples include:

- Total items
- Total items per status
- Total items per location
- Total items per location per status
- Total misplaced items
- Empty locations
- Status coverage
- Spread indicators

Advanced reporting expands this further with broader summary and trend-oriented views.

## Maintenance Module

The maintenance module supports service tracking using:

- Date
- Hours
- Cycles
- Distance

### Maintenance features

- Create a maintenance profile for an asset
- Set up routine services such as R1, R2, and R3
- Track current counters
- View overdue items
- View upcoming maintenance
- Use maintenance reporting and forecasting

If maintenance has not yet been set up for an item, the app will show that clearly and provide setup options.

## Settings

The Settings page includes:

- Upgrade information
- Label size selection
- Open PDF after printing
- Manage tags
- Manage locations
- Choose Master Folder
- Create Master Database
- Create Local Database
- Sync Databases

## Pricing Overview

### Free

- Limited number of items
- Local database only
- Dashboard access
- No sync

### Premium

- Unlimited items
- Sync features
- Basic reporting

### Advanced

- Includes reporting module improvements and advanced reporting

### Pro

- Includes full reporting and maintenance functionality

## Troubleshooting

If something is not working as expected:

- Restart the app
- Confirm required permissions are enabled
- Verify the correct database setup is being used
- Check that sync features are available under your plan
- Confirm maintenance has been configured for the selected asset if using maintenance screens

---
{% include footer.html %}
