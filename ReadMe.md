# Anime Music Recommender – Privacy Policy  
_Last updated: **APR 2025**_

## 1. Data We Collect
| Category | What exactly | Where it lives | Why we need it |
|----------|--------------|----------------|----------------|
| **AniList OAuth token** | The access token you approve when you log in | Stored **locally** in Chrome Sync Storage | To fetch your AniList profile (MAL IDs) |
| **Watch‑time feedback** | YouTube video ID, watch seconds, total duration | PostgreSQL DB hosted on Railway (🇺🇸/EU servers) | To improve song recommendations |
| **“Like” clicks** | Boolean flag per video | Same Railway DB | To prioritise favourite tracks |

We do **not** collect personal communications, financial data, or device fingerprints.

## 2. How We Use the Data
* Tokens are sent **only** to `graphql.anilist.co` to pull your list.
* Feedback & likes are used solely by our recommender at  
  `https://sideproject-production-fc87.up.railway.app`.  
  They are **never** sold, rented, or shared with third parties.

## 3. Retention
Data stays until you email us – at which point it’s deleted within 30 days.

## 4. Security
* All traffic is encrypted via HTTPS/TLS 1.2+.  
* Database access is limited to the backend service and CI deploy bot.

## 5. Your Choices
* Disconnect AniList any time in the popup (token is erased locally).
* Email us to request data export or deletion.

## 6. Contact
Questions? Write to artmusicasia@gmail.com
