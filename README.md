# FitForge 🏋️

AI-powered workout plan generator built with React Native (Expo SDK 54), TypeScript, Expo Router, and Zustand.

## Features
- Branching questionnaire (12-18 questions)
- Iron Avatar — animated SVG body that evolves during onboarding
- Research-backed AI plan generation (Gemini / Claude)
- Injury-aware exercise selection with pain trigger profiles
- Volume algorithm (MEV/MAV/MRV) with stress/recovery multipliers

## Stack
- **Framework:** Expo SDK 54, React Native 0.81.5
- **Routing:** Expo Router 6
- **State:** Zustand 5
- **Animations:** react-native-reanimated + react-native-svg
- **AI:** Gemini 2.0 Flash (primary), Claude Sonnet (fallback)

## Setup
```bash
npm install
npx expo start
```

Add your AI key to `.env`:
```
EXPO_PUBLIC_GEMINI_API_KEY=your-key-here
```

## Status
MVP — Onboarding + AI Plan Generation complete. Workout tracking not yet built.
