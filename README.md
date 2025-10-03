# Airport Timing Tracker

Track flight timings to maximise duty-free shopping time.

## CSV Columns

- **Date**: Flight date (YYYY-MM-DD)
- **Destination**: Type of flight
  - `Domestic` - Within country
  - `Short haul` - Under 4 hours
  - `Long haul` - Over 4 hours
- **Scheduled Departure**: Official departure time
- **Bag Check Close**: When bag drop closes
- **Security Check (mins)**: Time to get through security
- **Gate Announced**: When gate number appears on boards
- **Time to Gate (mins)**: Walking time from duty-free to gate
- **Gate Closes**: When boarding ends
- **Actual Departure**: When plane actually leaves
- **Security to Gate Time**: Total time from security to gate announcement
- **Duty Free Available (mins)**: Shopping time between gate announcement and gate closing

## Key Insights

The critical window for duty-free shopping is between:
1. Gate announcement time
2. Gate closing time (minus walking time to gate)

Track multiple flights to identify patterns by destination type and optimise your airport experience.