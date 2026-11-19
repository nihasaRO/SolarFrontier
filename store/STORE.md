# Solar Frontier: Connect IQ Store listing

## App name
Solar Frontier

## Short description
An adventure watch face that shows what matters next.

## Description (paste into the store)

YOUR WEATHER, LIGHT AND TRAIL, AT A GLANCE.
A free adventure watch face for the Instinct 3 Solar (45 and 50 mm), drawn pixel by pixel for its screen. A big, clear time, every other zone yours to fill, and one line that thinks ahead for you.

CONTEXT: ONE LINE THAT WATCHES THE SKY
Context shows the one message most likely to change what you do next, and stays quiet when nothing does:
- "TSTORM ~16:00": a thunderstorm in the forecast, hours before it arrives.
- "GUST ~72 KMH": strong gusts expected within the hour.
- "RAIN ~30M" / "DRY ~25M": when the rain starts or stops ("RAIN BY 16:00" where the forecast is hourly).
- "LIGHT 0:25": daylight left before sunset.
- "HEAT 41°", "WINDCHILL -30°", "FREEZING RAIN", "FOG 0.3 KM": act now.
- "TO 9° BY 15:00", "SNOW >1800 M", "BARO FALLING": a cold front, snow just above you, storm signs (even offline).
- "DRY 12H+": nothing to worry about.
The "~" means forecast: the face never pretends to know the minute.

ONE FACE, ARRANGED YOUR WAY
74 metrics and 631 options, all set on the watch itself or in Garmin Connect:
- Circle: 16 views, from the weather now, next 3 hours or tomorrow to the moon, wind or seconds.
- Top lines: a status icon (alarm, Bluetooth, pressure drop and more), the date in 7 formats or a metric, a number with its own bar.
- Line 3: any of 48 metrics, or Context, or one metric in large type.
- Two side gauges, as bars or blocks.
- Two layouts: three progress rows, or three columns with a history chart (8 sources over 1, 3 or 4 hours).
- Wrist raise adds exact values.
- Your style: dark or light theme, solid, outlined or dithered minutes, three colon styles, 12 or 24 hours.

BUILT FOR THE OUTDOORS
- Weather: feels-like, wind and Beaufort force, gusts, rain chance and amounts, snow, freezing level and the margin to your altitude, visibility, UV, air quality (European or US index), pollen (Europe).
- Light: sunrise and sunset, first and last light, golden hour, day length, moon phase.
- Terrain: altitude, barometric pressure and its trend, metres climbed and descended.
- Body: heart rate and zone, Body Battery, stress, breathing, Pulse Ox, steps, floors, intensity minutes.
- Watch: battery and days left, solar intensity, notifications, and a countdown to a date or a daily time.

WEATHER: OPEN-METEO OR GARMIN
Open-Meteo is the default. Garmin's weather gives only the current conditions: temperature, feels-like, today's high and low, rain chance, wind and humidity. Everything forecast-based needs Open-Meteo (free, no account, no data collected): Next 3 Hours, Tomorrow, rain and dry timing, thunderstorms, gusts, UV, visibility, air quality, pollen, freezing level, snow, and most of Context.
It downloads through your phone (every 5 to 60 minutes) and needs a known position: your GPS, Garmin's weather position or your last activity.

IF THE WEATHER DOESN'T SHOW
The Next 3 Hours and Tomorrow circles show the reason:
- NO GPS: no position yet. Run an outdoor GPS activity for a minute.
- NO DATA: no forecast yet. Wait for the next update.
- ERR-104: the watch can't reach your phone (Bluetooth off, or Garmin Connect closed).
- ERR-2 or ERR-300: the phone or the internet didn't answer in time. It retries.
- ERR-402 or ERR-403: the forecast was too large for the watch's memory. Please report it.
- ERR429: too many requests to Open-Meteo. It clears by itself.
- ERR500 to ERR503: Open-Meteo is busy. It retries in 5 minutes.
"AIR ERR" with a number means the same for the air-quality request.

GOOD TO KNOW
- The face cannot vibrate or sound an alarm. Context and the pressure-drop icon are indications, not official warnings; the Instinct's own storm alert remains the alarm.
- Weather data by Open-Meteo.com (CC BY 4.0). Air quality and pollen: Copernicus Atmosphere Monitoring Service (CAMS) via Open-Meteo.
- Permissions: health data, location (sun times, weather), background and internet (Open-Meteo only).

A personal project, built with the help of AI and shared for free.

## What's new

