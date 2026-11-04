# 🚗 White Window — Neon Highway Edition

### An endless arcade driving game where the police are relentless, the road is unforgiving, and your windscreen is your worst enemy.

**White Window** is a chaotic, first-person 3D arcade driving game built with JavaScript, HTML5, CSS3 and Three.js.

Accelerate by repeatedly tapping, dodge oncoming traffic, evade an increasingly aggressive police pursuit, and keep your windscreen clear enough to survive.

Built for **iPhone, iPad and desktop**, with touch-optimised controls, adaptive graphics and a landscape-focused mobile experience.

---

## 🎮 Game Features

### 🚗 Endless Highway Pursuit
- Drive along an endless, dynamically curving highway.
- Avoid traffic, construction obstacles, potholes and oil slicks.
- Survive an escalating police pursuit.
- Earn distance-based scores and compete against your personal records.
- Experience increasingly challenging conditions as your run progresses.

### 🎨 Enhanced 3D Graphics
- Atmospheric highway environments and dynamic lighting.
- Detailed vehicles, road signs, trees and roadside scenery.
- First-person cockpit with animated steering wheel and instruments.
- Rear-view mirror displaying pursuing police vehicles.
- Police emergency lighting and visual effects.
- Windscreen splatter and animated automatic wipers.

### 📱 Mobile & iOS Support
- Optimised for iPhone and iPad.
- Landscape-first gameplay.
- Automatic landscape-style display rotation when portrait orientation is detected.
- Touch steering, acceleration and braking.
- iPhone safe-area support.
- Full-screen-style experience when installed to the Home Screen.
- Native iOS project available for Xcode.

### ⚡ Adaptive Performance
- Adjustable graphics quality.
- Device-aware rendering resolution.
- Performance-friendly geometry and reusable objects.
- Built-in 2D rendering fallback.
- Reduced-motion option.
- Configurable sound and haptic feedback where supported.

### 🚨 Dynamic Gameplay
- Police pursuit intensity increases with distance.
- Traffic and obstacles become progressively more challenging.
- Repeated acceleration builds pressure and speed.
- Excessive acceleration reduces windscreen visibility.
- Automatic wipers help restore visibility.
- Near misses and consecutive actions reward skilled driving.

---

## 🕹️ Controls

### 📱 iPhone / iPad

| Action | Control |
|---|---|
| Accelerate | Repeatedly tap **JERK** |
| Steer | Drag the left steering control |
| Brake | Press and hold **BRAKE** |
| Pause | Tap the pause button |
| Sound | Toggle the sound button |
| Graphics | Open Settings |

Landscape orientation is recommended for the best driving experience.

### 💻 Desktop

| Action | Control |
|---|---|
| Accelerate | `SPACE` (repeated taps) |
| Steer left | `A` or `←` |
| Steer right | `D` or `→` |
| Brake | `S` or `↓` |
| Pause / Resume | `P` |
| Restart | `R` |
| Mute | `M` |

---

## 🚀 Play the Game

### Option 1 — Web Browser

White Window can be hosted as a static HTML website.

1. Download the latest HTML game file.
2. Upload it to a web server or static hosting provider.
3. Open the game's HTTPS URL in your browser.
4. Select **START PURSUIT**.

No database, PHP backend or user registration is required.

**Note:** The enhanced 3D renderer may require an initial internet connection to load Three.js. A built-in 2D fallback is available when the 3D engine cannot load.

### Option 2 — GitHub Pages

White Window can be deployed using GitHub Pages.

1. Upload the game HTML file to your GitHub repository.
2. Rename the main game file to `index.html`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder.
6. Save your settings.

Your game will be available at:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

Replace the placeholders with your GitHub username and repository name.

### Option 3 — Native iOS App

An Xcode source project is available for running White Window as an iOS application.

**Requirements**
- macOS
- Xcode
- An iPhone or iPad
- Apple signing credentials for device deployment

**Installation**

1. Download and extract the iOS Xcode project.
2. Open `WhiteWindow.xcodeproj`.
3. Select your Apple Development Team under Signing & Capabilities.
4. Connect or select your iPhone or iPad.
5. Build and run the application.

The native iOS configuration supports landscape-left and landscape-right orientations.

The source package is not a precompiled IPA. An Xcode build and on-device testing are required.

---

## ⚙️ Graphics Settings

| Setting | Description |
|---|---|
| Auto | Selects graphics settings based on device type |
| High Fidelity | Higher rendering resolution and visual quality |
| Balanced | Compromise between graphics and performance |
| Battery Saver | Lower rendering workload |
| Reduce Camera Shake | Reduces motion effects |
| Haptic Feedback | Enables supported vibration effects |

The ideal settings depend on your device's GPU, browser and available memory.

---

## 🏆 Leaderboards

White Window includes a local leaderboard system.

- Stores the top 10 runs per difficulty.
- Records distance travelled and driver name.
- Supports separate records for different difficulty modes.
- Uses browser local storage when available.
- Does not require an account or external database.

Scores are stored locally and are not synchronised between devices.

---

## 🛠️ Technology

| Technology | Purpose |
|---|---|
| HTML5 | Game structure and canvas rendering |
| CSS3 | Responsive interface and mobile layout |
| JavaScript | Game logic, physics and interactions |
| Three.js | WebGL 3D rendering |
| Canvas 2D | Windscreen effects and fallback rendering |
| Web Audio API | Procedural engine and sound effects |
| WebKit / SwiftUI | Native iOS application wrapper |
| LocalStorage | Settings and personal leaderboard |

---

## 📂 Repository Structure

Suggested GitHub repository layout:

```text
WhiteWindow/
├── index.html
├── README.md
├── LICENSE
└── iOS/
    └── WhiteWindow.xcodeproj
```

The browser game can run as a single HTML file.

The complete iOS source directory and associated assets must be retained for native builds.

---

## 📱 iOS Browser Limitations

Apple places restrictions on browser orientation and fullscreen functionality.

White Window includes a landscape-style rotation workaround for browsers that do not allow physical orientation locking.

For the best experience:

- Open the game directly in Safari.
- Use **Add to Home Screen** for a more app-like experience.
- Rotate your device to landscape where supported.
- Use the native iOS version when strict landscape orientation is required.

Some embedded browsers, including Facebook Messenger's in-app browser, may impose additional restrictions.

A website cannot guarantee that an external application will automatically open Safari.

---

## 🏁 Objective

**Drive as far as possible without being caught.**

Every kilometre brings more traffic, greater danger and increasing pressure from the police.

Your speed depends on how effectively you accelerate, but pushing too hard makes visibility worse.

Balance speed, steering, braking and visibility to survive.

There is no finish line.

Only your distance.

---

## 🔧 Development Status

**Current Edition:** Neon Highway — Landscape Edition v3.1

The game includes a browser-playable implementation and an iOS source project.

The HTML has undergone JavaScript syntax checks. Native iOS compilation and real-device gameplay verification are still required.

### Potential Future Improvements

- Additional highway environments and weather conditions.
- Improved vehicle models and cockpit textures.
- Dynamic day/night transitions.
- Enhanced particle effects and lighting.
- More detailed crashes and vehicle damage.
- Game controller support.
- Online leaderboards.
- Native iOS optimisations.

---

## 📜 License

No licence has been specified yet.

If you plan to make the project open source, add an appropriate `LICENSE` file to the repository. Until then, publishing the source does not automatically grant others permission to reuse or redistribute it.

---

**WHITE WINDOW**

*Jerk. Wipe. Survive.*

🚗 Drive recklessly. Wipe frequently. Explain absolutely nothing. 😂
