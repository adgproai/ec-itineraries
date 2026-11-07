# Experiences Caribbean · Guest Itineraries

Live at https://trips.experiencescaribbean.com

- `index.html`: the whole app. Staff build itineraries (sign-in with the Itineraries tick on the incident register's Team page); guests open their link `?t=<code>`.
- Data, sign-in and access rules: Supabase project TravelLife (migration `itinerary_001`).
- Photos and logo load from experiencescaribbean.com's media library.
- TourOps can open the editor with a booking pre-filled: `#tourops=<base64url JSON>` (format in the project doc `TourOps-Create-Itinerary-Prompt.md`).

To update the site, replace `index.html` and push to `main`.
