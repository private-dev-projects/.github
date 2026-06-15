# Hi, I'm Stefanie 👋

I'm a fullstack software developer with a focus on mobile app development, web development, and AI-powered applications. I enjoy working across the entire stack — from React Native frontends to Spring Boot backends — and I'm currently expanding into AI integration with Claude.

---

## Tech Stack

**Frontend & Mobile:** Angular, React Native, Expo, JavaScript, TypeScript, HTML, CSS  
**Backend:** Java, Spring Boot, PHP  
**AI & ML:**  Modal (Serverless GPU), Claude API (Anthropic)  
**Runtime & Tooling:** Bun, Git, Docker, GitHub Actions, EAS Build & Update  
**Other:** REST APIs, i18n / Localization, RevenueCat (In-App Purchases)

---

## Projects

### 📝 ToDo App *(Work in Progress · developed with Claude)*
**Offline-first mobile task and note manager — React Native + custom Bun/Hono backend**

A cross-platform app for creating and managing notes with nested task lists, priorities, due dates, and reminders. Fully usable without an account; optional cloud sync and consent-based sharing via a self-built REST API with its own authentication stack.

**Highlights:**
- 📱 Cross-platform (**iOS & Android**) with **React Native 0.81** and **Expo SDK 54**, New Architecture enabled
- ⚡ **Bun + Hono** backend — near-instant cold start, built-in TypeScript, no separate build step
- 🗄️ **Self-hosted PostgreSQL 16** with Docker; optional **Redis** for distributed rate limiting
- 🔐 **Custom authentication** — JWT access tokens (HS256, 15 min) + opaque refresh tokens with rotation and reuse detection (theft detection via family invalidation); passwords hashed with **Argon2id**
- 🛡️ Security-first: brute-force protection, account enumeration prevention, **HaveIBeenPwned** breach checks, NIST SP 800-63B password policy, structured audit logging
- 🔄 **Offline-first** — all data lives locally in AsyncStorage; manual sync uploads/downloads full state
- 🤝 **Consent-based sharing** via invitation system — recipients only get access after explicitly accepting; works for both individual notes and folders
- ✅ Nested tasks (todos + subtasks), priority levels, color tags, due dates, drag-and-drop reordering
- 🔔 Local reminders via system notifications — no external push service required
- 🌙 Light/Dark mode; full-text search, filters, four sort modes
- **TypeScript end-to-end**; 13 frontend test suites (Jest) + backend security unit tests (bun test)

**Tech:** React Native · Expo · TypeScript · Bun · Hono · PostgreSQL · Redis · Docker · Argon2id · JWT · AsyncStorage · expo-secure-store · Reanimated 4 · React Context API

---

### 🎨 Coloring Pictures — AI-Powered Coloring App
**Published on iOS & Android · * · [View on App Store](https://apps.apple.com/de/app/coloring-pictures/id6756795786)

A mobile app where users can choose from a collection of SVG images and color them digitally. Finished artwork can be saved and printed. 

**Highlights:**
- Published on the **Apple App Store**
- Cross-platform with **React Native 0.81** and **Expo SDK 54**
- **Multilingual** (German, English, and more) via i18next + expo-localization
- **In-app purchases** and subscription model via RevenueCat
- SVG rendering with touch and swipe gestures
- CI/CD pipeline with **GitHub Actions** and **EAS Build**
- Over-the-air updates without App Store approval
- Hermes JS Engine with New Architecture enabled

**Tech:** React Native · Expo · React Navigation · i18next · RevenueCat · react-native-svg · Axios

---



## Code Access

Most of my repositories are private. If you'd like to review the source code as part of a hiring process, feel free to reach out — I'll grant read access promptly.

[Email](mailto:coloringpicturesforkids@gmail.com) · [LinkedIn](https://linkedin.com/in/stefanie-b-90113a217/)
