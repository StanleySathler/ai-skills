# Dev: React Native + Expo

- If no references to Expo yet in this project, find latest stable version for Expo and use it. If any references, stick to whatever version is used in this project.
- Use 'expo-localization' to build a localized app. For pt-BR devices, content is pt-BR. For devices in any other language, content is en-US. Dev must be able to force pt-BR even on an en-US device, for development. Setup the localization, but start with pt-BR content only, then only add en-US translations when explicitly told to.
- Create an OTA Update channel. Start with `production` only, until explicitly told to add others.
