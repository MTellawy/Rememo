🧠 Rememo - Minimal Typing & Memorization Test

Rememo is a minimalist, distraction-free web application designed to help users practice typing and memorize texts. Whether you are practicing a speech, a script, or just improving your typing accuracy, Rememo provides a strict, real-time validation environment that ensures perfect recall.

✨ Key Features

Strict Real-Time Validation: Incorrect keystrokes are instantly blocked, and the screen flashes red to alert you. You cannot proceed until you type the exact correct character.

Two Practice Modes:

👁️ Easy Mode: The target text is visible as a faint "ghost" text in the background, guiding your typing perfectly.

😑 Hard Mode: The target text is completely hidden, forcing you to rely entirely on your memory.

Advanced Text-to-Speech (TTS): Listen to the text being read aloud. You can dynamically increase or decrease the reading speed in real-time without the audio restarting. It automatically defaults to premium voices (like Microsoft Brian on Edge or Google US English on Chrome).

File Upload & Drag-and-Drop: Easily import your own study materials. Supports drag-and-drop for .txt, .pdf, .doc, and .docx files while preserving their original paragraph formatting.

Smart Auto-Scrolling: The text area automatically scrolls as you type, keeping the blinking cursor perfectly centered on your screen for maximum comfort.

Anti-Cheat System: Text selection and copying are completely disabled globally to enforce actual typing and memorization.

Persistent Settings: All your preferences (Theme, Mode, Font, Size, Reading Speed, and Voice) are saved locally in your browser and automatically applied the next time you open the app.

Cinematic Settings UI: An ultra-minimal, full-screen settings menu inspired by movie end-credits for a premium feel.

🛠️ Technologies Used

Rememo is built with a lightweight, dependency-free core, utilizing only native web technologies along with two specialized libraries for document parsing:

HTML5, CSS3, Vanilla JavaScript: Core application logic and UI.

PDF.js: Used to extract raw text from uploaded .pdf documents.

Mammoth.js: Used to extract raw text from Word documents (.docx).

Web Speech API: Powers the native Text-to-Speech functionality.

🚀 Getting Started

Since Rememo is a purely client-side application, no build tools or server setup are required.

Clone the repository:

git clone [https://github.com/yourusername/rememo.git](https://github.com/yourusername/rememo.git)


Open the app:
Simply open the index.html file in any modern web browser (Google Chrome or Microsoft Edge recommended for the best TTS experience).

⚙️ Customization & Controls

Hover over the top of the screen to reveal the hidden toolbar. From there, you can control:

Mode Switch: Toggle between Easy (👁️) and Hard (😑) modes.

Typography: Change the font family (Poppins, Arial, Times New Roman, Courier New, Georgia) and adjust the font size dynamically using the - and + buttons.

Audio Controls: Play/Pause the TTS reading, and use the adjacent arrow buttons to adjust reading speed on the fly.

Theme Toggle: Switch between Dark Mode (default) and Light Mode.

Start Over: Reset your progress to the beginning of the text.

Upload: Manually select a file to practice, or simply drag and drop a file anywhere on the screen.

Settings Menu: Open the full-screen cinematic settings menu to set your default preferences.

📝 How to Use

Load your text either by pasting it, uploading a document, or dragging a file onto the screen.

Select your preferred mode (Easy or Hard).

Start typing! The text is case-insensitive, but you must type all punctuation (commas, periods, etc.) exactly as they appear in the original text.

If you make a mistake, the screen will flash red, and the keystroke will be ignored. Correct the mistake to continue.

Watch the top progress bar fill up as you approach 100% completion.

📄 License

This project is open-source and available under the MIT License.
