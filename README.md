# Academy Campus Fall Schedule System

A visual scheduling system for Academy Campus showing room usage across 6 rooms with interactive features and official institutional colors.

## Features

- **Master Calendar**: Interactive overview of all rooms with clickable class details
- **Individual Room Schedules**: Banner-style layouts perfect for posting outside rooms
- **Official Color Scheme**: Uses Academy Campus institutional colors
- **Interactive Details**: Click any class to see instructor, enrollment, and section information
- **Responsive Design**: Works on desktop and mobile devices
- **Clean Visual Design**: Professional appearance with bordered class entries

## Room Color Coding

- **A001** (Computer Lab): Hearty Hosta (soft green)
- **A002** (Animation): Canary Yellow (bright yellow)  
- **A201** (Media Arts Project Room): Regal Purple (deep purple)
- **A206** (Seminar): Ginger Spice (warm brown)
- **A208** (Theatre): Egyptian Sun (golden yellow)
- **A303** (Media Arts Classroom): Fresh Water Blue (soft blue)

## File Structure

```
academy-campus-schedule/
├── README.md
├── index.html (Master Calendar)
├── rooms/
│   ├── a001.html (Computer Lab)
│   ├── a002.html (Animation)
│   ├── a201.html (Media Arts Project Room)
│   ├── a206.html (Seminar)
│   ├── a208.html (Theatre)
│   └── a303.html (Media Arts Classroom)
├── css/
│   └── shared-styles.css
└── data/
    └── schedule-data.csv
```

## Usage

### For Web Display
1. Upload all files to your web server
2. Access `index.html` for the master calendar
3. Individual room schedules are in the `rooms/` directory

### For Drupal Integration
1. Copy the HTML content from any file
2. Paste into a Drupal content area
3. Set text format to "Full HTML"
4. Save and publish

### For Digital Signage
- Individual room HTML files work perfectly for digital displays
- Banner format is optimized for widescreen monitors
- Colors and fonts are designed for high visibility

## Customization

### Updating Class Data
Edit the `scheduleData` array in each HTML file with:
- Course codes and titles
- Instructor names and emails
- Enrollment numbers and capacity
- Material fees and waitlist information

### Color Modifications
Colors are defined in CSS custom properties:
```css
.room-A001 { 
    --room-color: #a8c8a0; 
    --room-color-dark: #8bb283; 
    --room-accent: #bdd4b5; 
}
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

MIT License - Feel free to adapt for your institution

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

*Academy Campus Schedule System - Professional scheduling visualization for educational institutions*