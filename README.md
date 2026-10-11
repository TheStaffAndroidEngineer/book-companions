# The Staff Android Engineer — companion code

First-edition source code for *The Staff Android Engineer: Designing, Diagnosing, and Evolving Android Systems* by Rajesh Pattanaik.

The projects below retain their frozen `first-edition-2026.10` tags. Download the [compact source ZIP (packaging revision 2)](https://github.com/TheStaffAndroidEngineer/book-companions/releases/download/first-edition-2026.10-r2/the-staff-android-engineer-first-edition-2026.10-r2-source.zip), which preserves the `code/projects/` layout required by shared investigation tools. Extract it alongside the paid companion guide.

Before opening or building an Android project from this compact download, run `python3 code/setup.py --project commerce-app` from the extracted package folder, replacing `commerce-app` with its project name. Use `--list` to list projects or `--all` to prepare them all. Python 3.9 or newer is required; use `python` if that is your Python 3 command. Setup restores exact original images and fonts offline. The download stores them once; preparing projects increases disk use. Individually cloned repositories already include their assets and need no preparation step.

Revision 2 removes author-only scripts and fetches the pinned Chapter 24 bundletool on demand with SHA-256 verification. Application source, image quality, fonts and chapter checkpoints are unchanged. `code/PACKAGE.json` documents distribution changes relative to the original source archive.

Original companion code is MIT licensed. Required third-party notices and assets retain their own terms. Book chapters, exercises, written solutions and detailed reader guidance are supplied with the purchased book.

Use JDK27 and the pinned Gradle wrappers. Set `ANDROID_HOME` to the SDK specified by each project. Individual READMEs describe build/service entry points. For root JVM labs, run `./gradlew test` inside the bundle’s `code/` directory.

| Chapter | Code repository | First-edition version |
| --- | --- | --- |
| Integrated shopping app | [commerce-app](https://github.com/TheStaffAndroidEngineer/commerce-app) | [`9de51642d4`](https://github.com/TheStaffAndroidEngineer/commerce-app/tree/first-edition-2026.10) |
| 0–5 JVM labs | [kotlin-labs](https://github.com/TheStaffAndroidEngineer/kotlin-labs-code) | [`a914681690`](https://github.com/TheStaffAndroidEngineer/kotlin-labs-code/tree/first-edition-2026.10) |
| 5 | [platform-runtime](https://github.com/TheStaffAndroidEngineer/platform-runtime) | [`8824664c7e`](https://github.com/TheStaffAndroidEngineer/platform-runtime/tree/first-edition-2026.10) |
| 6 | [compose-migration](https://github.com/TheStaffAndroidEngineer/compose-migration) | [`958f26a2e6`](https://github.com/TheStaffAndroidEngineer/compose-migration/tree/first-edition-2026.10) |
| 7 | [state-lifetimes](https://github.com/TheStaffAndroidEngineer/state-lifetimes) | [`d861108d7d`](https://github.com/TheStaffAndroidEngineer/state-lifetimes/tree/first-edition-2026.10) |
| 8 | [adaptive-cart](https://github.com/TheStaffAndroidEngineer/adaptive-cart) | [`b426dc01b7`](https://github.com/TheStaffAndroidEngineer/adaptive-cart/tree/first-edition-2026.10) |
| 9 | [navigation-migration](https://github.com/TheStaffAndroidEngineer/navigation-migration) | [`6af1cfb56f`](https://github.com/TheStaffAndroidEngineer/navigation-migration/tree/first-edition-2026.10) |
| 10 | [ui-verification](https://github.com/TheStaffAndroidEngineer/ui-verification) | [`af987fe0ce`](https://github.com/TheStaffAndroidEngineer/ui-verification/tree/first-edition-2026.10) |
| 11 | [catalog-network](https://github.com/TheStaffAndroidEngineer/catalog-network) | [`3a0a098ce9`](https://github.com/TheStaffAndroidEngineer/catalog-network/tree/first-edition-2026.10) |
| 12 | [persistence-contracts](https://github.com/TheStaffAndroidEngineer/persistence-contracts) | [`c4c8696b9c`](https://github.com/TheStaffAndroidEngineer/persistence-contracts/tree/first-edition-2026.10) |
| 13 | [offline-reconciliation](https://github.com/TheStaffAndroidEngineer/offline-reconciliation) | [`7153030338`](https://github.com/TheStaffAndroidEngineer/offline-reconciliation/tree/first-edition-2026.10) |
| 14 | [durable-work](https://github.com/TheStaffAndroidEngineer/durable-work) | [`5eab30a58a`](https://github.com/TheStaffAndroidEngineer/durable-work/tree/first-edition-2026.10) |
| 15 | [order-recovery](https://github.com/TheStaffAndroidEngineer/order-recovery) | [`2dc81b0176`](https://github.com/TheStaffAndroidEngineer/order-recovery/tree/first-edition-2026.10) |
| 16 | [architecture-boundaries](https://github.com/TheStaffAndroidEngineer/architecture-boundaries) | [`b0b2624d12`](https://github.com/TheStaffAndroidEngineer/architecture-boundaries/tree/first-edition-2026.10) |
| 17 | [dependency-ownership](https://github.com/TheStaffAndroidEngineer/dependency-ownership) | [`79c37a8bb7`](https://github.com/TheStaffAndroidEngineer/dependency-ownership/tree/first-edition-2026.10) |
| 18 | [build-investigation](https://github.com/TheStaffAndroidEngineer/build-investigation) | [`8ac75b6f5f`](https://github.com/TheStaffAndroidEngineer/build-investigation/tree/first-edition-2026.10) |
| 19 | [delivery-contracts](https://github.com/TheStaffAndroidEngineer/delivery-contracts) | [`ae535b4618`](https://github.com/TheStaffAndroidEngineer/delivery-contracts/tree/first-edition-2026.10) |
| 20 | [performance-diagnosis](https://github.com/TheStaffAndroidEngineer/performance-diagnosis) | [`1c05498bf7`](https://github.com/TheStaffAndroidEngineer/performance-diagnosis/tree/first-edition-2026.10) |
| 21 | [rendering-performance](https://github.com/TheStaffAndroidEngineer/rendering-performance) | [`322a588baf`](https://github.com/TheStaffAndroidEngineer/rendering-performance/tree/first-edition-2026.10) |
| 22 | [memory-lifetimes](https://github.com/TheStaffAndroidEngineer/memory-lifetimes) | [`607c79735f`](https://github.com/TheStaffAndroidEngineer/memory-lifetimes/tree/first-edition-2026.10) |
| 23 | [startup-readiness](https://github.com/TheStaffAndroidEngineer/startup-readiness) | [`2c2f1758dc`](https://github.com/TheStaffAndroidEngineer/startup-readiness/tree/first-edition-2026.10) |
| 24 | [resource-costs](https://github.com/TheStaffAndroidEngineer/resource-costs) | [`af653af149`](https://github.com/TheStaffAndroidEngineer/resource-costs/tree/first-edition-2026.10) |
| 25 | [trust-boundaries](https://github.com/TheStaffAndroidEngineer/trust-boundaries) | [`f7ada04007`](https://github.com/TheStaffAndroidEngineer/trust-boundaries/tree/first-edition-2026.10) |
| 26 | [release-recovery](https://github.com/TheStaffAndroidEngineer/release-recovery) | [`c01480be76`](https://github.com/TheStaffAndroidEngineer/release-recovery/tree/first-edition-2026.10) |
| 27 | [design-budgets](https://github.com/TheStaffAndroidEngineer/design-budgets) | [`c789422fbb`](https://github.com/TheStaffAndroidEngineer/design-budgets/tree/first-edition-2026.10) |
| 28 | [field-reconciliation](https://github.com/TheStaffAndroidEngineer/field-reconciliation) | [`b0f32aafc9`](https://github.com/TheStaffAndroidEngineer/field-reconciliation/tree/first-edition-2026.10) |
| 29 | [migration-adoption](https://github.com/TheStaffAndroidEngineer/migration-adoption) | [`d26eca8ca5`](https://github.com/TheStaffAndroidEngineer/migration-adoption/tree/first-edition-2026.10) |
| 33 | [reservation-payments](https://github.com/TheStaffAndroidEngineer/reservation-payments-code) | [`2cdaf42c8a`](https://github.com/TheStaffAndroidEngineer/reservation-payments-code/tree/first-edition-2026.10) |
| 34 | [live-location](https://github.com/TheStaffAndroidEngineer/live-location-code) | [`c3066e8e9a`](https://github.com/TheStaffAndroidEngineer/live-location-code/tree/first-edition-2026.10) |
| 35 | [messaging](https://github.com/TheStaffAndroidEngineer/messaging-code) | [`6b1013ce1b`](https://github.com/TheStaffAndroidEngineer/messaging-code/tree/first-edition-2026.10) |
| 36 | [social-feed](https://github.com/TheStaffAndroidEngineer/social-feed-code) | [`83fc116efe`](https://github.com/TheStaffAndroidEngineer/social-feed-code/tree/first-edition-2026.10) |
| 37 | [media-library](https://github.com/TheStaffAndroidEngineer/media-library-code) | [`7bb6e69a0c`](https://github.com/TheStaffAndroidEngineer/media-library-code/tree/first-edition-2026.10) |
| 38 | [realtime-calls](https://github.com/TheStaffAndroidEngineer/realtime-calls-code) | [`c5511196fa`](https://github.com/TheStaffAndroidEngineer/realtime-calls-code/tree/first-edition-2026.10) |
| 39 | [collaborative-notes](https://github.com/TheStaffAndroidEngineer/collaborative-notes-code) | [`6c56c4bf4d`](https://github.com/TheStaffAndroidEngineer/collaborative-notes-code/tree/first-edition-2026.10) |
| 40 | [resumable-transfer](https://github.com/TheStaffAndroidEngineer/resumable-transfer-code) | [`d3a8b75b3c`](https://github.com/TheStaffAndroidEngineer/resumable-transfer-code/tree/first-edition-2026.10) |
| 41 | [backend-scale](https://github.com/TheStaffAndroidEngineer/backend-scale-code) | [`11ed5a19b8`](https://github.com/TheStaffAndroidEngineer/backend-scale-code/tree/first-edition-2026.10) |
| 42 | [connected-device](https://github.com/TheStaffAndroidEngineer/connected-device-code) | [`c309d2d463`](https://github.com/TheStaffAndroidEngineer/connected-device-code/tree/first-edition-2026.10) |
| 43 | [camera-pipeline](https://github.com/TheStaffAndroidEngineer/camera-pipeline-code) | [`01e84c4165`](https://github.com/TheStaffAndroidEngineer/camera-pipeline-code/tree/first-edition-2026.10) |
| 44 | [ai-assistant](https://github.com/TheStaffAndroidEngineer/ai-assistant-code) | [`2cbba07a62`](https://github.com/TheStaffAndroidEngineer/ai-assistant-code/tree/first-edition-2026.10) |
| 30 | [coding-constraints](https://github.com/TheStaffAndroidEngineer/coding-constraints) | [`640226b359`](https://github.com/TheStaffAndroidEngineer/coding-constraints/tree/first-edition-2026.10) |
| 31 | [interview-conversations](https://github.com/TheStaffAndroidEngineer/interview-conversations) | [`f57141f767`](https://github.com/TheStaffAndroidEngineer/interview-conversations/tree/first-edition-2026.10) |

[Machine-readable repository map](catalog.json). Report reproducibility problems or errata through this repository’s Issues; identify the chapter and edition without posting paid chapter text.
