# Until The EU *

---

## Important Link

- **Android App :** [Download APK](https://drive.google.com/file/d/1NHGVcTUFFpUDQMdbYl8fnd0MNH5Rt1J7/view?usp=sharing)

---

## About The Project

**Until The EU** is an educational and mental wellness mobile application built using **Expo and React Native**. 

### Key Features
- **Stress Diagnostic Quiz:** Interactive questionnaire assessing user stress and emotional well-being.
- **Personalized Results:** Calculation of **StressScore** and categorized **StressLevel**.
- **Tailored Solutions:** Curated multimedia resources, soothing sounds/audio guides, relaxation activities, and educational video sessions to help relieve stress.

---

## How to Run Locally

Follow these instructions to install dependencies and run this project on your local machine.

### 1. Prerequisites

- **Node.js:** Node.js 16+ or modern Node (Node 18 / 20 / 22 / 24).  
  *Note:* Node 17+ uses OpenSSL 3.0. The project includes `cross-env` preconfigured with `--openssl-legacy-provider` in `npm scripts` so it runs out-of-the-box on modern Node versions without OpenSSL crypto errors.
- **Package Manager:** `npm` (included with Node.js) or `yarn`.
- **Testing Device / Environment:**
  - An Android device or iPhone with the **Expo Go** app installed.
  - Or an Android Emulator (Android Studio) / iOS Simulator (macOS Xcode).
  - Or run directly in your web browser.

---

### 2. Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MuhtasimMahim/Until-The-EU.git
   cd Until-The-EU
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

---

### 3. Running the Project

Start the Expo local development server:

```bash
npm start
```

This will launch the Metro Bundler and display a terminal QR code along with interactive commands:

| Command | Action |
|---|---|
| `a` (or `npm run android`) | Open in Android emulator / connected device |
| `i` (or `npm run ios`) | Open in iOS simulator (macOS) |
| `w` (or `npm run web`) | Open in your default web browser |
| `r` | Reload app |
| `m` | Toggle dev menu |

#### Running on a Physical Phone via Expo Go:
1. Ensure your computer and smartphone are connected to the **same local Wi-Fi network**.
2. Run `npm start`.
3. Open **Expo Go** on your device:
   - On Android: Scan the QR code printed in the terminal or web interface.
   - On iOS: Scan the QR code using the default Camera app and tap the Expo banner.

---

## Tech Stack & Dependencies

- **Framework:** [React Native](https://reactnative.dev/) `0.64.3`
- **Platform:** [Expo](https://expo.dev/) SDK `~44.0.0`
- **Navigation:** [React Navigation (Stack)](https://reactnavigation.org/) `v6`
- **UI & Animation:** [Lottie React Native](https://github.com/lottie-react-native/lottie-react-native)
- **Audio & Video:** `expo-av`, `react-native-sound`, `react-native-youtube-iframe`, `react-native-webview`
- **Compatibility Tooling:** `cross-env`, `expo-cli`

---

## Project Structure

```text
├── Docs/
│   ├── Presentation/           # Slides (PDF + Page 1-21 JPGs)
│   └── Proposal/               # Proposal document (PDF + Page 1-8 JPGs)
├── assets/                     # App icons, audio assets, animations, fonts
├── components/                 # Reusable React Native UI components
├── constants/                  # Colors, quiz questions, stress levels & data
├── screens/                    # Application screens
│   ├── SplashScreen.js         # Animated intro splash
│   ├── QuizScreen.js           # Stress assessment questionnaire
│   ├── HomeScreen.js           # Main dashboard with content cards
│   ├── DetailsScreen.js        # Detailed view of relief techniques
│   └── SolutionScreen.js       # Actionable solution & therapeutic activities
├── App.js                      # Root app entry point and navigation container
├── app.json                    # Expo project configuration
└── package.json                # Dependencies and run scripts
```

---
