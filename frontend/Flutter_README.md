 **README.md** files for the frontend, 



### **Frontend (Flutter) README.md**

```markdown
# Gender Equality Empowerment Platform (Frontend)

This is the frontend for the Gender Equality Empowerment Platform, built with Flutter. The app allows users to post stories, vote for impactful posts, and send emergency alerts.

## Features

1. **User Authentication**
   - JWT login/registration.

2. **Story Posting**
   - Users can post, comment, and like stories related to gender equality.

3. **Blockchain Voting**
   - Users can vote for featured stories, with votes stored securely using blockchain.

4. **AI Insights**
   - AI-driven analysis of the emotional tone of posts.

5. **Notifications**
   - Real-time notifications for new comments, likes, and alerts.

6. **Emergency Alerts**
   - Users can send alerts to police or healthcare services with blockchain-verified data.

## Technologies Used

- **Flutter**: Mobile development framework.
- **Dart**: Programming language for Flutter.
- **REST APIs**: To communicate with the Django backend.
- **Firebase**: For push notifications and analytics (optional).

## Installation and Setup

### Prerequisites

- Flutter 2.0+
- Dart 2.12+
- Android/iOS Emulator or Device

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gender-equality-frontend.git
   cd gender-equality-frontend
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Create a `lib/.env.dart` file to store the API URL and keys:
   ```dart
   const String API_URL = 'https://yourbackendurl.com/api/';
   const String BLOCKCHAIN_API_KEY = 'your_blockchain_api_key';
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Folder Structure

```
/lib/
│
├── /models/                # Data models (User, Post, Comment, etc.)
├── /services/              # API interaction services (auth, posts, comments)
├── /screens/               # Screens for login, home, post details, voting
├── /widgets/               # Reusable components (post cards, buttons)
├── /utils/                 # Utility functions (constants, themes)
├── main.dart               # Entry point for the app
├── routes.dart             # Route configuration
└── app_localizations.dart  # Localization and internationalization support
```

## Key Screens

1. **Login Screen**:
   - User login and registration with JWT.

2. **Home Screen**:
   - Displays all stories, allows voting and filtering.

3. **Post Details Screen**:
   - Users can comment, like, and see AI insights.

4. **Voting Screen**:
   - Allows users to vote for the most impactful stories.

5. **Emergency Alert Screen**:
   - Sends emergency alerts to healthcare or police.

## Testing

To run the app in debug mode:
```bash
flutter run
```

For unit tests:
```bash
flutter test
```

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

## License

This project is licensed under the MIT License.
```

---
