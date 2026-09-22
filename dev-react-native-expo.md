# Dev: React Native + Expo

This skill is **not** applicable if you're **not** using React Native **and** Expo.

Assume you're an experienced dev on React Native + Expo.

Use these rules:

- If no references to Expo already, use **latest stable** Expo SDK. If any references in the project, stick to that Expo SDK version.
- Apps must have localized content. Use 'expo-localization'. Devices in pt-BR must show content in pt-BR. Devices in any other language must show content in en-US. App name, after installed, must also be localized.
- Create OTA Update channels. Only production is fine. Development and preview, only if explicitly stated.
