# The ResponsiveLayout App
This app demonstrates responsive UI composition in Jetpack Compose by adapting layout based on available width. On narrow screens like a phone, the UI uses a single vertical layout to show a list of items with a simple detail section at the bottom.
On wide screens like a tablet, the UI switches to a two-pane layout.

## Screenshots

<img width="285" height="632" alt="Screen Shot 2026-02-24 at 4 10 31 AM" src="https://github.com/user-attachments/assets/92aaa1c6-6d59-4c84-9bad-227f3d60f1b2" />

<img width="706" height="317" alt="Screen Shot 2026-02-24 at 4 10 55 AM" src="https://github.com/user-attachments/assets/157e8ed0-0088-43da-8821-7206c0ab987a" />

## AI Disclosure
AI helped me troubleshoot scrolling behavior in the emulator. Although my LazyColumn implementation was correct two finger trackpad gestures were not being recognized by the emulator. AI helped me distinguish between a layout issue and an emulator input issue by suggesting programmatic scroll testing using LazyListState. I also used AI to format the code file with appropriate spacing and alignment to make clean, readable code for graders. I also used AI to review if my code fulfilled grading requirments and identify missing rubric items.
