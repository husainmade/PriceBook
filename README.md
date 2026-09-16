# Price Book

A simple, fast and privacy-focused Android app for managing product prices.

Price Book helps you keep your product prices organized by **Category → Product → Cost → Unit**, making it easy to quickly check and update prices whenever you need them.

## ✨ Features

### 📂 Categories & Units

- Organize products into customizable categories.
- Add, edit or remove categories.
- Choose from flexible units of measurement.
- Create your own units when needed.
- Remember the last used category and unit for faster entry.

### 💰 Fast Price Reference

- Store product prices in one place.
- Quickly check the latest price of any product.
- Keep different products and variants organized.
- View price changes over time.

### 🔎 Instant Search

- Search products instantly by name.
- Search works across your saved product list.
- Quickly find the price you need without browsing through categories.

### ↕️ Sort Products

Sort products using multiple options, including:

- Price — Low to High
- Price — High to Low
- Date — Added, Newest First
- Date — Added, Oldest First
- Date — Updated, Newest First
- Date — Updated, Oldest First

### ➕ Easy Product Management

- Add products manually.
- Edit product details and prices.
- Update existing prices without creating duplicate entries.
- Record pricing with the relevant date.
- Keep product information organized and easy to review.

### ⚡ Quick Price Update

- Double-tap any product entry to quickly update its price.
- Enter a new price and date without going through the full product-edit workflow.
- Useful when supplier prices change frequently.

### 📷 Add Pricing from Photos

Add product pricing directly from bills or invoices using your **Camera** or **Gallery**.

#### On-device OCR

Price Book includes on-device OCR for reading:

- Item
- Rate
- Unit

Images from the Camera and Gallery can be cropped and rotated before processing.

Detected pricing is shown for review before anything is added to your Price Book.

#### 🤖 AI Bill Extraction

For more advanced bill and invoice extraction, Price Book can optionally use AI.

AI Bill Extraction can extract:

- Product name
- Unit
- Rate
- Discount (%)
- GST (%)

The extracted information is processed through the existing **Review Products** workflow, allowing you to check and edit the detected products before adding them.

AI extraction also calculates the resulting cost using the extracted rate, discount and GST where applicable.

> Always review AI-extracted information before adding it to your Price Book.

### 🔌 Multiple AI Providers

AI Bill Extraction supports multiple providers:

- Groq
- Google Gemini
- OpenAI
- HF / OpenAI-compatible providers

You can configure providers individually using their respective API key or token.

Each provider has its own:

- API key/token
- Model selection
- Usage and limits information
- Data & privacy information

### 🔄 Automatic Model Selection

Price Book supports **Automatic** model selection.

When available, Price Book can retrieve the provider's currently available models instead of relying only on a fixed model list.

You can also manually select a specific supported model when required.

### 🔁 Automatic Provider Fallback

When using Automatic provider selection, Price Book can try another configured provider when the selected provider cannot process the request because of applicable availability or usage limitations.

This allows AI Bill Extraction to continue when another configured provider is available.

### 🔐 AI Provider Data & Privacy

AI Bill Extraction is optional.

Your original photo stays on your phone. **Only the crop you confirm is sent to the selected AI provider.**

For better privacy, crop tightly around the product table before confirming the image so unrelated supplier, customer or total information is not included.

Provider data handling can vary:

- **Groq:** Inference data is not retained by default. GroqCloud also provides Zero Data Retention (ZDR) controls for additional protection.
- **Google Gemini:** Google currently states that Gemini API Free Tier content may be used to improve its products.
- **OpenAI:** Data is handled according to the current OpenAI API data-use and retention policies.
- **HF / OpenAI-compatible:** Data handling depends on the selected provider or endpoint.

Review the selected provider's current policies and terms before processing sensitive information.

API tokens are encrypted using the Android Keystore and stored separately for each AI provider.

### 📊 Price History

- Keep a history of product prices.
- Track when prices were added or updated.
- View previous prices for the same product.
- Useful for comparing supplier pricing over time.

### 📈 Insights

Get useful information from your saved pricing data, including price changes and other product-level insights.

### 🔍 Similar Items

