# Texas Water Safari Team Captain App

A Progressive Web App (PWA) designed specifically for Texas Water Safari team captains to track their team's progress during the 260-mile canoe race. Features real-time race timing, checkpoint management, and estimated arrival times to help teams navigate the challenging course from San Marcos to Seadrift.

## Author

Jesse Fornear ([@jfornear](https://x.com/jfornear))

## Features

- Real-time race timer
- Interactive checkpoint tracking
- Estimated arrival times based on current pace
- Timeline view of all checkpoints
- Mobile-first design
- Offline support via PWA
- Share race results via email
- Editable checkpoint notes and tasks
  - Customize tasks and exchange items for each checkpoint
  - Edit sleep and upcoming checkpoint information
  - Personalize finish line congratulations message
  - All changes save automatically to local storage

## Demo

Try the app: [Texas Water Safari Team Captain App](https://jfornear.s3.us-west-2.amazonaws.com/tws/captains-checklist.html?1)

## Screenshot

![App Screenshot](app-screenshot.png?2)

## Getting Started

1. Clone the repository
2. Open `captains-checklist.html` in a web browser

## Development

The application is built with vanilla HTML, CSS, and JavaScript. No build process is required.

### Project Structure

- `captains-checklist.html` - Main application file
- `manifest.json` - PWA manifest
- `sw.js` - Service worker for offline support
- `icons/` - Application icons

### Customizing Checkpoint Information

The app allows team captains to customize various sections of each checkpoint:

1. **Tasks Section**
   - Edit the default tasks for each checkpoint
   - Add or remove items as needed
   - Changes save automatically

2. **Exchange Section**
   - Modify the exchange items list
   - Add notes about specific requirements
   - Update quantities or special instructions

3. **Sleep Cards**
   - Customize sleep location details
   - Add notes about rest area conditions
   - Update upcoming checkpoint information

4. **Finish Line**
   - Personalize the congratulations message
   - Add team-specific instructions
   - Include post-race requirements

All changes are automatically saved to your browser's local storage and will persist between sessions. The editable sections are marked with a subtle border when you hover over them.

### Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Texas Water Safari organizers and volunteers
- All the paddlers who have participated in the race
