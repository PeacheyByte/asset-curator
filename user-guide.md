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

X **Asset Curator - User Guide**

Welcome to the Asset Curator User Guide. The Guide explains what Asset Curator does, how to use the major parts of the app, and why certain fields and setup choices matter. While the manual reflects the app’s current features, the developer has great plans for the future and this manual will be updated accordingly.

**Prefer a full document version?**
[Download the complete Asset Curator User Manual (PDF)](../assets/Asset_Curator_User_Manual.pdf)


## **1. Introduction**

Asset Curator is an asset management application for individuals, teams, and organisations that need a clear record of their physical assets. It combines structured asset records with QR codes, label printing, maintenance tracking, and reporting tools.

The app is designed to answer the practical questions that often arise when managing equipment: What is this item? Where should it normally be? Where is it right now? Is it serviceable? Is it due for maintenance? Is it easily identifiable?

The value of the system comes from consistency. A well-maintained asset record reduces guesswork, saves time during audits or handovers, and makes it easier to find items, prove ownership, and keep equipment in service.


## 2. **Getting Started**

When first launched, Asset Curator operates in Local Mode. In this mode, the data is stored on the active device only. This allows a user to begin entering assets immediately without first setting up a shared database.

This default approach is useful for two reasons. First, it lowers the barrier to entry for new users who simply want to start tracking items. Second, it allows the app to be trialled or demonstrated without the extra setup involved in synchronisation.

For paid tiers, the app can also work with a shared Master Database. That shared file allows more than one device or user to work with the same asset set while still keeping a local working copy on each device.

**Typical starting paths**
-  Single user or trial use: begin with a Local Database and start entering assets immediately.
-  Team or shared environment: create or connect to a Master Database so multiple devices can work from the same central data source.
-  Existing setup: connect to an already-created Master Database and create a Local Database from it on the current device.

In short, Local Mode is the easiest way to begin, while synchronised use is the better long-term option where multiple people need access to the same asset information.


## 3. **App Overview**

The main screen displays the asset list. Each entry is intended to show enough information for the user to identify an item quickly without opening the full record.

Depending on the selected list view, each asset entry shows:
-  Title
-  Asset ID
-  Current Location and Home Location
-  Status
-  Optional image

The top area of the main screen provides the core daily actions:
-  Scan Label - scans a QR code and opens the linked asset record.
-  Add Item - creates a new asset record.
-  Print Label - generates labels for the current filtered view.

The main screen also provides access to the Dashboard and the main menu. The menu includes Add Item, Export to Excel, Settings, and About.

Search and filtering tools are provided to help users narrow down the list. This is particularly important once the number of assets grows.


## 4. **Adding and Managing Assets**

New assets are created from the Add Item button on the main screen. This opens the Add/Update page, where the asset's information can be entered or edited.

At a minimum, a new record requires an Asset ID and a Title. The Asset ID is auto-generated so that each asset can be uniquely identified. This matters because the Asset ID is the stable identifier used on labels, in QR codes, and during scanning.

**Fields currently available**

**Mandatory fields:**
-  Asset ID (auto-generated)
-  Title

**Strongly recommended fields:**
-  Description
-  Home Location
-  Current Location
-  Status
-  Tags

**Additional optional fields:**
-  Image
-  Serial Number
-  Part Number
-  Bought Price
-  Date Bought
-  Sale Price
-  Sold Price
-  Record Last Update

Although some fields are optional, filling them in improves the usefulness of the database. For example, locations make the record operationally useful, tags improve filtering, and serial or part numbers make the system more valuable when dealing with repairs, spares, or warranty questions.

Selecting an asset from the main page opens the item details page, where the record can be updated. This makes the app suitable not only for initial data entry, but also for ongoing day-to-day record maintenance.


## 5. **Locations and Tags**

Locations and Tags are managed centrally because they form part of the structure of the database, not just a single record.

**Locations**

There are two location types in the app:
-  Home Location - where the asset normally belongs.
-  Current Location - where the asset is currently located.

This distinction is important, by comparing Home and Current location, the app can help identify items that are out of place, on loan, dispatched, or under repair.

**Tags**

Tags are used for categorisation. They help answer questions such as what kind of asset an item is, what area it belongs to, or how it should be grouped for reporting and filtering.

The user can add, rename, deactivate, or delete Tags and Locations through the management tools. Deletion is restricted when an entry is still in use, which helps preserve data integrity and prevents accidental breakage of existing records.

