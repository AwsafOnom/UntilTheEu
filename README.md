# Until The EU 

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

## Presentation Slides
<img width="7214" height="4058" alt="Until The EU presentation_Page_02" src="https://github.com/user-attachments/assets/ba7c0f03-5ba2-43ec-8289-f3051e7aa49d" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_03" src="https://github.com/user-attachments/assets/57c8605d-0a98-47ee-a322-198859fb9792" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_04" src="https://github.com/user-attachments/assets/f5fcdb1a-38da-4f1d-8b22-49f2fb35cea0" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_05" src="https://github.com/user-attachments/assets/fc67f607-c5fd-44b0-b331-626489d28ed3" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_06" src="https://github.com/user-attachments/assets/477dd776-48ea-498c-94e3-61da56eb28e7" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_07" src="https://github.com/user-attachments/assets/307f19cf-ce40-4762-9ad7-18eefd9f4b0a" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_08" src="https://github.com/user-attachments/assets/39585836-1cef-4412-891e-5f0de437e176" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_09" src="https://github.com/user-attachments/assets/7b838ba5-7981-4f5c-8ffd-96f6531b4226" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_10" src="https://github.com/user-attachments/assets/5682c66a-66dd-4432-ac52-03a4f47daa2e" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_11" src="https://github.com/user-attachments/assets/0a04817c-8587-46d5-985f-1d6d490e5e71" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_12" src="https://github.com/user-attachments/assets/71e3414a-b3fe-42a2-8327-5347847933fd" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_13" src="https://github.com/user-attachments/assets/6e7b5965-a90b-40fb-a490-735ab9282630" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_14" src="https://github.com/user-attachments/assets/ec0f5fa8-f79b-4f86-b10e-465d85c58e72" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_15" src="https://github.com/user-attachments/assets/015e76a6-11d5-4495-a701-a72fffd025fa" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_16" src="https://github.com/user-attachments/assets/894ecf05-1740-4299-9343-df9bfc2d22e0" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_17" src="https://github.com/user-attachments/assets/8d330efd-94ca-4e03-ba63-ebb87aed3c1d" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_19" src="https://github.com/user-attachments/assets/1318b070-f367-4768-8cd8-f366114ca3d9" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_20" src="https://github.com/user-attachments/assets/470b519b-44e3-462c-a1a2-e22595e39469" />



### 2. Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/MuhtasimMahim/Until-The-EU.git](https://github.com/AwsafOnom/UntilTheEu)
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