WHAT'S NEW
- Context sees more coming: a cold front later today ("TO 9° BY 15:00"), a very different tomorrow ("TMRW HIGH 6°", in the evening), snow just above you while it rains ("SNOW >1800 M"), and storm signs from the watch's barometer ("BARO FALLING"), which work without a phone or signal.
- More accurate timing: the 3-hour rain chance and the gust warning only look at the hours ahead, and outside Central Europe and North America "DRY BY" is no longer an hour late.
- No more blank weather at midnight: tomorrow's high and low become today's until the next update.
- The chart comes back about 3 seconds after you leave a menu, instead of when the watch goes back to sleep.
- Wrist raise detail now works in the Rows layout too: the exact gauge values appear at the ends of the line under the time.
- With Garmin weather, Next 3 Hours and Tomorrow now say OPEN METEO instead of showing dashes, since those two need it.
- Fixed: the watch menu could fail when scrolling past the last colon style.
- Lighter: the moon, the wind arrow and other small shapes now come from the font, and fewer readings happen inside each minute's redraw. Even with the new warnings, the face has more memory to spare than before. The moon now changes in steps (16 phases on the circle, 8 on line 1) and the wind arrow points in 16 directions.
- New installs start with Open-Meteo weather (every 15 minutes), the Chart layout with the 3-hour heart rate, and Context on line 3. If you already use the face, your settings stay as they are.

