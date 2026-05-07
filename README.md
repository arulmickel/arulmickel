<!-- Banner -->
![Header](https://capsule-render.vercel.app/api?type=waving&color=0:2C3F26,100:6B9459&height=200&section=header&text=Arul%20Michael%20Antony&fontSize=40&fontColor=ffffff&animation=fadeIn)

Hii, I'm Arul Michael Antony Felix Raja(I get it, my name is long)

**M.S. Computer Science (AI Concentration)** @ DePaul University, Chicago  
**Android Developer** | **Test Automation & SDET** | **AI-Integrated Development** | **Meta Android Certified**  

4 years of hands-on experience building native Android applications in **Kotlin** and **Java**, with deep focus on **test automation frameworks, Espresso & Compose UI testing, and CI/CD reliability** - plus **AI-Integrated development workflows**.

**Portfolio:** [arulmickel.github.io/portfolio-](https://arulmickel.github.io/portfolio-/)

---

## Quick Links
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-2C3F26?logo=google-chrome&logoColor=white)](https://arulmickel.github.io/portfolio-/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/arul-michael-antony-f-661260187/)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:arulmichaelantonyf@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-blue?logo=kaggle)](https://www.kaggle.com/arulmichaelantony)
[![Meta-Certificate]([https://img.shields.io/badge/Kaggle-Profile-blue?logo=kaggle](https://pngimg.com/image/110792))]([https://www.kaggle.com/arulmichaelantony](https://www.credly.com/badges/43d31ac1-b650-462d-a740-7a5b8babca1c/public_url))

---

## Skills Matrix

| **Area** | **Tech / Tools** |
|---|---|
| **Test Automation & SDET** | Espresso, Compose UI Test, JUnit 4, MockK, Truth, Turbine, Hilt test rules (`@UninstallModules` + `@BindValue`), MockWebServer, kotlinx-coroutines-test, Room in-memory DBs, Page Object Model, test data builders, flake reduction, animations-disabled test runs |
| **Android Development** | Kotlin, Java, Android SDK, Jetpack Compose, XML Layouts, MVVM, MVC, Clean Architecture, ViewModel, LiveData, Coroutines, Flow, Room, WorkManager, Retrofit, OkHttp, Material Design, Google Play Store Publishing |
| **AI-Assisted Development** | Windsurf AI, AI-powered Code Generation & Refactoring, AI Code Review & Validation, Prompt Engineering for Code Quality |
| **Firebase & Services** | Firebase Auth, Firestore, FCM, Crashlytics, Google Play Services (Maps/Location), Google Play Console |
| **Debugging & Profiling** | Android Profiler, LeakCanary, Logcat, Crashlytics, ANR analysis, memory leak triage |
| **Backend & APIs** | RESTful APIs (JSON), Spring Boot, Flask, MongoDB, AWS (EC2, S3, Lambda, DynamoDB, CloudWatch), Secure Data Storage |
| **DevOps & CI/CD** | Git, GitHub Actions, Jenkins, Docker, Postman, Linux, Bash, CI/CD Pipelines, Selenium Grid |
| **Methodologies** | Agile/Scrum, Code Reviews, Secure Coding Practices, Mobile Application Security, TDD |
| **Languages** | Kotlin, Java, Python, SQL, JavaScript, C++ |

---

## Experience

### Android Developer - Digital Factory (Chicago, IL) `Sep 2025 - Present`
- Dependency Injection & Modularization: Refactored feature modules using Hilt and Gradle Kotlin DSL, enabling parallel feature development across teams and reducing incremental build times by ~30%.
- Reactive State Management: Implemented Unidirectional Data Flow (UDF) with StateFlow and SharedFlow across 12+ Compose screens, eliminating UI race conditions and producing predictable, testable screen states.
- Performance & Stability Monitoring: Integrated Firebase Crashlytics and Android Vitals dashboards to track ANRs, cold-start, and slow-frame rates; reduced p95 cold-start by 22% via Baseline Profiles and lazy initialization of non-critical components.
- Offline-First Caching: Designed an LRU in-memory cache layered over Room as the single source of truth, delivering sub-100ms reads for hot location data and seamless offline operation for field users.
- Map & Location Features: Integrated Google Maps SDK with custom marker clustering, polygon overlays, and geofence visualizations for field-service workflows handling 1,000+ active sites with low frame-drop rates.
- Test Framework: Built a Page Object Model (POM) test framework on top of Espresso and JUnit, achieving 70%+ coverage on critical flows and wiring it into GitHub Actions for every pull request.
- Accessibility & Material 3: Migrated UI components to Material 3 design tokens and added TalkBack support, semantic content descriptions, and dynamic font scaling to meet WCAG 2.1 AA compliance.
- Secure Storage: Implemented Android KeyStore-backed encrypted token storage and BiometricPrompt re-authentication for high-privilege actions, hardening the app against on-device credential theft.
- Code Quality Gates: Introduced Detekt and ktlint static analysis with pre-commit hooks and CI checks, standardizing Kotlin style across the team and shortening PR review cycles.

- ### Android Developer - Knight Group (EV Startup - India) `Oct 2022 – Aug 2023`
- Vehicle Control App: Developed a Tesla-like companion app that allows the control of the vehicle remotely (lock, unlock, horn, light, Summon), charging, and pre-conditioning, utilizing Kotlin Coroutines, StateFlow, and IbSocket connections to control the vehicle’s systems.
- Phone Key and BLE Passive Entry: Developed passive entry via Bluetooth Low Energy that would allow unlocking and starting the car when the user gets close to the car, focusing on developing a low-latency solution and managing services and handshakes.
- Live Camera and Energy Dashboard: Developed live camera streams for monitoring Sentry mode/Dashcam, utilizing Media3/ExoPlayer, as Ill as an energy monitoring dashboard (PoIrwall, solar, and grid consumption) through Jetpack Compose.
- Security and Cross-functional Work: Developed end-to-end encryption via Android Keystore for safety-critical commands from the app to the vehicle; worked cross-functionally with embedded firmware, backend, and product design engineers to develop vehicle-to-app API contracts.

### App Engineer - Tata Consultancy Services (India) `May 2022 – Sep 2022`
- Android API Integration: Built REST clients on the Android side using Retrofit and OkHttp interceptors with Gson serialization and centralized error handling, consumed by client mobile applications.
- UI Development: Developed Android screens in Kotlin and Java using XML layouts, ConstraintLayout, and RecyclerView adapters with DiffUtil, implementing pagination and pull-to-refresh on data-heavy list views.
- Offline Caching: Implemented Room-backed local caching of API responses to enable offline reads and reduce redundant network calls by 35% on low-bandwidth field devices.
- Crash Reporting & Telemetry: Integrated Firebase Crashlytics and Analytics into Android builds, surfacing top crash signatures and key funnel events to product stakeholders for prioritization.
- Build Pipelines: Configured Gradle build variants (debug/staging/prod) and signed APK generation, enabling QA to receive nightly builds via Jenkins for faster regression turnaround.

### Junior Android Developer - HumCen (India) `Jan 2021 – April 2022`
- App Bootstrapping & Architecture: Bootstrapped the Android app from scratch using MVVM with ViewModel, LiveData, and the Repository pattern, establishing a modular package structure that scaled to 8+ feature modules over the project lifecycle.
- UI Development: Built 20+ customer-facing screens in Kotlin with XML layouts, ConstraintLayout, RecyclerView with DiffUtil, and Material Components for patent search, IP-filing forms, and consultant chat flows.
- Networking Layer: Designed the REST networking layer with Retrofit, OkHttp logging interceptors, and Gson, implementing OAuth token refresh and standardized error handling across 25+ API endpoints.
- Local Persistence: Implemented Room for offline storage of patent drafts and user data, including type converters for complex objects and migrations across 4 schema versions without data loss.
- Authentication & Push: Integrated Firebase Authentication (email and phone OTP) and Firebase Cloud Messaging (FCM) for real-time push notifications on patent application status changes.
- Async Refactor: Migrated legacy callback-based async code to Kotlin Coroutines and Flow, simplifying error propagation and reducing networking-layer boilerplate by ~40%.
- Testing: Wrote unit tests with JUnit and Mockito for ViewModels and repositories, plus instrumentation tests with Espresso for critical onboarding and submission flows.
- Performance Optimization: Profiled UI rendering with Android Studio Profiler and Layout Inspector, lowering dropped-frame rates on the patent listing screen from 14% to under 2%.
- Image Loading: Integrated Glide for caching and transforming patent diagrams and consultant avatars, with disk-cache strategies tuned for low-RAM devices common in the target market.
- Release Management: Owned Play Store release tasks including ProGuard/R8 shrinking and obfuscation, signed App Bundle (AAB) generation, staged rollouts, and crash-rate monitoring via Firebase Crashlytics.
- Collaboration & Mentorship: Partnered with backend engineers to define API contracts in Swagger, conducted code reviews on pull requests, and onboarded an incoming intern on Android fundamentals before transitioning out of the role.

---

## Featured Projects

### MapTest Framework -Android Maps SDET Framework
*Kotlin | Jetpack Compose | Espresso | Compose UI Test | Hilt | Room | Retrofit | MockWebServer | MockK | Page Object Model*  
Production-style Android Maps app paired with a comprehensive SDET test framework. Demonstrates **Page Object Model** architecture, **Hilt-based test doubles** via `@UninstallModules` + `@BindValue`, **MockWebServer** for deterministic networking, **in-memory Room** for DAO tests, and **DSA in real context** (LRU cache, Trie autocomplete, BFS/Dijkstra route graph, Haversine distance). Launches without API keys via a graceful fallback UI -designed to be runnable on any reviewer's machine.  
🔗 [View Repository](https://github.com/arulmickel/Map-Test-Framework)

### BorBuddy -Social Media App
*Kotlin | Jetpack Compose | MVVM | Room | WorkManager | Windsurf AI*  
Full-featured social network with real-time feeds, secure auth, and offline-first architecture. Leveraged Windsurf AI for rapid prototyping.  
🔗 [View Repository](https://github.com/arulmickel/BorBuddy-app)

### Parking Finder -Location & Maps App
*Kotlin | Google Play Services | Room | Retrofit | Espresso*  
Geolocation-powered parking finder with offline caching, retry/backoff, Material Design, and Espresso UI tests.  
🔗 [View Repository](https://github.com/arulmickel/Parking-Finder-app)

### React Native Banking UI -Cross-Platform App
*React Native | JavaScript | REST APIs | Accessibility | Section 508/WCAG*  
Multi-screen banking front-end with reusable components, mock API layer, and accessibility compliance.  
🔗 [View Repository](https://github.com/arulmickel/React-Native-Banking-UI)

### DermAI -Skin Lesion Classifier
*Python | PyTorch | ResNet18 | Transfer Learning | CNN*  
Multi-class image classification pipeline for 7 skin lesion categories from ISIC 2018 dataset with F1/AUC evaluation.  
🔗 [View Repository](https://github.com/arulmickel/DermAI-ISIC2018-Skin-Lesion-Classifier)

### Deepfake Classifier -Vision Transformers
*Deep Learning | Image Processing | Grad-CAM | Vision Transformers*  
AI-generated deepfake image detection with Grad-CAM interpretability techniques.  
🔗 [View Repository](https://github.com/arulmickel/deepfakedetect-vit)

### AI Code Generator -Screenshot to Code
*Python | OpenCV | YOLOv8 | Flask | Docker*  
Web-based system generating HTML/CSS/JS from UI screenshots using computer vision + LLM workflow.  
🔗 [View Repository](https://github.com/arulmickel/vision-to-code)

---

## Education

**DePaul University -Chicago, IL**  
M.S. Computer Science (AI Concentration) -*Nov 2025*  

**Relevant Courses:** Data Structures & Algorithms, Database Management Systems, Distributed Systems, Object-Oriented Development, Programming Language Concepts, AI, Computer Vision, Neural Networks

---

## Certifications
- **Meta Android Developer Professional Certificate**
[Verify on Credly](https://www.credly.com/badges/43d31ac1-b650-462d-a740-7a5b8babca1c/public_url)
---

## Extracurricular
- **Google Developer Group** (2017–2018) -Android Study Jams, Kotlin bootcamps
- **DePaul CS Society** (2023–2025) -Led Android workshops, mentored undergrads
- **IEEE Computer Society** (2017–2020) -Design Head, led 15 members, 10+ workshops

---

## GitHub Stats
![Arul's GitHub Stats](https://github-readme-stats.vercel.app/api?username=arulmickel&show_icons=true&theme=vue-dark&hide_border=true&bg_color=1A2617&title_color=8BAF7C&icon_color=6B9459&text_color=D1DFC9)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=arulmickel&layout=compact&theme=vue-dark&hide_border=true&bg_color=1A2617&title_color=8BAF7C&text_color=D1DFC9)

---

## Let's Connect
Email: [arulmichaelantonyf@gmail.com](mailto:arulmichaelantonyf@gmail.com)  
LinkedIn: [linkedin.com/in/arul-michael-antony-f-661260187](https://www.linkedin.com/in/arul-michael-antony-f-661260187/)  
Portfolio: [arulmickel.github.io/portfolio-](https://arulmickel.github.io/portfolio-/)  
Kaggle: [kaggle.com/arulmichaelantony](https://www.kaggle.com/arulmichaelantony)

---

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:6B9459,100:2C3F26&height=150&section=footer)
