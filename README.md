# Household Inventory Web App

A simple and mobile-friendly web app for managing household supplies, tracking stock levels, recording purchases, and creating a shopping list.

This project was created as a personal learning project, with Claude used as a coding assistant to help design the layout, improve the UI/UX, and refine the app logic.

## Overview

Household Inventory is designed to help users manage daily household items such as seasonings, toiletries, cleaning supplies, fresh food, vegetables, dry goods, milk, and drinks.

The app helps answer simple questions such as:

- What items do I currently have at home?
- Which items are running low?
- What do I need to buy next?
- When did I last buy something?
- How much did I spend this month?

## Features

### Inventory Management

- Add new household items
- Edit or delete existing items
- Increase or decrease item quantity directly from the inventory list
- Set unit type, starting quantity, and low-stock alert quantity
- Highlight low-stock items automatically

### Category Management

- Default categories include:
  - Seasoning
  - Household
  - Fresh food
  - Vegetables
  - Dry goods
  - Cleaning
  - Milk
  - Drinks
- Add custom categories
- Delete categories
- Choose category icons

### Default Inventory Items

The app includes default items when first used:

| Item | Category | Unit | Starting Qty | Alert Qty |
|---|---|---:|---:|---:|
| น้ำมันพืช | เครื่องปรุง | ขวด | 2 | 1 |
| ซีอิ้วขาว | เครื่องปรุง | ขวด | 1 | 1 |
| น้ำปลา | เครื่องปรุง | ขวด | 1 | 1 |
| น้ำตาล | เครื่องปรุง | ถุง | 1 | 1 |
| สบู่ | ของใช้ | ขวด | 4 | 2 |
| ยาสระผม | ของใช้ | ขวด | 1 | 1 |
| น้ำยาปรับผ้านุ่ม | ทำความสะอาด | ถุง | 1 | 1 |
| ผงซักฟอก | ทำความสะอาด | ถุง | 0 | 1 |

### Filtering and Sorting

- Filter items by category
- Multi-select category filter
- Filter low-stock items
- Sort items by category

### Purchase Tracking

- Record purchased items
- Add purchase quantity, price, date, store, and note
- Automatically increase stock quantity after recording a purchase
- View purchase history by date and store
- Track monthly spending

### Shopping List

- Create a shopping list from existing inventory items
- Add low-stock items to the shopping list
- Mark items as bought
- Clear completed items
- Share the shopping list

### Language Support

- Supports Thai and English
- Users can switch language directly from the app

### Mobile-Friendly Web App

- Designed for mobile usage
- Supports PWA-related setup such as:
  - `manifest.json`
  - theme color
  - Apple touch icon
- Can be used like a lightweight mobile web app

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- LocalStorage
- Tabler Icons

## Data Storage

This app stores data locally in the browser using `localStorage`.

No backend server or database is required.

Main localStorage keys:

- `hh4_items`
- `hh4_logs`
- `hh4_shoplist`
- `hh4_lang`
- `hh4_cats`

## Project Purpose

This project was created to practice building a practical, everyday-use web app with simple front-end technologies.

It focuses on:

- Clean and compact UI
- Mobile usability
- Household stock tracking
- Bilingual support
- Local data storage
- Practical user workflows

## Future Improvements

Possible improvements for future versions:

- Export / import data
- Barcode or QR code scanning
- Expiry date tracking
- Search function
- More detailed spending dashboard
- Cloud sync
- User accounts
- Better PWA offline support

## Credits

Built as a personal project with assistance from Claude for coding support, UI refinement, and feature iteration.
