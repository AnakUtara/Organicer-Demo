# 📱 Organicer – AI-Powered Organizer App (Demo)

This is a **feature demo showcase** of `Organicer`, a cross-platform mobile app that helps users automatically identify and organize physical items using on-device image processing and AI-powered image labeling.

⚠️ **Note:** This repo contains only a video preview and description of the app. The full source code remains private.

---

## 🎥 Demo Video

Watch a short demo of the core flow:
- Authentication: Sign in & Sign up
- Capture a single photo of multiple organized items
- Detect and crop objects using ML Kit
- Analyze each item with Gemini API
- Display and edit labeled results in a dynamic form

  
👉 [View Demo Video - First 2 months(initial)](https://drive.google.com/file/d/1-VuDN4p8-N8clkrakhw6dWXIp-WNyLFG/view?usp=drive_link)
👉 [View Demo Video - 3rd month progress](https://drive.google.com/file/d/1cir8nJ6NVeL_AofV7UV2Y8U32_1Lpxdc/view?usp=sharing)

---

## 🧠 Key Features

- ✨ **AI + ML Integration**: Combines Google ML Kit and Gemini API to process, label, and enrich object data.
- 📸 **Smart Image Workflow**: One photo → multiple object detections → AI-generated labels per item.
- 🔁 **Smooth UX Flow**: Designed with robust transition handling (PopScope, GoRouter, loading states).
- 📂 **Cloud-Ready Architecture**: Built with Firebase Auth, Firestore (emulator during development), and Riverpod for scalable state management.
- 🔒 **Clean Architecture Prep**: Structure loosely follows feature-first separation with maintainability in mind.
- 🧪 **Tested Flow Resilience**: Idle states, background resume, and transitions tested over multiple iterations.

---

## 🧰 Tech Stack

- **Flutter** (cross-platform mobile)
- **Riverpod with riverpod_annotation** + **State Notifier**
- **Firebase**: Auth, Firestore, Emulator Suite
- **Google ML Kit**: Object detection
- **Gemini API via Firebase AI**: Image labeling
- **GoRouter**: Navigation & data passing
- **flutter_dotenv**: Multi-environment config
- **build_runner**: Code generation
- **freezed**: Immutable States
- **json_serializable**: Model JSON transformer
- **camerawesome**: Camera
- **flutter_form_builder**: React Hook Form & Formik style form handling

---

## 📍 Current Status

The app is currently under active development and is being prepared for an early access release.
This repo serves as a professional preview for portfolio and job application purposes.

---

## 🔒 License

This demo content is licensed under the  
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You may **view and share** this content, but you may not reuse, modify, or distribute it for commercial purposes.

---

## 🙋‍♂️ About the Developer

I’m a career-switcher and self-taught developer with a background in creative work and a passion for building meaningful tools. `Organicer` is my most ambitious solo project to date — combining technical depth, real-world utility, and personal vision.

If you're hiring or just curious, feel free to [reach out](mailto:tok.riady@gmail.com)!


