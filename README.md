# Harsha ❤️ Jeeva — Chapter Two

Anniversary travel planner for GitHub Pages. Upload all files and the `assets` directory to a GitHub repository and enable Pages from the main branch root. Open the deployed HTTPS website in Safari on iPhone and choose Share → Add to Home Screen.

## Adding entries
Use the single **+ Add** button anywhere in the trip. Select a category (flight, car rental, stay, activity, food, or other) and the form adjusts. For an expense already incurred, select **Actual expense** under Planning status.

## Flights and car rentals
Flights support Round trip (default) or One way. A round trip records outbound departure and arrival, plus return departure and arrival, each with its own airports, dates, and local times. Rentals have pickup and drop-off dates, times, and locations; drop-off defaults to the pickup location. Both are stored as **one reservation**, shown as separate timeline events even if both happen on the same day, and counted **once** in the budget. Flight times are local to each airport.

## Storage
The app saves to browser localStorage under the same key as the earlier Wayfare/Our 2nd Anniversary version to preserve existing data on the same origin and browser. Back up regularly using Export backup; private browsing, browser clearing, device replacement, or a different domain can remove or separate this data. Supabase cloud sync is not yet implemented. Maps use OpenStreetMap and Google Maps external directions; Google Places photo integration is not included.
