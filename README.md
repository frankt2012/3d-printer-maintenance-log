# 3D Printer Maintenance Log

A free, single-file web app for tracking maintenance on your 3D printers. No install, no account, no build step. Open `index.html` in any browser.

## What it does

- **Multiple printers.** Each printer has its own print-hours counter, installed nozzle (type and size) and installed build plate.
- **Maintenance categories.** New printers start with eight: carbon rods, linear rods, lead screws, belts, cutter, extruder, fans and nozzle. Add, edit or remove any category.
- **Quick picks.** Around 50 ready-made categories (motion, hotend, bed, filament handling, electronics, enclosure, multi-material systems such as CFS, AMS Lite, AMS and MMU, and resin printers) with a suggested starting interval you can change.
- **Flexible intervals.** Repeat by print hours, calendar days or months, and set the date you last serviced each item.
- **Two views.** A task list with progress gauges, and a Year board with one row per category and a frame on the month it is next due. Frames turn orange when due soon and red when overdue.
- **Service history.** Log each service with a date, print hours and a note.
- **Light and dark themes** that follow your system setting.

## Using it

Download `index.html` and open it, or turn on GitHub Pages for this repository (Settings, Pages, deploy from the `main` branch) to use it as a website.

## Your data

Everything is saved in your browser's local storage on the device you use. Nothing is sent anywhere. That means:

- Each browser and device keeps its own separate list.
- Clearing your browsing data erases it.
- The page has no export button yet, so there is no built-in backup.

The suggested intervals are general starting points, not manufacturer schedules. Adjust them to match your printers.

## Fonts

The page loads Barlow Condensed, IBM Plex Sans and IBM Plex Mono from Google Fonts. Without an internet connection it falls back to your system fonts and still works.
