# Family Feud Fast Money UI

A two-screen Family Feud Fast Money round interface that allows you to quickly input answers and points, then control what appears on the main display in real-time.

## Features

- **Dual-screen setup**: Separate control panel and display screens
- **Real-time synchronization**: Changes appear instantly on the display
- **Professional game show appearance**: Authentic Family Feud styling with template background
- **10-answer layout**: Full Family Feud board with two columns (answers 1-5 and 6-10)
- **Easy controls**: Type answers, set points, check boxes to reveal
- **Quick actions**: Reveal all, hide all, reset all with one click
- **Live scoring**: Automatic total calculation of revealed answers

## How to Use

### 1. Open the Control Panel
- Open `control.html` in your web browser
- This will be your host/operator interface

### 2. Open the Display Screen
- Click "Open Display Window" in the control panel
- This opens `display.html` in a new window
- Move this window to your second screen/projector

### 3. Setup Your Round
- In the control panel, enter answers in the text fields
- Set point values for each answer
- The display will remain hidden until you check the reveal boxes

### 4. During the Game
- **Reveal answers**: Check the boxes next to answers to make them appear on the display
- **Live scoring**: The total automatically updates as you reveal answers
- **Quick controls**: Use the buttons to reveal all, hide all, or reset everything

## Files

- `control.html` - Host control interface
- `display.html` - Main game display
- `feud template.jpg` - Reference image (your original template)

## Tips

- Set up answers and points before starting the round
- Use the "Reveal All" button for dramatic effect
- The "Reset All" button clears everything (with confirmation)
- Keep the control panel on your private screen and display on the audience screen
- The system works entirely offline - no internet connection needed

## Technical Notes

- Uses HTML, CSS, and JavaScript only
- Cross-window communication for real-time updates
- Responsive design works on different screen sizes
- Modern browsers required for full functionality

Enjoy hosting your Family Feud games! 