- Find products with similar names or details.
- Helps identify possible duplicate entries.
- Review similar products before adding new entries.

### 🗑️ Recycle Bin

- Deleted products are moved to the Recycle Bin.
- Restore products when needed.
- Permanently remove unwanted entries.

### 📊 Excel Backup & Restore

- Export your Price Book data to Excel.
- Keep an offline backup of your product and pricing data.
- Restore your saved data when needed.

### 📱 Widgets & Shortcuts

Use home-screen widgets and shortcuts for faster access to common actions.

Available shortcuts/widgets include:

- Search
- Add Manually
- Scan with Camera
- Scan from Gallery

The Search widget can open the Price Book search field directly.

### 👆 Gesture Controls

Quickly access common actions using gestures.

- Swipe gestures for navigation
- Double-tap for Quick Price Update
- Other supported gestures are available within the app

### 💡 Tips

A dedicated Tips section provides useful information about Price Book's features and workflows.

### 🎨 Material You Design

- Built using modern Android design principles.
- Supports Android dynamic colors.
- Choose between:
  - System
  - Light
  - Dark
- Interface adapts to your device appearance settings.

### 📶 Works Offline

Price Book is designed to remain fully usable offline for its core features.

- Your product and pricing data stays on your device.
- Manual product entry works offline.
- Search and sorting work offline.
- Price history and insights work offline.
- Backup and restore work locally.
- Built-in on-device OCR does not require an internet connection.

**AI Bill Extraction is optional and requires an internet connection when enabled.**

If AI Bill Extraction is disabled, Price Book's normal features continue to work fully offline.

### 🔒 Privacy

Price Book does not require an account or sign-in.

Your normal product catalog and price data are stored locally on your device.

There is no cloud dependency for the core Price Book features.

Photo-based pricing using the built-in on-device OCR is processed locally and does not require an online service.

When **AI Bill Extraction** is enabled:

- The original photo remains on your device.
- Only the crop confirmed by you is sent to the selected AI provider.
- AI processing requires an internet connection.
- The AI provider's own data policies, retention rules and usage limits apply.
- API tokens are encrypted using Android Keystore.
- Each provider's token is stored separately.

Price Book does not set or control AI provider quotas, rate limits or charges.

### 📦 Simple & Lightweight

Price Book is designed to stay focused on its core purpose:

**Quickly record, organize and reference product prices.**

AI Bill Extraction is an optional feature and does not replace the normal offline Price Book workflow.

## 🏪 Ideal For

Price Book can be useful for anyone who regularly needs to maintain and reference product prices, including:

- Retailers
- Shopkeepers
- Wholesalers
- Traders
- Purchase teams
- Small businesses
- Anyone who wants a simple personal price reference

The default categories and units are fully customizable, so the app can be adapted to different types of businesses.

## 📱 Screenshots

| Home | Add Pricing from Photo |
|---|---|
| ![Home](screenshots/home.jpg) | ![Photo Pricing](screenshots/photo-pricing.jpg) |

| Insights | Price History |
|---|---|
| ![Insights](screenshots/insights.jpg) | ![Price History](screenshots/price-history.jpg) |

| Similar Items | Recycle Bin |
|---|---|
| ![Similar Items](screenshots/similar-items.jpg) | ![Recycle Bin](screenshots/recycle-bin.jpg) |

> **Note:** Screenshots are for illustration purposes. Product names, prices and other values shown are for demonstration purposes and may not represent actual current prices. The UI may have been improved or updated in newer versions, so some screens may differ slightly from the current version. UI examples are intended to demonstrate the app's features and workflow.
Screenshots below show the current Price Book interface and its major features.

## 📥 Download

[Download the latest APK](https://github.com/husainmade/PriceBook/releases)

## 🔐 Source Code

Price Book is currently distributed as a closed-source application.

This repository is provided for releases, documentation and project information.

## 💬 Feedback

Found a bug or have a suggestion?

Open an issue in the [Price Book GitHub repository](https://github.com/husainmade/PriceBook/issues) and include as much detail as possible.

For bug reports, please include the steps needed to reproduce the problem and, when possible, screenshots or other relevant details.

## 👨‍💻 Developer

**Husain**

© 2026
