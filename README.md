# SimpleUI for KOReader

## My personalizations for doctorhetfield-cmd's simpleui.koplugin

A clean, distraction-free UI plugin for KOReader that transforms your reading experience. SimpleUI adds a **dedicated Home Screen**, a customisable bottom navigation bar, a top status bar, and a reworked library title bar, giving you instant access to your library, history, collections, and reading stats without navigating through nested menus.

# My Changes:

## Stats Provider:

- Added monthly stat calculations
- Changed weekly stat calculations to allow referencing of week totals by reading stats
- Fixed avg_pages and avg_secs so that they're an average of the last seven days including non-reading days, rather than an average of only the days in the last week that the user read anything. This should bring it in line with the setting description, as well as the 7-day average calculated by stock KOReader on the reading progress page

## Reading Stats:

- Added weekly data (last 7 days, time and pages) to widget
- Added monthly data (time and pages) to widget options
- Added yearly data (time) to widget options

## Reading Goals:

- Added monthly goal option (hours/month, set in increments of 1)
