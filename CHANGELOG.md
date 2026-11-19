# Changelog

Store numbers and these build numbers may differ; each release here notes the build.

## 1.9.18

Context: a cold front within 3 hours by day (5° colder or more), tomorrow's high from 17:00 when it is 8° away from today's, the snow line (about 300 m below the freezing level, shown while it rains and when it is less than 800 m above you), and storm signs (more than 3 hPa lost in 3 hours, read at wrist raise). Wrist-raise gauge values in the Rows layout too. The chart is rebuilt about 3 seconds after a menu, not at the next sleep.

## 1.9.17

Lighter: the moon, the wind arrow, the high/low triangles and the colon are now drawn from the icon font instead of code (the moon in 16 phases on the circle, 8 on line 1; the arrow in 16 directions), freeing about 0.6 kB of the watch's app memory.

## 1.9.16

Weather no longer goes blank at midnight: tomorrow's high and low become today's until the next update. Rain chance and gusts look at the hours ahead (the hour that just ended no longer counts). Outside Central Europe and North America, rain and dry times follow the hour in progress, so "DRY BY" no longer runs an hour late. With Garmin weather, Next 3 Hours and Tomorrow say they need Open-Meteo instead of showing dashes. Fixed a menu fault past the last colon style. New installs start with Open-Meteo weather (every 15 minutes), the Chart layout with the 3-hour heart rate chart, and Context on line 3 (existing settings stay as they are). Lighter: fewer sensor reads inside the minute's redraw, and the settings menu's tables only use memory while the menu is open.

## 1.9.15

Lighter at busy moments: the 3-hour pressure trend, stress and Body Battery are read when you raise your wrist or the watch goes to sleep, not inside the minute's redraw; after the settings menu, the chart refills a few seconds later. The air-quality gauge shows GOOD as a first segment (it looked empty before) and its number is the level (1-6).

## 1.9.14

Context gets air quality on its own, so its air warnings work without an air metric on the face; the option is now simply called "Air quality".

## 1.9.13

In North America, air quality uses the US index and its words (GOOD to HAZARDOUS); a short break in the rain no longer counts as dry (the next 75 minutes, or the next hour, must stay dry too).

## 1.9.12

Gusts warned before they arrive: Context now also uses the strongest gust forecast for the coming hour ("GUST ~72 KMH"), plus a Gusts next hour metric. To make room: the Body Battery 2-hour change, the solstice/equinox countdown and the Diamonds colon are removed (their slots show Body Battery and the next hour's gusts).

## 1.9.11

Steadier: one activity read per redraw, and one pass over the hourly forecast for snow, rain amounts and thunderstorms.

## 1.9.10

Fix: a crash outside Central Europe and the US when Context showed a rain or storm time ("RAIN BY 16:00").

## 1.9.9

Thunderstorm warnings from the forecast's thunderstorm codes: act now within the hour, ahead of its own rain within 2 hours, and a forecast within 6 hours ("TSTORM ~16:00"); a T-storm forecast metric and a Thunderstorm circle view. The second time zone (with Zulu) is removed to make room; its slots show the thunderstorm forecast.

## 1.9.8

Lighter: the thunderstorm-potential metric (storm energy, not a storm forecast) is replaced by metres descended in the same slots; the second time zone is calculated without a date object; the countdown's day and year are plain lists in the watch menu.

## 1.9.7

Three more act-now messages: HEAT (feels-like 40°+ or 38° in the shade), WINDCHILL (feels-like -28° or below), SNOW + GUSTS (snow with gusts of 56+ km/h).

## 1.9.6

Freezing rain warned an hour ahead ("ICE RAIN ~1H"), and hourly rain timing from the forecast amount (0.3 mm), so light drizzle codes no longer trigger rain messages.

## 1.9.5

Honest rain timing outside Central Europe and the US ("RAIN BY 16:00": the forecast there is hourly), and BMNT/EENT, the position and sun elevation replaced by visibility, rain in the last hour and tonight's low in the same option slots.

## 1.9.4

Context is more honest: fog only from a fog code (dense fog under 400 m first, FREEZING FOG below 0°), freezing rain only from its codes, no thunderstorm from storm energy alone, and "SETS 20:25" / "RISES 06:10" without weather.

## 1.9.3

The right side gauge moved 2 px inward, so it is no longer cut off by the bezel on the 45 mm Instinct 3 Solar.

## 1.9.2

Seconds in the circle after a wrist raise, with the dotted ring filling over the minute.

## 1.9.1

Context is about weather and light only (Body Battery removed); during steady rain it shows how much is still to come ("RAIN +14MM"); leaner Context code.

## 1.9

Context ordered by what to act on; approximate rain and snow timing with snow from the forecast; compact on-watch menu with current values; allocation-free clock.

## 1.8

Rain and snow start and stop times up to 12 hours ahead, Context, daily countdown.

## 1.7

Six European air-quality levels, Beaufort wind force, clearer thunderstorm-potential and pressure-drop wording, countdowns up to 2045.

## 1.6

Pressure in inHg, wind in knots, a month/day date format, rain and snow units that follow the temperature setting; watch temperature and side gauges always fill; internal optimisations.

## 1.5

Memory and stability: single-screen settings menu, wind compass, side-gauge fix.

## 1.4

Big text mode, 1/3/4-hour charts, smoother charts while resting.

## 1.3

Open-Meteo (no API key): thunderstorm potential, pollen, freezing level, snow, UV maximum, rain today.

## 1.2

Air quality, precipitation timing, Body Battery trend, sun elevation, chart minimum and maximum on wrist raise.

## 1.1

Countdown, intensity goal, new metrics.

## 1.0

Initial release.
