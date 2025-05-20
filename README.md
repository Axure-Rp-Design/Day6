# HCI Interaction Prototype – Axure RP

This project is a **Human-Computer Interaction (HCI) interactive prototype** built using **Axure RP**. It demonstrates advanced gesture interactions (tap and swipe) between dynamic panels, focusing on smooth animation and user control feedback.

## 🧩 Features

- Tap on the **info panel** to:
  - Slide the panel up (200ms)
  - Move the image panel up by 100px (linear, 200ms)
  - Set selection state of the image panel to `true`

- Swipe down on the **image panel**:
  - Move it down by 100px (linear, 200ms)
  - Hide the info panel (slide down, 200ms)
  - Set selection state to `false`

- Swipe down on the **info panel**:
  - Triggers the `swipe down` event of the image panel via **Fire Event** interaction

## 📸 Output Preview

### 🔽 Image
![Output Image](2020ICT85.png)

### 🎥 Video

[▶️ Click here to watch the output video](https://github.com/Axure-Rp-Design/Day6/blob/main/output.mp4)
![Output Video](https://github.com/Axure-Rp-Design/Day6/blob/main/output.mp4)
> Ensure both `output-image.png` and `output-video.mp4` are placed in the same directory as this README.

## 📁 Files Included

- `2025_05_20(HCI)P.rp` – Main Axure RP project file
- `output-image.png` – Screenshot of the interaction
- `output-video.mp4` – Demo video showing the working prototype
- `README.md` – This documentation file

## 📦 How to Open

1. Open **Axure RP** (version 9 or later recommended).
2. Load the project file:  
   `File → Open → 2025_05_20(HCI)P.rp`
3. Preview using `F5` or export to HTML to test swipe/tap interactions.

## 🛠️ Developed Features

- Condition-based panel movement
- Animated state transitions
- Reusable gestures using Fire Event logic
- Realistic interaction behavior for mobile prototypes

---

📬 For any suggestions or improvements, feel free to contact the author.

