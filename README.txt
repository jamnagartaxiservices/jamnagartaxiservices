JAMNAGAR TAXI SERVICES - STATIC WEBSITE
=======================================

A simple, fast, single-page website for Jamnagar Taxi Services.
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).
To view it, double-click index.html. (The map needs an internet connection.)

FILES
-----
index.html     Main page: header, hero, about, services, cars with rates, photo gallery, how it works, contact with map, footer
privacy.html   Privacy Policy
terms.html     Terms & Conditions
styles.css     All styling (colours are CSS variables at the top of the file)
assets/
  logo.svg          Your logo (about section and footer). It wraps the same image as
                    logo.jpg, so it is not a true vector file.
  logo.jpg          Same logo as a plain image
  favicon.png       Browser tab icon and header logo (the round emblem from your logo)
  taxi-branded.jpg  Branded taxi photo (hero and link preview, full size 1536x1024)
  car-dzire.jpg     White Dzire sedan
  car-innova-1.jpg  White Innova Crysta
  car-innova-2.jpg  White Innova Crysta (second photo)
  car-ertiga.jpg    Ertiga with flower garland
  fleet-dzire.jpg, fleet-rumion.jpg, fleet-ertiga.jpg, fleet-carens.jpg, fleet-innova.jpg, fleet-tempo.jpg
                    Car images used in the Our Cars rate cards

DETAILS USED ON THE SITE
------------------------
Business : Jamnagar Taxi Services
Phone    : 9824270752 (call and WhatsApp buttons)
Address  : Opposite S.T. Bus Stand, Summer Club Road, Jamnagar, Gujarat 361006
Hours    : Open 24/7
Privacy and Terms are dated 7 October 2026 and name the courts at Jamnagar, Gujarat.

CHOICES MADE FOR YOU (change in the HTML if needed)
---------------------------------------------------
- Services: local rides, outstation trips (Dwarka, Somnath, Rajkot, Ahmedabad are named as examples),
  airport and railway transfers, wedding cars, family and group travel, 24/7 booking.
- Cars and rates (per km): Swift Dzire Rs 10 (4 persons), Toyota Rumion Rs 13 (6), Ertiga Rs 12 (5),
  Kia Carens Rs 16 (5), Innova Crysta Rs 18 (7), Tempo Traveller Rs 33 (12). All shown as air conditioned.
  To change a rate or seat count, edit the matching card in the Our Cars section of index.html.
- A note under the cars says the final fare, toll, parking and waiting charges are confirmed at booking.
- No star ratings are shown, because no real customer ratings were provided.
- Cancellation: free before the driver leaves for pickup; charges may apply after that.
- Payment: the method is agreed at the time of booking.
- No email address is shown, because none was given.

HOW IT WORKS
------------
- Top bar with address and phone, sticky header with a Call button; anchor links scroll smoothly to each section.
- Car photos are always shown in full (never cropped). The gallery uses a blurred background of the same photo.
- On mobile (under 860px) the menu collapses behind a Menu button and a Call / WhatsApp bar stays at the bottom.
- The Poppins font loads from Google Fonts when online; without internet a clean system font is used instead.
- Sections fade in as you scroll.
- All "Book on WhatsApp" and WhatsApp buttons open a chat with 9824270752 and a ready message.
  The number is written as 919824270752 (India country code 91).
- "Get directions" opens Google Maps, and the contact section shows a map of the address.
- The footer year updates automatically.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/
