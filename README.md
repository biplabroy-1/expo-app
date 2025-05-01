# Remind Me - Class Schedule App 📚

## Overview

Remind Me is a mobile application designed to help students keep track of their class schedules efficiently. Built with React Native and Expo, it provides timely notifications, intuitive schedule viewing, and smart reminders to ensure you never miss a class.

![App Screenshot](https://via.placeholder.com/250x500?text=Remind+Me+App)

## Features

- 📱 **Easy Schedule Viewing**: View your daily and weekly class schedules in an intuitive interface
- 🔔 **Smart Notifications**: Get timely reminders before classes start
- 👥 **Multiple Class Groups**: Support for different sections and groups
- 🌙 **Evening Reminders**: Get notifications the night before about your next day's schedule
- 🔄 **Automatic Updates**: In-app update system to ensure you have the latest features
- 📅 **Holiday Recognition**: Smart detection of holidays and breaks

## Installation

### Download the APK

Download the latest APK from our release assets:

- [Latest Release](https://github.com/your-org/remind-me-v4-application/releases/latest)

### Build from Source

```bash
# Clone the repository
git clone https://github.com/your-org/remind-me-v4-application.git

# Install dependencies
npm install

# Start the development server
npm start

# Build for Android
npm run build
```

## Development

```bash
# Start the Expo development server
npm start

# Run on Android device/emulator
npm run android

# Build release APK
npm run build
```

## Tech Stack

- **React Native**: Core framework for mobile app development
- **Expo**: Development platform and tools
- **NativeWind (TailwindCSS)**: For styling components
- **Expo Notifications**: For scheduling and managing notifications
- **Async Storage**: For local data persistence
- **React Native Reanimated**: For smooth animations and transitions
- **Expo Task Manager**: For background tasks
- **Axios**: For API requests

## Project Structure

```
remind-me-v4-application/
├── Components/           # React components
│   ├── Card.tsx         # Schedule card component
│   ├── Utils/           # Utility functions
│       ├── DivideGroups.ts
│       ├── notificationService.js
│       └── utils.ts
├── assets/              # Static assets like images and sounds
├── App.tsx              # Main application component
└── android/             # Native Android files
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Version

Current version: 4.3.0

## License

This project is licensed under the MIT License.

---

Built with ❤️ for students
