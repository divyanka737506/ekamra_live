# Ekamra Live · Events in Bhubaneswar

A responsive event management website where people can explore upcoming events in Bhubaneswar, read the details, and register for the ones they like. It is themed around the Temple City, with a Konark wheel, a temple skyline and a sun-to-moon journey as you scroll.

## Features

**Core**
- Hero section introducing the platform, with a typing headline and a countdown to the next event
- Featured events (the three soonest) and a full event list with Upcoming, Recently held and All views
- Event cards showing name, date, venue, image and a short description
- Search by name, venue, description or category, plus category filter chips
- Event details popup with highlights, schedule, organiser, price and live seats-left bar
- Registration form collecting name, email, phone number and the selected event (locked to the event you opened), plus number of seats
- JavaScript validation: name format, email format, 10-digit Indian mobile number, duplicate email per event, and seat limits
- Confirmation message after registering
- Fully responsive across phones, tablets and desktops, with a mobile menu

**Bonus**
- Dark and light mode, remembered between visits
- Event countdown timer
- Registrations saved with Local Storage, shown under "My tickets" with a cancel option
- Animations: respects the "reduce motion" setting

**Motion extras**
- Temple door-opening intro with a rising sun (plays once per visit, skippable)
- Sky that changes from sunrise to dusk to night as you scroll, with a moving sun and moon
- Konark wheel scroll tracker that also works as a back-to-top button
- Lanterns and fireflies in dark mode
- Marigold cursor trail and magnetic buttons (desktop only)
- Event card expands into the details popup
- Rolling section headings and count-up numbers
- Ticket-print animation with a CONFIRMED stamp, a rangoli drawing itself and falling petals

## Tech stack

- HTML5, CSS3 and vanilla JavaScript (no frameworks or build step)
- Google Fonts (Fraunces and DM Sans)
- Git and GitHub for version control, GitHub Pages for hosting

## Notes

- The events are sample data created for demonstration. Their dates are set relative to today's date, so the site always shows upcoming events.
- Registrations are stored only in the visitor's own browser (Local Storage). No data is sent to a server and no email is sent.
- Some event photos load from Wikimedia Commons and need an internet connection. If a photo fails to load, a drawn poster is shown instead.

## Author

Built as a student project by Divyanka Dutta.
