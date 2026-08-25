![preview](https://raw.githubusercontent.com/williamhuang92/koch-wave-dojo/main/promo_4175c.svg)
[![Download](https://raw.githubusercontent.com/williamhuang92/koch-wave-dojo/main/dl_dbcf0.svg)](https://williamhuang92.github.io/koch-wave-dojo/)

# EchoForge — Tactical Morse & Signal Intelligence Trainer 🛰️

**Master the language of the airwaves, one dit and dah at a time.**

EchoForge is a comprehensive Morse code (CW) and signal intelligence training platform, reimagined for the modern handheld computing era. Inspired by the raw utility of field radios and the meditative focus of the telegraph, EchoForge transforms your R36S or compatible Linux handheld into a personal code-breaking dojo. It is not merely an app; it is a forge where auditory reflexes, visual pattern recognition, and historical knowledge are welded into practical expertise.

---

## 🌟 Why EchoForge? The Art of Silent Communication

In a world saturated with visual noise, Morse code remains the ultimate signal of resilience and clarity. EchoForge ignores the spectacle of modern gaming and focuses on the **craft** of decoding. This trainer is built around the **Koch method**, a proven accelerated learning technique that introduces characters at full speed from the very first session, training your brain to recognize tones as a single gestalt rather than individual dots and dashes.

The project is architected for the R36S handheld’s dual-screen and physical button layout, providing a tactile response that feels like operating genuine WWII-era signal equipment. Whether you are preparing for an amateur radio license, researching historical cryptography, or simply seeking a mentally demanding hobby that works offline, EchoForge provides a distraction-free environment to sharpen your cognitive edge.

---

## 🚀 Core Features: Beyond Basic Beeps

EchoForge goes far beyond simple playback and repetition. It is a complete field kit for the digital radio operator.

### 🎯 Koch Method Adaptive Curriculum
- **Progressive Complexity**: Start with two characters (K & M) and gradually add new letters only when your previous accuracy hits a rising threshold. No more frustrating plateaus.
- **Intentional Speed**: Maintains a steady 20 WPM (Words Per Minute) from day one. You learn to *copy* at speed, not to count dots.
- **Dynamic Error Tracking**: The engine analyzes your mistakes and re-weights future training sessions to target your specific weak points, ensuring efficient neural pathway reinforcement.

### 📡 Waterfall Band Explorer
- **Live Spectral Analysis**: A built-in spectral waterfall display visualizes incoming audio, letting you see characters as visual "time-slivers" while hearing them.
- **Simulated Band Noise**: Realistic atmospheric noise and fading (QSB/QRN) generators simulate real propagation conditions, teaching you to copy through interference.
- **Frequency Snapshot Library**: Store and annotate specific frequency "scenes" to practice decoding difficult signal patterns found in historical recordings.

### 📖 Glossary & Historical Decoder
- **Interactive Reference**: A searchable glossary of over 100 CW abbreviations, Q-codes, and pro-signs (e.g., "QSL," "73," "SK").
- **Reverse Dictionary**: Type an English phrase to see its standard Morse abbreviation; type a code to see its expansion.
- **Historical Context**: In-depth articles on the origins of the Morse code, the details of the International vs. American code, and the evolution of telegraphy in maritime and military use.

### 🏆 Challenge Modes & Leaderboards
- **The "Ghost Sig" Challenge**: Decode a full message retrieved from a synthetic "faded signal" with only 5% of the characters visible.
- **Speed Run**: Compete against the clock to decode 50 random words with zero errors.
- **Local Leaderboards**: Compete against pre-loaded "historical operators" (simulated AI times) or your own previous bests across 10 different difficulty tiers.

### 🕹️ Optimized for Handheld Controls
- **Full Gamepad Support**: Navigate menus, replay audio, and input characters using the R36S physical buttons.
- **Haptic Feedback**: Subtle vibration on successful character entry to reinforce muscle memory.
- **Dark Mode UI**: High-contrast, anti-glare interface designed for long eye-strain-free sessions, even in direct sunlight.

---

## 📊 SEO-Friendly Keywords & Technical Excellence

This project is engineered not just for use, but for **discoverability** and **long-term maintenance**. The codebase is clean, modular, and documented.

- **Primary Keywords**: Morse code trainer, CW practice software, R36S app, amateur radio learning tool, Koch method, Q-codes, telegraphy simulation, signal intelligence, offline learning, Linux handheld game.
- **Secondary Keywords**: Audio waveform visualization, tactile interface, retro computing, skill-based learning, radio operator exam prep, historical simulation.

---

## 🌍 Multilingual & Universal Design

**EchoForge** is designed for a global community of radio enthusiasts.

- **UI Localization**: The interface is fully translated into English, Japanese, Spanish, and German. The core Morse code standard is universal, but the instruction text adapts to the user's language.
- **Audio Cues**: All instructional audio uses standardized microphone tones that are identical across all hardware, ensuring consistent learning on any device.
- **Responsive Layout**: Although optimized for the R36S screen (640x480), the underlying engine uses a scalable resolution matrix. It will gracefully adapt to clamshell devices, tablets, or even a desktop window with a keyboard input overlay.

---

## 🛠️ Architecture & Extension Points

The project is structured into three distinct layers, each independently testable:

1.  **The Signal Core (`/core`)**:
    - Handles the generation of sine waves, timing control, and the WPM/CWT calculations.
    - Includes a `codec` module for converting text to Morse and vice-versa.
    - Fully deterministic audio pipeline for testing.

2.  **The Learning Engine (`/engine`)**:
    - Implements the Koch algorithm and the spaced repetition scheduler.
    - Tracks user performance metrics (accuracy, latency, endurance).
    - Generates the dynamic "waterfall" visual data from the audio buffer.

3.  **The Field Interface (`/interface`)**:
    - The gamepad and touch-screen UI layer.
    - Uses an orthographic projection for fast rendering of the waterfall.
    - Contains the glossary and challenge state machines.

---

## 📜 Licensing & Open Source Philosophy

EchoForge is released under the **MIT License**—the exact open-source agreement that permits commercial use, modification, distribution, and private use, provided the original copyright notice and disclaimer are retained.

**We believe in the open sharing of knowledge.** Just as morse code was a public utility before the internet, this software is a public utility for learning. You are encouraged to fork the repository, adapt the interface for your specific hardware, or contribute new challenge packs.

**Important:** While the software is free to use, we kindly request that you **avoid using the term "free"** when describing your usage tier; instead, we refer to it as the **"Open Frequency"** edition. All core features are available in the "Open Frequency" edition.

---

## 📚 Getting Started: Your First Transmission

EchoForge requires no external account or cloud connection. The initial setup is minimal:

1.  **Acquire the Software**: Download the latest release package for your architecture (ARMv7 or x86_64) from the repository's releases section.
2.  **Transfer**: Copy the `eforge` binary and the `resources/` folder to your SD card or internal storage.
3.  **Execute**: Run the executable from the terminal or the emulator frontend. The application will request permission to access the microphone (for the Band Explorer live mode) but can run entirely in "Generator Mode" without it.
4.  **Calibrate**: The first launch asks for a simple audio volume test to ensure the tone is audible above the device's internal speaker noise.

*Note: For developers, the build system uses a cross-compiler toolchain, but downloading pre-compiled binaries is the recommended path for non-developers.*

---

## 🧑‍💻 Contribution & 24/7 Support Philosophy

While we cannot offer literal 24/7 human phone support, our documentation repository and issue tracker are monitored actively.

- **Discussions**: For questions regarding study methods or CW in general, open a discussion in the "Operations" category.
- **Issue Reporting**: If you encounter a bug (e.g., a waveform glitch or UI overlap), report it via the GitHub issue template.
- **Pull Requests**: We welcome contributions, especially:
    - New historical audio packs.
    - Localization files for additional languages.
    - Improvements to the Koch scheduler algorithm.

### 📮 Roadmap (2026 Vision)

The projected roadmap for 2026 includes:
- **Cross-Device Sync**: Save your progress to a local file (JSON) to transfer between devices.
- **AI "Ghost" Operator**: A more intelligent simulated adversary that sends messages with human-like timing variations (QRS).
- **Hardware HID Support**: Direct USB Keyboard emulation for use with telegraph keys connected via GPIO.

---

## ⚠️ Disclaimer & Signal Notices

**Use at your own risk.**
EchoForge is an educational simulator. It is **not** a certified telegraph receiver or transceiver. The audio output is designed for the internal speaker of handheld devices and should not be used for actual radio transmission.

**Radio Interference**: Do not use the "Simulated Band Noise" generator in close proximity to actual radio receivers, as the electromagnetic emission from the device's speaker may cause unintended interference.

**Medical**: Listening to high-pitched tones for extended periods may cause fatigue in some users. Take a 10-minute break every hour. The app includes a timer feature scheduled for the 2026 update to enforce this.

**Accuracy**: While the Koch method is highly effective, results may vary. The application does not guarantee a specific speed attainment within a set timeframe.

**Legendary Word Note**: This project avoids the term "hack" in all documentation, as we consider this learning process a "**Strategic Decoding Evolution**" or "**SDE**."

---

## 📄 License & Legal

This project is licensed under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.** IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Click here to view the full [LICENSE](LICENSE) file for the legal text.

---

## ✨ Closing the Loop

EchoForge is more than a training tool; it is a **bridge to a bygone era of communication** that persists in emergency bands and ham radio communities today. It turns a gaming device into a precision instrument for the mind.

73 & Good DX, from the EchoForge Operations Team.

*Last updated: January 2026*