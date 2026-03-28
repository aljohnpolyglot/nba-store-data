# 🏀 NBA Commissioner Master Asset Database

This is an encrypted procurement list of official NBA assets scraped for the Commissioner's Simulator. 

## 📂 Included Categories
- Jerseys, Footwear, Shorts, Hoodies, Hats, T-Shirts, Accessories, Collectibles, Hardwood Classics.

## 📊 Data Structure (Schema)
Every object in the JSON array uses these exact keys:

| Key | Description |
| :--- | :--- |
| `title` | Full product name |
| `price` | Price in USD (String) |
| `img` | Direct image link (frgimages CDN) |
| `link` | Original store.nba.com product link |
| `category` | Injected during merger (e.g., "Jerseys") |

## 🛠 Usage
This Gist's uses `raw` URL to populate the NBA Commissioner Store UI.
