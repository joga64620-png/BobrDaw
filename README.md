<img width="1919" height="1136" alt="Снимок экрана 2026-11-09 143551" src="https://github.com/user-attachments/assets/f6a155f2-b0fc-4cd6-8a92-2bf9f4922b44" />

# BobrDAW 1.0.0 🦫🎹

**BobrDAW** is a lightweight, free, and intuitive Digital Audio Workstation (DAW) written in Python. The project is designed for those who want to start making music without overloading their computer with heavy software, and for those who love math and programming.

![Piano Roll Screenshot](link_to_screenshot_1.png)

## ✨ Key Features

*   **Piano Roll:** A full 128-key MIDI grid with infinite scrolling support (up to 65,535 columns).
*   **Mixer:** 5 independent tracks (Melody, Bass, Drums, Guitar, Custom) with volume control, Mute, and Solo functions.
*   **Custom Instrument Creation:** Built-in math synthesizer! You can input your own formulas (e.g., `np.sin(freq * t * 2 * np.pi) * np.exp(-3*t)`) to create unique sounds.
*   **ZIP Sample Support:** Load `.zip` archives containing `.wav` files directly into the program to use real instrument sounds.
*   **Multi-language Support:** The interface is available in 5 languages: English, Русский, 中文, Deutsch, Español.
*   **Export:** Save projects in `.bobrdaw` format, and export finished tracks to WAV and MP3.
*   **Plugins:** Basic system for loading custom extensions.

## 🚀 Installation and Setup

### Option 1: Pre-built Version (Windows)
1. Go to the **[Releases](../../releases)** section of this repository.
2. Download the latest `.zip` archive with the program.
3. Extract the archive to any convenient folder.
4. Run `main.exe`.

*(Note: Due to the lack of a paid digital signature, Windows Defender or antivirus software might falsely flag the `.exe`. You can add the file to exceptions or build the project yourself from source).*

### Option 2: Running from Source (for Developers)
Make sure you have Python 3.10 or higher installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/BobrDAW.git
   cd BobrDAW
