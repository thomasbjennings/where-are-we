# where are we

A small web app that tells you what town you're standing in.

Open it, allow location, and it shows the municipality you're in right now, along with the county, state, and ZIP code. Where the data exists, it also shows your school district and high school, your legislative and congressional districts, and, in New York City, your neighborhood. A map shows your position, and the app keeps a list of the towns you've visited.

It's a web page, not an App Store app. Nothing to download from a store, no account, no sign-up.

**Open it here:** [thomasbjennings.github.io/where-are-we](https://thomasbjennings.github.io/where-are-we/)

## Where it works

The app only knows the places it has boundary data for:

- **New Jersey**: towns, counties, ZIP codes, school districts and high schools, state legislative and congressional districts
- **New York**: towns, cities, villages, counties, and school districts, plus neighborhoods in New York City
- **Connecticut, Massachusetts, New Hampshire, Vermont, Maine, Pennsylvania, North Carolina, and Arizona**: towns, cities, and counties

Anywhere else, it won't be able to name your town.

## Your location stays on your phone

- Your location is read by your browser and used **only on your device**. It is never sent to me or to any server.
- The list of towns you've visited is saved in your browser's own storage, on your phone. No one else can see it. Clearing your browser's website data erases it.
- There are no accounts, no ads, no analytics, and no tracking.

## How it works

The first time you use it in a state, the app downloads that state's public boundary maps (town lines, county lines, ZIP codes, and so on) from official government sources such as the U.S. Census Bureau and the State of New Jersey. It saves them on your phone, so after that, figuring out which town you're in happens on the device itself, without asking anyone.

The page and the background map tiles (from OpenStreetMap) still need an internet connection to load.

Near a town line, GPS can be off by a few dozen feet, so the app may briefly show the neighboring town.

## Add it to your home screen

Adding it to your home screen makes it open full screen, like a regular app.

### iPhone or iPad

1. Open the link in **Safari**. (Other browsers on iPhone may not offer this option.)
2. Tap the **Share** button, the square with an arrow pointing up.
3. Scroll down and tap **Add to Home Screen**, then **Add**.
4. Open it from the new icon and tap **Allow** when it asks for your location.

If it never asks, or you tapped "Don't Allow," go to **Settings → Privacy & Security → Location Services → Safari Websites** and choose **While Using the App**.

### Android

1. Open the link in **Chrome**.
2. Tap the **⋮** menu in the top-right corner.
3. Tap **Add to Home screen** (on some phones it says **Install app**), then **Add**.
4. Open it from the new icon and tap **Allow** when it asks for your location.

If you blocked location by mistake, open the page in Chrome, tap the icon to the left of the address, then **Permissions → Location → Allow**.

---

Made by [Thomas Jennings](https://thomasjennings.org).
