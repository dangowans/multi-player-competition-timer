# Multi-Player Competition Timer

A web-based timer application designed for tracking multiple competitors in games, races, or other competitive events. Perfect for game nights, competitions, or any scenario where you need to time multiple participants.

## Features

- **Two Timer Modes:**
  - **Together Mode**: All participants start together, and you record finish times as each person completes
  - **Single Mode**: Time each participant individually, one at a time

- **Participant Management**: Add, remove, and track unlimited participants

- **Large Display**: Optimized for viewing on TVs and large screens with high-contrast design

- **Responsive Layout**: 
  - Portrait mode for mobile devices
  - Landscape mode optimized for TVs and horizontal displays
  - Mode toggles positioned next to participants section in landscape for easy access

- **Wake Lock Support**: Prevents screen from sleeping during active timing

- **Persistent Storage**: Participant list is saved locally in your browser

## How to Use

### Getting Started

1. **Add Participants**: 
   - Enter names in the "Participants" section
   - Press "Add Participant" or hit Enter
   - Remove participants by clicking the × button next to their name

2. **Choose a Timer Mode**:
   - **Together Mode**: For races or competitions where everyone starts simultaneously
   - **Single Mode**: For turn-based timing where each participant goes individually

### Together Mode

1. Add all participants first
2. Click "Start" (or tap the timer display) when the competition begins
3. Click "Stop" (or tap the timer display) each time a participant finishes
4. After all times are recorded, assign each time to the correct participant using the dropdown menus
5. Times are automatically sorted to show fastest times first after assignment

### Single Mode

1. Add all participants first
2. Select the first participant from the dropdown menu
3. Click "Start" when they begin
4. Click "Stop" when they finish - the time is automatically assigned
5. The next participant is automatically selected for you
6. Repeat until all participants have completed

### Controls

- **Start Button**: Begin timing
- **Stop Button**: Record the current time (in Together Mode) or finish timing the current participant (in Single Mode)
- **Reset Button**: Clear all recorded times and reset the timer to 00:00.00
- **Timer Display**: Click/tap the timer display to start or stop (same as the buttons)

## Landscape/TV Optimization

When viewed in landscape orientation on screens 768px or wider:
- Mode toggles appear next to the Participants section for easy access
- Timer display is larger (66% of width) for better visibility
- Recorded times column is narrower (33% of width) but with larger font sizes
- Layout maximizes space efficiency for viewing from a distance

## Technical Details

- Pure HTML/CSS/JavaScript - no build process required
- Uses localStorage to persist participant data
- Supports Web Wake Lock API to prevent screen dimming during active timing
- Progressive Web App (PWA) ready with manifest and icons

## Installation

Simply open `index.html` in any modern web browser. For best results:
- Use a modern browser (Chrome, Firefox, Safari, Edge)
- Allow wake lock permissions for uninterrupted timing
- Add to home screen on mobile devices for full-screen experience

## License

See LICENSE file for details.
