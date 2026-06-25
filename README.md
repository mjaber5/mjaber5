<div align="center">

# Mohammed Jaber

**Mobile Engineer · Flutter · Mobile Security**

Building secure, production-grade mobile experiences for digital banking and beyond.

<img src="https://komarev.com/ghpvc/?username=mjaber5&label=Profile%20Views&color=1F2937&style=flat-square" alt="Profile views"/>
<img src="https://img.shields.io/github/followers/mjaber5?label=Followers&style=flat-square&color=1F2937" alt="Followers"/>

[About](#about-me) · [Tech Stack](#tech-stack) · [Experience](#experience) · [Open Source](#open-source-work) · [Projects](#featured-projects) · [Contact](#lets-connect)

</div>

<br/>

## About Me

Mobile engineer with **3+ years** of hands-on Flutter development, including production work across **digital banking**, SaaS workforce platforms, server-driven e-commerce, and enterprise field operations. My background spans native Android (Java) and cross-platform Flutter, with a growing focus on **mobile application security**.

I designed a runtime security architecture for a digital banking platform — adaptive threat signals, risk-based access control, and **OWASP MASVS**-aligned resilience across native Kotlin/Swift detection layers and a Flutter risk engine. Author of **2 open-source Flutter packages** on pub.dev.

**Currently**
- Building the security & risk layer for a digital banking app at **MUJEER**
- Deepening expertise in mobile application security — root/jailbreak detection, hooking-framework checks, fail-secure design
- Maintaining [`adaptive_foreground`](https://pub.dev/packages/adaptive_foreground) and [`veil_ui`](https://pub.dev/packages/veil_ui) on pub.dev
- B.Sc. in Computing Smart Devices — Tafila Technical University (2025)

<br/>

## Tech Stack

**Mobile**

![Flutter](https://img.shields.io/badge/-Flutter-1F2937?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/-Dart-1F2937?style=flat-square&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-1F2937?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-1F2937?style=flat-square&logo=swift&logoColor=white)

**Architecture**

![Clean Architecture](https://img.shields.io/badge/-Clean%20Architecture-1F2937?style=flat-square)
![BLoC/Cubit](https://img.shields.io/badge/-BLoC%2FCubit-1F2937?style=flat-square)
![MVVM](https://img.shields.io/badge/-MVVM-1F2937?style=flat-square)
![SOLID](https://img.shields.io/badge/-SOLID-1F2937?style=flat-square)
![Server--Driven UI](https://img.shields.io/badge/-Server--Driven%20UI-1F2937?style=flat-square)

**Security**

![OWASP MASVS](https://img.shields.io/badge/-OWASP%20MASVS-1F2937?style=flat-square)
![Biometric Auth](https://img.shields.io/badge/-Biometric%20Auth-1F2937?style=flat-square)
![Secure Storage](https://img.shields.io/badge/-Secure%20Storage-1F2937?style=flat-square)

**Backend & Tooling**

![Firebase](https://img.shields.io/badge/-Firebase-1F2937?style=flat-square&logo=firebase&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-1F2937?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/-Git-1F2937?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-1F2937?style=flat-square&logo=github&logoColor=white)
![Android Studio](https://img.shields.io/badge/-Android%20Studio-1F2937?style=flat-square&logo=androidstudio&logoColor=white)
![Xcode](https://img.shields.io/badge/-Xcode-1F2937?style=flat-square&logo=xcode&logoColor=white)

<br/>

## Experience

**Mobile Engineer · MUJEER** — Amman, Jordan &nbsp;|&nbsp; *Jun 2025 – Present*

<details>
<summary><b>Digital Banking Application</b></summary>
<br/>

- Built a native security layer (Kotlin + Swift) with root/jailbreak detection, emulator identification, debugger detection, and hooking-framework checks (Frida, Xposed)
- Designed a centralized risk engine with graduated responses — allow, limited, step-up verification, block — aligned with OWASP MASVS-RESILIENCE
- Implemented a fail-secure architecture with AES-encrypted API communication for financial transactions
- Developed OTP & biometric auth flows, P2P/CliQ/IBAN payment modules, and eFAWATEERcom bill-payment integration
- Reduced cold-start time by ~3 seconds through lazy loading and startup performance tuning

</details>

<details>
<summary><b>Basma — SaaS Attendance & Workforce Management</b></summary>
<br/>

- Engineered a geofenced clock-in/out engine with GPS proximity validation and biometric session binding (Face ID / Touch ID) via `flutter_secure_storage`
- Built role-based UI across Employee, Manager, and HR roles with leave-approval pipelines, real-time status tracking, and native home-screen widgets (iOS & Android)
- Architected a secure network layer using Dio and auth interceptors on a feature-first Clean Architecture with GetIt DI

</details>

<details>
<summary><b>Neelli — Server-Driven E-Commerce Platform</b></summary>
<br/>

- Designed a hybrid SDUI rendering engine letting non-engineering teams modify Home, Shop, Offers, and Campaign layouts without new releases — JSON-to-Widget factory with Freezed unions and graceful fallbacks
- Engineered a 15-module feature-first architecture, session lifecycle management, route-level AuthGuard, and a multi-step WebView payment flow

</details>

<details>
<summary><b>Discounter, RidePass, WMS & Hakk Shop</b></summary>
<br/>

- **Discounter** (Palestine Market): full e-commerce experience with OTP auth, checkout, loyalty rewards, and complete Arabic RTL + English LTR support
- **RidePass**: digital transit platform with QR scan-and-go validation, ride history, device-integrity checks, and full AR/EN localization
- **WMS**: enterprise field-operations platform with VoIP/SIP telephony, real-time fleet tracking via Pusher Channels, and native platform channels for device-level call handling
- **Hakk Shop**: guest-user permission system, real-time Firebase chat, OTP phone auth, and a seller reputation system

</details>

<br/>

## Open Source Work

Two MIT-licensed Flutter packages, published and maintained on pub.dev.

<table>
<tr>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/mjaber5/veil_ui/main/assets/demo_appbar.gif" width="220"/><br/>
<sub><b>veil_ui</b> — GlassAppBar</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/mjaber5/veil_ui/main/assets/demo_modal.gif" width="220"/><br/>
<sub><b>veil_ui</b> — Modal Sheet</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/mjaber5/flutter_adaptive_foreground/main/assets/demo.gif" width="220"/><br/>
<sub><b>adaptive_foreground</b> — Live Contrast</sub>
</td>
</tr>
</table>

| Package | Description | Links |
|---|---|---|
| **veil_ui** | iOS-inspired glassmorphism kit — `GlassAppBar`, blurred pinned-CTA overlay, native Cupertino sheets, full dark-mode & RTL support | [pub.dev](https://pub.dev/packages/veil_ui) · [GitHub](https://github.com/mjaber5/veil_ui) |
| **adaptive_foreground** | Auto-selects black/white foreground from background luminance via live `RepaintBoundary` sampling; WCAG-aware contrast flipping | [pub.dev](https://pub.dev/packages/adaptive_foreground) · [GitHub](https://github.com/mjaber5/flutter_adaptive_foreground) |

<br/>

## Featured Projects

| Project | Highlight |
|---|---|
| [**Qanoni**](https://github.com/mjaber5/Qanoni-App) — Legal Contract Management | Crown Prince Award Finalist 2025 · AI legal chatbot, PDF processing, payments — Clean Architecture (MVVM), Firebase |
| **Dispute Management System** | 2nd Place — FinTech Rally 2024, national-level financial dispute-resolution system |
| [**MJS**](https://github.com/mjaber5/MJS) — Social Media App | Full social platform — auth, profiles, real-time likes/comments, follow system, notifications |

<br/>

## Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-1F2937?style=flat-square&logo=googlechrome&logoColor=white)](https://mojaber.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammad-jaber-profile)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mhammdjbr555@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1F2937?style=flat-square&logo=github&logoColor=white)](https://github.com/mjaber5)

</div>
