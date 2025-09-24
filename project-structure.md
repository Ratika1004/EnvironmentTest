# Project Structure - EnvironmentTest

EnvironmentTest/
├── android/          # Android-specific files (Gradle build, manifests, Java/Kotlin code)
├── ios/              # iOS-specific files (Xcode project, Info.plist)
├── node_modules/     # All installed dependencies
├── App.js            # Main React component (UI of the app)
├── index.js          # Entry point that registers the App component
├── package.json      # Project configuration & dependencies
├── babel.config.js   # Babel configuration (JS compiler settings)
└── README.md         # Project documentation

## Folder Organization
- `src/components/` - Reusable UI components
- `src/screens/` - Screen components
- `src/services/` - API and configuration services
- `src/utils/` - Utility functions
- `src/constants/` - App constants
## Development Scripts
- `npm run dev:android` - Start development for Android
- `npm run lint` - Check code quality
- `npm run format` - Format code
## Environment Configuration
- Development: `.env.development`
- Production: `.env.production`
