# RS Routine

A web-based routine viewer for RS, allowing students to view their class schedules and Friday/Saturday activities interactively.

## Features

- Search for your class routine by section number
- View detailed schedules for Sunday–Wednesday
- See meal times and activities for Friday and Saturday
- Download your routine as an image
- Responsive, mobile-friendly UI

## Usage

1. Open [index.html](index.html) in your browser.
2. Enter your section number (e.g., `04`) and optionally select an activity.
3. Click **Search** to view your routine.
4. Use the **Capture Routine** button to download your schedule as an image.

## Data Files

- [sun-tues.json](sun-tues.json): Sunday & Tuesday schedules
- [mon-wed.json](mon-wed.json): Monday & Wednesday schedules
- [activities.json](activities.json): Friday/Saturday activities

## Deployment

- Static hosting ready (see [firebase.json](firebase.json) for Firebase, [static.yml](.github/workflows/static.yml) for GitHub Pages)
- No backend required

## Development

- All logic is in [index.html](index.html) (vanilla JS, Tailwind CSS)
- Data is loaded from JSON files

## License

MIT License

---

**Note:** This project is not affiliated with any official institution. For official schedules, always refer
