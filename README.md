# RentNest

A browser-based rental property portal using the listings in `properties.json` and 40 supplied room photos.

## Run locally

The site loads its processed listing data from `properties.json`, so open it through a local web server instead of opening `index.html` directly. From this folder, run:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Included modules

- Renter registration and login, with renter/admin role selection
- Listing search with location, rent, bedroom, and property type filters
- Saved homes, property photos, property details, and owner enquiry interaction
- Booking requests with a dedicated booking history page
- Light and dark themes with a saved browser preference
- Preferences based property recommendations
- Area rent estimates calculated from comparable dataset listings
- Demand and inventory analytics derived from all loaded listings
- Listing management with browser-local add/remove actions

Accounts, preferences, booking requests, and listing changes are demonstrations stored in the current browser's local storage. Booking history is not shared across browsers or devices; the app has no server-side authentication or database. Forty supplied room photos are distributed evenly across all listings. The current `properties.json` contains 600 listings; provide an updated dataset to display 1,000.
