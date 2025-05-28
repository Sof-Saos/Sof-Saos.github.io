# 📱 Didactik AR - Educational Augmented Reality Experience

**Didactik AR** is an interactive web-based augmented reality (AR) application designed to enhance learning experiences for children using marker-based tracking. Built with [MindAR.js](https://hiukim.github.io/mind-ar-js-doc/) and [A-Frame](https://aframe.io/), this project brings educational content to life through physical image targets that, when scanned, reveal relevant 2D visuals.

## 🧠 Features

- 🎯 Multiple **image targets** for different educational themes:
  - Mathematics (types of angles)
  - Reading comprehension in spanish
  - English learning: Topics suach as: Emotions, Family, Home, School, Animals, Body
- 📄 Markers are printed and recognized by the camera to trigger AR content.
- 📐 All virtual content is displayed as if it were "stuck" to the real-world surface.
- ⚡ Light, fast and browser-friendly — no app install required!

## 🛠️ Built With

- [MindAR.js](https://github.com/MindAR-js/): Marker-based AR library
- [A-Frame](https://aframe.io/): Web framework for building 3D/AR/VR experiences
- Vanilla HTML, CSS and JavaScript

## 🖼️ How It Works

1. Open this webpage https://sof-saos.github.io/ with a device that has a camera. 
2. Grant camera permissions when prompted.
3. Point the camera at any of the printed markers (image targets).
4. See the relevant AR visuals appear on top of the marker in real time.

## 🗂️ File Structure

```bash
Assets/                 # All educational images (PNG format)
targets.mind            # MindAR compiled image target file
index.html              # Main AR scene with MindAR & A-Frame
README.md               # Project description and setup
