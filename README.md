# RentNest

A browser based rental property recommendation portal built from `rental_properties_600.csv`.

## Run locally

The site loads its processed listing data from `properties.json`, so open it through a local web server instead of opening `index.html` directly. From this folder, run:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Included modules

- Renter registration and login, with renter/admin role selection
- Listing search with location, rent, bedroom, and property type filters
- Saved homes, property details, and owner enquiry interaction
- Preferences based property recommendations
- Area rent estimates calculated from comparable dataset listings
- Demand and inventory analytics derived from the supplied 600 rows
- Listing management with browser-local add/remove actions

Accounts and listing changes are demonstrations stored in the current browser's local storage. The app has no server-side authentication or database.
