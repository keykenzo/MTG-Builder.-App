# MTG Deck App 🃏
[![Swift Version](https://img.shields.io/badge/Swift-6.0-orange.svg)](https://swift.org)
[![iOS Version](https://img.shields.io/badge/iOS-18.0%2B-blue.svg)](https://apple.com/ios)

This is an MTG Deck App, a project that lets Magic: The Gathering players browse card collections, build decks, check card prices, and enjoy a fully optimized dark mode experience.

## 📸 Screenshots

### Highlights

| Card Browser | Deck Builder | Card Prices |
|:---:|:---:|:---:|
| <img src="MTGDeckApp/Screenshots/browse.png" width="200"> | <img src="MTGDeckApp/Screenshots/deckbuilder.png" width="200"> | <img src="MTGDeckApp/Screenshots/prices.png" width="200"> |

### Complete Gallery

Here you can see the app in action:

<p align="left">
  <img src="MTGDeckApp/Screenshots/browse_list.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/card_detail.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/deck_stats.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/mana_curve.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/search.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/price_history.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/collection_sets.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/deck_export.png" width="200" hspace="5">
</p>

#### 🌙 Dark Mode & Extras

<p align="left">
  <img src="MTGDeckApp/Screenshots/browse_dark.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/deckbuilder_dark.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/card_detail_dark.png" width="200" hspace="5">
  <img src="MTGDeckApp/Screenshots/prices_dark.png" width="200" hspace="5">
</p>

> [!TIP]
> <img src="MTGDeckApp/Screenshots/presentation.gif" width="200">

## ✨ Features

- [x] Card Browser: Explore all Magic: The Gathering sets and collections with powerful filters by color, type, rarity, and CMC.
- [x] Deck Builder: Build and manage your decks with real-time mana curve and color distribution stats.
- [x] Card Prices: Check market prices in real time and track price history for any card.
- [x] Real-time Search: Quickly find any card by name, text, or type with a dynamic search bar.
- [x] Dark Mode Support: Fully optimized for both Light and Dark appearances.

## 🛠 Technologies and Tools

- **Language:** Swift 6.0
- **Interface:** SwiftUI
- **Architecture:** MVVM
- **Card Data:** Scryfall API
- **Pricing:** TCGPlayer / CardMarket API
- **Key Concepts:** async/await, Combine, SwiftData

## 🚀 How to run the project

1. Clone Repository:
   ```bash
   git clone https://github.com/seu-usuario/MTGDeckApp.git
   ```

2. Open in Xcode:
   ```bash
   cd MTGDeckApp
   open MTGDeckApp.xcodeproj
   ```

3. Add your API keys in `Config.swift`:
   ```swift
   let scryfallBaseURL = "https://api.scryfall.com"
   let tcgPlayerAPIKey = "your_key_here"
   ```

4. Select your simulator or device and press **Run** (`⌘R`).
