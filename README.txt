# OoruBites — Chennai street-food discovery frontend (v3)

## Two separate demo sign-ins
Customer:
- Email: customer@oorubites.in
- Password: Ooru@123

Vendor:
- Email: vendor@oorubites.in
- Password: Vendor@123

The sign-in modal now shows two clear role cards: **I'm a customer** and **I'm a vendor**. Select the correct role, then use the matching demo account or create a browser-local account.

## Customer flow
Sign in as customer -> browser asks for location permission -> reverse-geocoding attempts to suggest the Chennai neighbourhood -> user confirms/selects area -> browse area-wise shops, photos, menus, prices, parcel charges, shop count and reviews -> rate individual food items or the overall shop.

## Vendor flow
Sign in as vendor -> vendor form opens -> enter shop name, category, area, full address, landmark, opening hours, phone, shop image, menu item names, prices, parcel charges and optional food image URLs -> save. Vendor can click their avatar to edit their shop profile.

## Images
The sample shop cards use food photography from Unsplash as illustrative images. They are not verified photographs of the named businesses. Vendors can upload their actual shop photo; food item images can be supplied as image URLs in this prototype.

## Run
Extract ZIP -> open folder in VS Code -> run index.html with Live Server. Geolocation requires localhost or HTTPS.

## Limitations
Frontend-only prototype. Authentication, vendor profiles, photos, reviews and ratings are saved only in the current browser LocalStorage. No shared database, server-side validation, secure authentication or real moderation. Starter shop data, public ratings, menus, hours and exact addresses need field verification. Reverse geocoding uses the public Nominatim endpoint and may not always identify a Chennai area accurately.
