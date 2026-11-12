# Solar Frontier: Connect IQ Store listing

## App name
Solar Frontier

## Short description
An adventure watch face that shows what matters next.

## Description (paste into the store)

YOUR WEATHER, LIGHT AND TRAIL, AT A GLANCE.
Solar Frontier is a free adventure watch face for the Instinct 3 Solar (45 and 50 mm), drawn pixel by pixel for its high-contrast screen. A big, clear time. Every other zone yours to fill. And one line that thinks ahead for you.

CONTEXT: ONE LINE THAT WATCHES THE SKY
Most faces show the same numbers all day. Context shows the one message most likely to change what you do next, and stays quiet when nothing does:
- "TSTORM ~16:00": a thunderstorm in the forecast, hours before it arrives.
- "GUST ~72 KMH": strong gusts expected within the hour.
- "RAIN ~30M" / "DRY ~25M": when the rain starts or stops ("RAIN BY 16:00" where the forecast is hourly).
- "LIGHT 0:25": daylight left before sunset.
- "HEAT 41°", "WINDCHILL -30°", "FREEZING RAIN", "FOG 0.3 KM": act now.
- "DRY 12H+": nothing to worry about.
The "~" means forecast: the face never pretends to know the minute.

ONE FACE, ARRANGED YOUR WAY
74 metrics and 631 options, all set on the watch itself (no phone needed) or in Garmin Connect:
- Circle: 16 views, from the weather now, the next 3 hours or tomorrow, to the moon, wind, thunderstorm or seconds on wrist raise.
- Top lines: a status icon (alarm, Bluetooth, pressure drop and more), the date in 7 formats or a metric, a number with its own bar.
- Line 3: any of 48 metrics, or Context, or one metric in large type.
- Two side gauges, as bars or blocks.
- Two layouts: three progress rows, or three columns with a history chart (heart rate, stress, Body Battery, pressure, altitude, temperature, Pulse Ox or solar, over 1, 3 or 4 hours).
- Wrist raise adds exact values.
- Your style: dark or light theme, solid, outlined or dithered minutes, three colon styles, 12 or 24 hours.

BUILT FOR THE OUTDOORS
- Weather: temperature and feels-like, wind and Beaufort force, gusts now and in the next hour, rain chance and amounts, snow, freezing level and the margin to your altitude, visibility, UV, air quality (European or US index) and pollen.
- Light: sunrise and sunset, first and last light, golden hour, day length, moon phase.
- Terrain: altitude, barometric pressure and its trend, metres climbed and descended.
- Body: heart rate and zone, Body Battery, stress, breathing, Pulse Ox, steps, floors, intensity minutes with your own daily goal.
- Watch: battery and days left, solar intensity, notifications, and a countdown to a date or a daily time.

YOUR WEATHER SOURCE
Garmin's own weather, or free forecasts from Open-Meteo through your phone every 5 to 60 minutes. No account, no key, no data collected.

GOOD TO KNOW
- The face cannot vibrate or sound an alarm. Context and the pressure-drop icon are indications from the forecast and your barometer, not official warnings; the Instinct's own storm alert remains the alarm.
- Pollen: Europe only, in season.
- Weather data by Open-Meteo.com (CC BY 4.0). Air quality and pollen: Copernicus Atmosphere Monitoring Service (CAMS) via Open-Meteo.
- Permissions: health data and heart-rate zones, location (sun times, local weather), background and internet (Open-Meteo only).

A personal project, built with the help of AI and shared for free.

## What's new

WHAT'S NEW
- Earlier wind warnings: if strong gusts are forecast for the next hour, Context tells you now, before they arrive ("GUST ~72 KMH"; the "~" means it's a forecast). A new Gusts next hour metric shows the same.
- Air quality on your region's scale: in North America the US index (GOOD to HAZARDOUS), elsewhere the European one. Context now checks air quality even if no air metric is on your face.
- The air-quality gauge no longer looks empty on clean days: GOOD fills the first segment, and the number shows the level, from 1 (best) to 6.
- No more early "DRY": a short pause in the rain is no longer announced as its end.
- Smoother on the watch: heavier readings now happen when you raise your wrist, not every minute. After changing settings, the chart takes a few seconds to come back.

REMOVED TO MAKE ROOM
- If you used one of these, the same spot now shows something close: Body Battery 2-hour change became Body Battery, Solstice/equinox became Gusts next hour, and the Diamonds colon became Squares. All your other settings stay as they were.

Version history:
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
