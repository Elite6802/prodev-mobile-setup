# Mobile Development Setup with Expo

## Objective
Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we will be using the **Expo Framework** for React Native, which simplifies mobile app development and testing.

This setup ensures you can efficiently build and run React Native applications on both Android and iOS devices without relying heavily on emulators or additional hardware.

---

## Prerequisites
Before starting, make sure you have the following installed:

- **Node.js LTS** (v16 or higher)
- **VS Code** (recommended IDE)
- A compatible operating system: **macOS**, **Linux**, or **Windows**
- **Expo Go** installed on your physical device (Android or iOS)

---

## Why Expo Go?
Mobile development usually requires device emulators to test applications. However, keeping up with the wide range of mobile devices (e.g., iPhone 7 → iPhone 16 Pro Max, various Android devices) can be expensive and resource-intensive.

**Expo Go** provides a cost-effective solution by allowing you to:

- Test React Native applications directly on a physical device.
- Support both **iOS and Android** seamlessly.
- Skip complicated native code setup during development.

---

## Steps to Install Expo Go

1. Visit the official Expo Go homepage: [https://expo.dev/go](https://expo.dev/go)
2. Select the latest SDK version.
3. Install the app on your device:
   - **Android:** Install from the **Google Play Store**
   - **iOS:** Install from the **Apple App Store**
4. Open the Expo Go app on your device.
5. Create a new account or log in if you already have one.

---

## Challenges and Solutions

During the setup, I encountered a few challenges:

1. **Expo Go installation issues on iOS**
   - **Challenge:** The app would not install due to App Store restrictions.
   - **Solution:** Updated the iOS version to the latest supported version and ensured sufficient storage space on the device.

2. **Connecting physical device to Expo**
   - **Challenge:** The QR code scan did not open the app automatically on my device.
   - **Solution:** Made sure the phone and development machine were on the same Wi-Fi network and restarted the Expo CLI server. Manually entering the development URL in Expo Go also resolved the issue.

3. **Node.js version conflicts**
   - **Challenge:** Some packages did not install correctly due to an older Node.js version.
   - **Solution:** Verified Node.js LTS version (`node -v`) and upgraded to v18, then reinstalled Expo CLI.

4. **Slow reloads or connection issues**
   - **Challenge:** Live reloading was occasionally slow or failed to reflect code changes.
   - **Solution:** Cleared Expo cache (`npx expo start -c`) and ensured a stable Wi-Fi connection.

---

## Documentation
- Document your setup process in this README.md file.
- Include any **challenges** faced and how you resolved them.
- This will help track progress and troubleshoot issues during development.

---

## Repository Structure

