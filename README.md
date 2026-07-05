RANKTECH - Cyber Arena | AI & ELO-Based Hardware Battle
RANKTECH is a cross-platform mobile application built on the foundations of gamification, Generative AI (Gen-AI), and the ELO Ranking Algorithm. It was developed to combat the "information overload" and "decision fatigue" problems of traditional, static hardware rating platforms.

Instead of manipulated 5-star reviews on existing e-commerce sites, it pits hardware in 1v1 (head-to-head) duels, creating an organic and unbiased leaderboard (Champions League) driven entirely by community preferences.

 Key Features
⚔️ Dynamic ELO Duels: Powered by the ELO algorithm coded with the dart:math library, users clash two pieces of hardware using a "Swipe Left/Right" mechanic, determining their rankings in real-time.

 Cyber Assistant (Gemini AI API): Utilizing Google Gemini AI, complex hardware specifications are parsed, chronic issues are summarized, and dynamic price-performance simulations are generated based on the user's budget and use cases.

 Real-Time Synchronization: Hardware scores and leaderboards are updated in milliseconds via Firebase Cloud Firestore's WebSockets architecture.

 Airtight Security & Authentication: Secure session management is provided via Firebase Auth with Google, Apple, Email, and "Guest (Anonymous)" login options.

 Technologies and Architecture
Client: Flutter, Dart

Database (Backend): Firebase Cloud Firestore (NoSQL)

Authentication: Firebase Authentication (OAuth 2.0)

Media Storage: Firebase Storage

Artificial Intelligence: Google Gemini Generative AI REST API

State Management: Stateful Widget & StreamBuilder Architecture

Graphics & Data Visualization: fl_chart

 Installation and Setup
You can follow the steps below to run the project in your local environment:

1. Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/ranktech.git
2. Download the required Flutter packages:

Bash
flutter pub get
3. Add Firebase configuration files:
Add the google-services.json and GoogleService-Info.plist files to their respective directories within the project.

4. Run the project:

Bash
flutter run
