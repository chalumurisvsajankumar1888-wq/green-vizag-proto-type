# Green Vizag – Smart Garbage Reporting and Tracking System

## Technologies
- HTML
- CSS
- Vanilla JavaScript
- Browser LocalStorage for demo data

No backend language or database is used in this prototype.

## Run the project
1. Extract the ZIP file.
2. Open the `Green-Vizag` folder in Visual Studio Code.
3. Open `index.html` in a browser. For the best experience, use the VS Code Live Server extension.
4. Create a citizen account using **Join us**.
5. Log in and submit a garbage report.
6. Copy the generated complaint ID and use **Track complaint**.
7. Open **Login** and use the demo administrator account to update statuses.

## Demo administrator login
- Email: `admin@greenvizag.demo`
- Password: `GreenVizag123`

## Important limitations
This is a front-end educational prototype:
- Data is stored in LocalStorage in the current browser only.
- Different users/devices do not share reports.
- Login is for demonstration only; passwords are not securely protected.
- Admin credentials are visible in the JavaScript source and must not be used for a real deployment.
- The app is not connected to GVMC or any official municipal system.
- Browser geolocation requires user permission and generally a secure context (HTTPS or localhost).
- Map links use OpenStreetMap; no Google Maps API key is required.

For a real public service, a secure server, database, verified authentication and an official municipal workflow would be required.
