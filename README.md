# Sunrise Hotel Room Booking and Billing System

**Admission number:** CT100/G/25039/24  
**Individual requirement 9:** Optional late checkout for KSh 2,000.

A responsive hotel booking prototype with a luxury navy-and-gold landing page, room cards, a booking form, live JavaScript bill estimate, and PHP confirmation. PHP validates the submitted data again and independently calculates the bill using server-side rates.

## Run with XAMPP
1. Extract this folder into `C:\xampp\htdocs\CT100_G_25039_24_HotelRoomBooking` (or your chosen folder under `htdocs`).
2. Start **Apache** in the XAMPP Control Panel. MySQL is not required by this version because bookings are not saved to a database.
3. Open `http://localhost/CT100_G_25039_24_HotelRoomBooking/` in your browser.
4. Select **Book your stay**, complete the form, and submit it to test the PHP confirmation page.

## Project files
- `index.html` — responsive homepage with room cards and prices.
- `booking.html` — booking form and live price summary.
- `booking.js` — browser-side validation, room capacity, room preselection and bill estimate.
- `process_booking.php` — server-side validation, independent bill calculation and confirmation.
- `style.css` — shared responsive navy-and-gold design.
- `screenshots/` — original sample SVG mockups.

## Rates and limits
- Single room: KSh 3,500 per night; capacity 1.
- Double room: KSh 5,000 per night; capacity 2.
- Family room: KSh 7,500 per night; capacity 4.
- Breakfast: KSh 700 per guest per night.
- Airport transfer: KSh 2,000 per booking.
- Late checkout (requirement 9): KSh 2,000 per booking.
- Nights: 1–14; phone number: exactly 10 digits.

Room photography and web fonts use external URLs and therefore need an internet connection. This is a demonstration project: submitted bookings are displayed in a confirmation page but are **not stored in MySQL**.
