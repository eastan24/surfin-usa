# surfin-usa Product Brief

## Purpose
Help surfers of any skill level decide one thing: **"Should I surf today, and where?"**

The app shows the conditions a surfer needs (waves, swell, wind, tide, weather, water temperature), puts spots on a map, and highlights popular spots. The surfer makes the final call; the app makes the information easy to read.

This is a learning project for building a full-stack app that can handle many users. It is not planned as a market launch.

## Audience
Surfers at every level:
- **Beginners** who don't know how to read a forecast or which spot suits them
- **Intermediate surfers** choosing between spots and tracking their progress
- **Experienced surfers** who want accurate conditions and alerts for specific spots

## Coverage
All US coasts:
- West Coast
- East Coast
- Gulf Coast
- Hawaii
- Alaska
- Territories such as Puerto Rico
- Possibly the Great Lakes later

Launch with a few famous spots per region and grow the list over time. There is no good free nationwide spot dataset, so the spot list will be built by hand.

## Surf domain primer
What surfers check before going out:
- **Wave height:** how big the waves are
- **Swell period:** seconds between waves; longer means more powerful
- **Swell direction:** each spot only works with certain directions
- **Wind:** offshore (blowing out to sea) gives clean waves; onshore makes them messy
- **Tide:** many spots only work at certain tides
- **Water temperature:** decides wetsuit choice
- **Weather, sunrise and sunset**

Traits of each spot:
- Break type (beach, reef, point)
- Skill level it suits
- Best swell direction, tide, and wind
- Hazards (rocks, rip currents, crowds)
- Parking and facilities

Coasts behave differently: the Pacific gets distant-storm swell, while the Atlantic is more wind- and hurricane-driven. "Good conditions" must be defined per region or per spot, and times must be shown in the spot's local time zone.

## Features

### v1: Core
- Conditions for each spot (waves, swell, wind, tide, weather, water temperature)
- Interactive map of spots
- Popular spots grouped by region
- **Surf score** by skill level, with a plain-English reason (for example, "Small and clean, good for beginners")

### v2: Accounts
- User accounts
- Favorite spots
- Alerts when a favorite spot turns good

### v3: Community and tracking
- Session log with the day's conditions attached automatically
- User surf reports with photos (crowd level, current conditions)

### Anytime
- Safety info: rip current and surf advisories, beach water quality and closures
- Beginner glossary explaining surf terms

## Open questions
- Where will the spot list and spot traits come from, and how will they be seeded?
- Which data sources provide conditions for each region (NOAA is the likely base)?
- How should "good" be defined for each region and skill level?
- Great Lakes: include or not?

## Out of scope
- Selling or marketing the app
- Real-time chat or social feeds
- Booking lessons or gear
