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
<img width="7214" height="4058" alt="Until The EU presentation_Page_20" src="https://github.com/user-attachments/assets/50e3fee6-894d-4e52-92c8-6f362c148bdc" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_19" src="https://github.com/user-attachments/assets/72a71781-3e52-4c8a-aa74-f51fe7e99792" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_17" src="https://github.com/user-attachments/assets/4a85d48c-f611-4725-a305-43add35609f5" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_16" src="https://github.com/user-attachments/assets/748e1474-01e9-4556-b053-70c49c8eb855" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_15" src="https://github.com/user-attachments/assets/37fd5634-6043-4623-9b77-870dd62448b1" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_14" src="https://github.com/user-attachments/assets/793cdf6a-2fc1-42c7-a358-bd1035b475eb" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_13" src="https://github.com/user-attachments/assets/826f95a6-b921-484f-831d-733f816bc318" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_12" src="https://github.com/user-attachments/assets/fcc773fe-4bc0-43a0-9fcc-c361f7d150db" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_11" src="https://github.com/user-attachments/assets/e5f83e89-e6bd-477d-a51e-f5a4bdbd8ecf" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_10" src="https://github.com/user-attachments/assets/f1fc989d-c1d9-420d-bf6b-d37b7837df19" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_09" src="https://github.com/user-attachments/assets/8df038ac-93bc-4445-b91b-8eda88ec1011" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_08" src="https://github.com/user-attachments/assets/3070b60b-78c6-4462-9061-f67af23435d9" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_07" src="https://github.com/user-attachments/assets/95214201-feb1-4731-b5bf-5e498d4c9379" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_06" src="https://github.com/user-attachments/assets/38527772-bb19-437d-88fd-3094147392c5" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_05" src="https://github.com/user-attachments/assets/2c72977a-8e52-4ca4-9542-8f84fa2a6a92" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_04" src="https://github.com/user-attachments/assets/31e39972-1003-4362-847c-0c1496d15565" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_03" src="https://github.com/user-attachments/assets/1a62de4f-d6d8-4e0c-860e-6690b99cb23b" />
<img width="7214" height="4058" alt="Until The EU presentation_Page_02" src="https://github.com/user-attachments/assets/d99ddc60-bea3-4d83-9acd-d0db095e3477" />


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
