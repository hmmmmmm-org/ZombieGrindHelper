# Zombie Grind Helper (starter Android project)

This is a small native Android accessibility-service starter for repeating one tap at a fixed screen coordinate. It is **not a finished smart Roblox bot** and does not inspect Roblox game data, identify zombies, decide where to build, complete quests, or guarantee rewards.

## Build
1. Install Android Studio on a computer.
2. Open this folder as an existing Android project.
3. Let Gradle sync; install the Android SDK platform 35 if prompted.
4. Build an APK using **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the APK on your OPPO and allow installation from that source if Android asks.
6. Open the helper, tap **Enable accessibility service**, and enable its service in Android Accessibility settings.
7. Configure coordinates and tap interval. Start a short test, then switch to Roblox.

## Important limitations
- The service taps only one fixed screen coordinate. Coordinates depend on device resolution, orientation, and game UI.
- Android/ColorOS may restrict background execution; this starter does not include a persistent foreground notification or floating stop button.
- Test with a harmless UI location first and stop immediately if it taps the wrong control.
- Use automation only if permitted by Roblox and the specific experience. It may violate game rules or lead to penalties.
- This project is source code, not a prebuilt APK. A desktop Android build environment is needed to compile it.