Version history:
- 1.9.18 Context: a cold front within 3 hours by day (5° colder or more), tomorrow's high from 17:00 when it is 8° away from today's, the snow line (about 300 m below the freezing level, shown while it rains and when it is less than 800 m above you), and storm signs (more than 3 hPa lost in 3 hours, read at wrist raise). Wrist-raise gauge values in the Rows layout too. The chart is rebuilt about 3 seconds after a menu, not at the next sleep.
- 1.9.17 Lighter: the moon, the wind arrow, the high/low triangles and the colon are now drawn from the icon font instead of code (the moon in 16 phases on the circle, 8 on line 1; the arrow in 16 directions), freeing about 0.6 kB of the watch's app memory.
- 1.9.16 Weather no longer goes blank at midnight: tomorrow's high and low become today's until the next update. Rain chance and gusts look at the hours ahead (the hour that just ended no longer counts). Outside Central Europe and North America, rain and dry times follow the hour in progress, so "DRY BY" no longer runs an hour late. With Garmin weather, Next 3 Hours and Tomorrow say they need Open-Meteo instead of showing dashes. Fixed a menu fault past the last colon style. New installs start with Open-Meteo weather (every 15 minutes), the Chart layout with the 3-hour heart rate chart, and Context on line 3 (existing settings stay as they are). Lighter: fewer sensor reads inside the minute's redraw, and the settings menu's tables only use memory while the menu is open.
- 1.9.15 Lighter at busy moments: the 3-hour pressure trend, stress and Body Battery are read when you raise your wrist or the watch goes to sleep, not inside the minute's redraw; after the settings menu, the chart refills a few seconds later. The air-quality gauge shows GOOD as a first segment (it looked empty before) and its number is the level (1-6).
- 1.9.14 Context gets air quality on its own, so its air warnings work without an air metric on the face; the option is now simply called "Air quality".
- 1.9.13 In North America, air quality uses the US index and its words (GOOD to HAZARDOUS); a short break in the rain no longer counts as dry (the next 75 minutes, or the next hour, must stay dry too).
- 1.9.12 Gusts warned before they arrive: Context now also uses the strongest gust forecast for the coming hour ("GUST ~72 KMH"), plus a Gusts next hour metric. To make room: the Body Battery 2-hour change, the solstice/equinox countdown and the Diamonds colon are removed (their slots show Body Battery and the next hour's gusts).
- 1.9.11 Steadier: one activity read per redraw, and one pass over the hourly forecast for snow, rain amounts and thunderstorms.
- 1.9.10 Fix: a crash outside Central Europe and the US when Context showed a rain or storm time ("RAIN BY 16:00").
- 1.9.9 Thunderstorm warnings from the forecast's thunderstorm codes: act now within the hour, ahead of its own rain within 2 hours, and a forecast within 6 hours ("TSTORM ~16:00"); a T-storm forecast metric and a Thunderstorm circle view. The second time zone (with Zulu) is removed to make room; its slots show the thunderstorm forecast.
- 1.9.8 Lighter: the thunderstorm-potential metric (storm energy, not a storm forecast) is replaced by metres descended in the same slots; the second time zone is calculated without a date object; the countdown's day and year are plain lists in the watch menu.
- 1.9.7 Three more act-now messages: HEAT (feels-like 40°+ or 38° in the shade), WINDCHILL (feels-like -28° or below), SNOW + GUSTS (snow with gusts of 56+ km/h).
- 1.9.6 Freezing rain warned an hour ahead ("ICE RAIN ~1H"), and hourly rain timing from the forecast amount (0.3 mm), so light drizzle codes no longer trigger rain messages.
- 1.9.5 Honest rain timing outside Central Europe and the US ("RAIN BY 16:00": the forecast there is hourly), and BMNT/EENT, the position and sun elevation replaced by visibility, rain in the last hour and tonight's low in the same option slots.
- 1.9.4 Context is more honest: fog only from a fog code (dense fog under 400 m first, FREEZING FOG below 0°), freezing rain only from its codes, no thunderstorm from storm energy alone, and "SETS 20:25" / "RISES 06:10" without weather.
- 1.9.3 The right side gauge moved 2 px inward, so it is no longer cut off by the bezel on the 45 mm Instinct 3 Solar.
- 1.9.2 Seconds in the circle after a wrist raise, with the dotted ring filling over the minute.
- 1.9.1 Context is about weather and light only (Body Battery removed); during steady rain it shows how much is still to come ("RAIN +14MM"); leaner Context code.
- 1.9 Context ordered by what to act on; approximate rain and snow timing with snow from the forecast; compact on-watch menu with current values; allocation-free clock.
- 1.8 Rain and snow start and stop times up to 12 hours ahead, Context, daily countdown.
- 1.7 Six European air-quality levels, Beaufort wind force, clearer thunderstorm-potential and pressure-drop wording, countdowns up to 2045.
- 1.6 Pressure in inHg, wind in knots, a month/day date format, rain and snow units that follow the temperature setting; watch temperature and side gauges always fill; internal optimisations.
- 1.5 Memory and stability: single-screen settings menu, wind compass, side-gauge fix.
- 1.4 Big text mode, 1/3/4-hour charts, smoother charts while resting.
- 1.3 Open-Meteo (no API key): thunderstorm potential, pollen, freezing level, snow, UV maximum, rain today.
- 1.2 Air quality, precipitation timing, Body Battery trend, sun elevation, chart minimum and maximum on wrist raise.
- 1.1 Countdown, intensity goal, new metrics.
- 1.0 Initial release.

## Store assets in this folder (regenerate with: python3 tools/store_assets.py)
- app-icon-500.png: the app icon (cover), 500 x 500 px, both layouts and both gauge styles, no text. Orange variant: app-icon-500-orange.png.
- hero-1440x720.jpg / hero-1440x720-small.png: hero image, 1440 x 720 px.
- device-icon-128.png: optional on-device store icon, 128 x 128 px, black and white.
- screenshot-01 ... 08: every one differs in all three top lines, the layout, the gauges, the circle and the data:
  01 Chart: default top lines (moon, date, battery + solar); wind, humidity, feels like; visibility.
  02 Rows: alarm + thunderstorm forecast, Body Battery bar, countdown with time; daily intensity row; heart-rate circle.
  03 Chart: Do Not Disturb + date, resting HR + intensity bar, next new moon; resting HR, breathing, climbed.
  04 Rows: pressure-drop icon + week number, stress bar, metres descended; floors, move, daylight; wind circle.
  05 Chart on wrist raise: Bluetooth + date, battery days + battery bar, day length; UV max, rain today, freezing level.
  06 Rows on wrist raise: notifications + date, heart rate + zone bar, gusts next hour; next sunset circle.
  07 Light theme: phone + date, notifications + steps bar, pollen; humidity, air quality, rain chance as bars.
  08 Minimal: no icon, gauges, circle, bar or line 3; steps to goal, watch temperature, new snow.
- hero-versatility-1440x720.png: alternative hero with the real numbers (74 metrics: 34 weather, 16 outdoors = sun & moon + tactical, 20 health & activity, 4 watch; 15 circle views, 8 charts, 2 layouts, 16 slots, 631 options). Generated by tools/store_hero_versatility.py from the versatility images.
- context-day.png (1440 x 1440): "A day with Context": the same face at five times of day, each showing the message that matters then (DRY 12H+, RAIN ~30M, GUST 72 KMH, LIGHT 0:35, RAIN +14MM), with consistent values (wind, rain chance and Body Battery change through the day).
- adventure-1 ... 4.png (1440 x 1440): four adventure scenarios, one large face each: Alpine (freezing level, Beaufort force, a climbing altitude chart), Rain (Context rain timing, next 3 hours), Sun (light theme, UV, daylight left, solar), Night (snow timing, first light, moon). Every value agrees with the circle view shown.
- anatomy-chart.png / anatomy-rows.png (1440 x 1440): each layout with numbered zones and a legend of what each zone can show; the counts are read from the real option lists.
  The seven images above: generated by tools/store_adventure.py.
- versatility-1 ... 4.png (1440 x 1440): the previous metric-variety images (Chart, Chart + big text, Rows, Light, no metric repeated within an image). Still generated by tools/store_versatility.py.
- native-*-176.png / native-*-528.png: exact screen pixels at 1:1 and 3x, if device-resolution screenshots are needed.
