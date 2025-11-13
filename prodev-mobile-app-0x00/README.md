First Mobile Application with Expo Router

## Objective
Set up your first mobile application using the **Expo Router template**. Document the scaffolding process and understand the file structure of a React Native application using Expo.

---

## Steps Followed for Scaffolding

### 1. Navigate to Project Directory
Open the terminal and move to the parent project directory:

```bash
cd prodev-mobile-setup
2. Set Up the Expo Project
Initialized a new Expo project using the latest Expo Router template:

bash
Copy code
npx create-expo-app@latest .
Selected TypeScript when prompted.

The scaffolding process created the following main directories and files:

app/ – contains all application routes and screens.

app/(tabs)/index.tsx – the default Home Screen.

package.json – project dependencies and scripts.

tsconfig.json – TypeScript configuration.

node_modules/ – installed dependencies.

3. Modify the Home Screen
Opened app/(tabs)/index.tsx.

Located the default text Welcome!.

Replaced it with:

tsx
Copy code
<Text className="text-lg font-bold">First App Created</Text>
4. Run and Test the Application
Started the Expo development server:

bash
Copy code
npx expo start
iOS Devices: Scanned the QR code using the phone’s Camera app.

Android Devices: Scanned the QR code using the Expo Go app.

Verified that the home screen displayed First App Created.

5. Reset the Application
Executed the reset command:

bash
Copy code
npm run reset-project
Observations
The reset-project command restored the project to its initial scaffolding state.

All local modifications, including the edited home screen text, were reverted back to the default Welcome! message.

Dependencies remained intact, but any unsaved or uncommitted changes were lost.

This command is useful for starting fresh or troubleshooting project inconsistencies.

Summary
Successfully scaffolded an Expo project using the Expo Router template.

Modified the Home Screen to display custom text.

Tested the application on both iOS and Android devices via Expo Go.

Observed the effects of the reset-project command: it restores the project to its default state while preserving dependencies.