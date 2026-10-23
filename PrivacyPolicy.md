# Bloomwater Privacy Policy

**Last updated:** October 23, 2026

Bloomwater ("the app") is developed by Tim (SoupFork Studios / OldManBOMBIN). This policy explains what the app does and does not do with your data.

## What the app stores on your device

Bloomwater keeps the following on your device, in storage private to the app:

- Your drink history (the amounts and times you log) and your daily goal.
- Your flower collection.
- Your settings: cup sizes, reminder preferences, and your chosen location (if you set one).
- The daily high temperature for your location, so each day keeps the water goal it had.
- The current and upcoming weather conditions for your location (wind, rain, cloud cover), for about a day ahead, so the app's scenery can match the weather outside.

None of this is sent anywhere except as described in the location and weather section below. No account or sign-in is required.

## Goal estimate

The "Estimate for me" button on the drinks screen can suggest a daily goal. It asks for a weight, and optionally for sex, pregnancy and nursing, all of which you can leave blank. The calculation happens on your device and the answers are not saved or sent anywhere. Only the goal you choose to use is kept, like any goal you type in yourself. The estimate is a general guide, not medical advice.

## Location and weather

On hot days the app can raise your daily water goal, and it can show the weather outside (clouds, wind, rain, snow, thunderstorms) as scenery behind your flower. To do either it needs a rough idea of where you are. You choose how:

- **City name or postal code.** The app looks these up in a list bundled inside the app. It covers US ZIP codes and postal codes in Poland, Germany, France, Spain and Portugal. The search happens on your device and nothing is sent to look it up.
- **Use my location.** If you tap this, Android asks for approximate (coarse) location permission. The app reads your approximate position once, only when you tap the button. It does not track you in the background.
- **Skip it.** Setting a location is optional. Without one the app works normally with your base goal and a default sky.

The app rounds coordinates to two decimal places (roughly one kilometer) before storing or sending them. To get the forecast, the app sends those rounded coordinates to forecast.soupforkstudios.com, a small server run by SoupFork Studios. The request contains the rounded coordinates and nothing else about you: no name, account, device ID, or drink data.

What the server does with a request:

- It turns the coordinates into a coarse map grid cell and keeps the hourly forecast for that cell (temperatures, wind, rain, cloud cover, and thunder or snow indicators) so the next request for the same area is fast. It stores the cell, the forecast, the time it was fetched, and the time it was last requested. It does not store who asked.
- It gets forecasts from the US National Weather Service (in the US) or MET Norway (elsewhere). Those services receive the server's requests for a grid cell, not your device's.
- It does not keep access logs. Your IP address is not written to disk. A short-lived counter held in memory limits how often one address can trigger new forecast fetches, to prevent abuse.
- Places that nobody has requested for 30 days are deleted.

If the server cannot be reached, the app may contact the US National Weather Service (in the US) or MET Norway directly, sending the same rounded coordinates. Like any internet request, that reveals your IP address to those services, which are governed by their own privacy policies.

## What the app does not do

- No advertising, and no data is shared with advertisers.
- No analytics, tracking, or crash-reporting SDKs are used.
- No accounts, and nothing is sold or shared for marketing.
- Your drink history and collection are never uploaded.

## Permissions used

- **Notifications:** to show your hydration reminders.
- **Exact alarms:** so reminders arrive at the times you set.
- **Run at startup:** so your reminders are set up again after you restart your phone.
- **Approximate location (optional):** only if you tap "Use my location", to find your area for the weather forecast.
- **Internet:** to fetch the weather forecast as described above.

## Data sources and credits

- **Forecast data:** [US National Weather Service](https://www.weather.gov) (public domain) and [MET Norway](https://api.met.no), licensed under [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). SoupFork Studios processes this data, reducing hourly forecasts to a daily high temperature and to simple hourly levels of wind, rain and cloud cover. This app is not endorsed by or affiliated with NOAA, the National Weather Service, or MET Norway.
- **Place names, postal codes and coordinates:** [GeoNames](https://www.geonames.org), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and the [US Census Bureau](https://www.census.gov) (ZIP code areas, public domain). The lists are trimmed and reformatted for this app.
- **Water needs:** the goal estimate is based on the European Food Safety Authority's reference values for total water intake.

## Deleting your data

You can remove your saved location from the location screen in the app. To delete everything the app stores, clear its storage in Android Settings or uninstall the app. Forecast data on the server is not linked to you, and unused places are deleted automatically after 30 days.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised.

## Contact

Questions about this policy can be sent to tim@soupforkstudios.com.