Tags and Locations can also be created directly from the drop-down menus on the Add/Update page. This is useful when a user is entering a new asset and a category or location does not yet exist.


## 6. **QR Codes and Labels**

A QR code is automatically generated for each asset record. QR codes are included in printed labels, and scanning a label will open Asset Curator and load the relevant asset details.
-  QR codes are generated from the asset record.
-  Labels can be printed from within the app.
-  Scanning a label opens the linked asset record.

If the app is not installed on a device, the the code will to direct the user to Google Play to install Asset Curator.


## 7. **Searching and Viewing Items**

The main screen search bar is used to find items quickly by asset Title.

Users can also filter the list by Tag or Location, making searching easier, especially when updating or stocktaking a particular location.

The app currently supports filtering rather than full sorting tools, this is function will be available in future versions.

**List views**
The asset list can be viewed with or without images. The no-image list is useful when the priority is fitting more assets on screen, while the image list is useful where for visual identification.


## 8. **Database Synchronisation**

Local Mode stores data only on the current device. This is simple and reliable for single-user setups.

A shared Master Database allows multiple devices to synchronise against the same central data source. Each device still keeps its own local copy, but synchronisation is used to keep the overall data set aligned.

Asset Curator's model allows each device to work independently and then synchronise changes back to the shared database.

To reduce the chance of overwriting newer data with older data and causing data conflicts, the system uses timestamps and device identifiers when merging updates.

**Common synchronisation actions**
-  Create a Master Database from an existing Local Database. Generally used when setting up a common dataset for the first time.
-  Connect a new device to an existing Master Database, used for creating a Local Database from a Master Database.
-  Synchronise between Local and Master databases.

These functions are available through Settings. In practice, this means a single-user setup can grow into a multi-user system later without needing to rebuild the database from scratch.


## 9. **Maintenance Module**

The Maintenance Module allows a user to track servicing requirements for an asset. This moves the app from simple asset storage into lifecycle management.

Maintenance can be tracked using the following trigger types:
-  Dates
-  Distance
-  Usage cycles
-  Hours

Up to three routine servicing schedules can be programmed for an asset, in addition to ad-hoc servicing or repairs. The app can then identify maintenance as upcoming or overdue based on the thresholds that have been configured.

**How to access maintenance**
Open the asset's record from the main list, then select Maintenance. From there, the user can view configured routines and update the current running figures for the asset.


## 10. **Reporting Module**

The Reporting Module provides quick operational visibility into the current state of the database. It is designed to help users spot patterns and issues without having to open each asset one by one.

Current reporting focuses on summaries such as:
-  Asset status distribution
-  Maintenance status, including overdue and upcoming servicing
-  Location summaries

Good summaries help a user identify what needs attention, where equipment is concentrated, and whether the database reflects real operational conditions. The reporting function is evolving and will be expanded in future Asset Curator versions. 


## 11. **Settings**

Settings is where the user configures app behaviour and maintains the supporting structures around the database.

The Settings area currently includes:
-  Upgrade access
-  Label format selection, including printer paper or label size
-  Tag management tools
-  Location management tools
-  Database synchronisation tools, including creating or linking Local and Master databases


## 12. **Free vs Paid Features**

Asset Curator is structured so that users can begin with the core functions and then move to paid tiers if they need more scale or more advanced capability.

**Free version**
-  Limited number of assets
-  Core asset management functions
-  Dashboard access
**Paid versions**
-  Unlimited assets
-  Synchronisation functions
-  Advanced reporting (Advanced tier)
-  Maintenance management (Pro tier)

This approach is designed to allow users to trial the app and determine whether it fits their workflow before committing to the broader feature set.


## 13. **Troubleshooting**

If issues occur, start with the simple checks first. Many problems in asset systems come from configuration, permissions, or database selection rather than from the asset record itself.
-  Restart the app.
-  Check that camera and storage-related permissions are enabled where needed.
-  If using shared mode, confirm that the correct database has been selected.
-  If labels or scanning are involved, confirm that the correct asset record exists and that the QR code is readable.

For persistent issues, contact support. When reporting a problem, it helps to include what action was being performed, whether the issue occurred in Local or synchronised use, and whether the problem affects one asset or the whole app.


## 14. **Final Notes**

The quality of the database depends on the consistency of the records entered into it. Asset Curator works best when Titles are clear, Locations are kept current, Status values are updated when conditions change, and labels are attached to physical items as early as possible.

Used well, the app becomes more than a list of items. It becomes a practical working record of what the organisation owns, where those assets are, and what needs attention next.
