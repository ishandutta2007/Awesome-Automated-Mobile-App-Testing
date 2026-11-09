# Awesome Automated Mobile App Testing

A curated list of automated mobile app testing platforms, device clouds, test runners, and frameworks for Android and iOS.

---

## Sector Overview & Market Dynamics

The global mobile application testing market is valued between **$8.6 Billion and $14.8 Billion** (projected to reach over $17 Billion with a CAGR of ~13%–17%), driven by explosive mobile device fragmentation, 5G adoption, and continuous delivery pipelines. The sector exhibits a **hybrid, moderately concentrated structure**: while the bottom and mid-tier developer segments remain highly fragmented across thousands of regional QA consultancies and open-source test frameworks (such as Appium and Maestro), the top-tier enterprise cloud device farm and automated quality infrastructure space is moderately concentrated among hyperscalers (AWS, Google) and specialized quality engineering platforms (BrowserStack, Perforce/Perfecto, SmartBear/BitBar, and Sauce Labs).

---

## SaaS Mobile Testing Platforms & Device Clouds

The table below lists leading commercial mobile testing clouds and automated device labs. Sorted in descending order by parent company scale (valuation / annual revenue).

| Platform | Company Scale (Valuation / Revenue) | Entry Pricing | Free Tier / Free Trial Limits | Description & Key Capabilities |
|---|---|---|---|---|
| **[AWS Device Farm](https://aws.amazon.com/device-farm/)** | **~$2 Trillion+ Market Cap** (~$100B+ ARR AWS run rate) | **$0.17 / device-minute** (Pay-as-you-go); Unmetered from **$250 / slot / month** | **1,000 device-minutes** (One-time free trial on sign-up) | Real-device cloud for running automated Android and iOS test suites (Appium, Espresso, XCUITest) and remote debugging. |
| **[Firebase Test Lab](https://firebase.google.com/docs/test-lab)** (Google) | **~$2 Trillion+ Market Cap** (~$300B+ annual revenue) | **$1.00 / hour** (Virtual); **$5.00 / hour** (Physical) on Blaze plan | **Spark Plan (Free forever)**: 10 virtual tests/day (max 60 min/day) & 5 physical tests/day (max 30 min/day) | Cloud-based app-testing infrastructure integrated directly with Google Cloud and Firebase; automated Robo test support. |
| **[Perfecto](https://www.perfecto.io/)** (Perforce Software) | **~$500M–$750M ARR** (Enterprise Valuation ~$2B+) | From **$83 / month** (Manual); Automation plans start at **$300 / month** | **14-day free trial** (Includes ~240 minutes of testing on public cloud real devices) | Enterprise-grade cloud for continuous web and mobile automation with enterprise biometric, network, and audio virtualization. |
| **[BrowserStack App Automate](https://www.browserstack.com/app-automate)** | **$4 Billion Valuation** (~$230M ARR) | **$199 / month** (Billed annually; $249 / month billed monthly) per parallel test | **100 minutes** of automated mobile app testing + 30 min interactive live testing (No fixed day limit) | Scalable real-device mobile cloud supporting Appium, Espresso, XCUITest, Flutter, and EarlGrey with fast local testing tunnels. |
| **[BitBar](https://smartbear.com/product/bitbar/)** (SmartBear) | **~$1.8B–$1.9B Valuation** (~$150M+ ARR) | **€45 / parallel / month** annual (Live); **€202 / parallel / month** (Unlimited automated) | **14-day free trial** (Full functional trial on real devices; free tier available for approved open-source projects) | Flexible mobile app and web testing cloud supporting any native mobile test framework without vendor lock-in. |
| **[Sauce Labs](https://saucelabs.com/)** | **~$613 Million Valuation** (~$50M–$100M ARR) | **$149 / month** annual ($199/mo monthly) for Virtual; **$199 / month** annual for Real Devices | **28-day free trial** (Includes 60 automated/live testing minutes across 3 parallel virtual machines) | Real-device cloud and emulators/simulators with integrated error reporting, automated test analytics, and Sauce Connect VPN. |
| **[LambdaTest](https://www.lambdatest.com/)** | **~$400 Million Valuation** (~$80M–$120M ARR) | **$15 / month** (Live manual); Automation starting from **$79 / month** | **Free Forever plan**: 60 minutes/month automated web/mobile testing + 6 live sessions of 10 min each | Unified testing cloud supporting automated mobile testing across physical devices and emulators with real-time debugging. |
| **[HeadSpin](https://www.headspin.io/)** | **~$50M–$100M Valuation** (~$15M–$20M ARR) | **$49 / month** (CloudTest Lite, 40 hrs manual); **$83 / month** (CloudTest Go) | **14-day free trial** upon approved sales demo request (No self-serve open-ended free tier) | AI-driven global device infrastructure providing real-world performance metrics, audio/video QoE, and network emulation. |
| **[Kobiton](https://kobiton.com/)** | **~$40M+ Funding Raised** (Series B stage) | **$83 / month** (Startup plan, includes 500 device-minutes/month) | **15-day free trial** (Includes 120–300 minutes of real device access without commitment) | Mobile testing platform offering real device access, scriptless test automation generation, and on-premises private cloud deployment. |
| **[TestGrid](https://testgrid.io/)** | **~$5M+ ARR** (Early/Growth stage funding) | **$199 / seat / month** (Starter CoTester plan) | **Guided free trial / PoC** via sales request (Custom days/limits configured per evaluation) | End-to-end AI-powered testing platform providing codeless mobile automation, real-device cloud access, and IoT device testing. |

---

## Open-Source Mobile Test Runners & Frameworks

Open-source automation runners execute tests on local devices, emulators, or connected cloud device farms:

| Project | Description | Target Platforms | Cloud Support |
|---|---|---|---|
| **[maestro-runner](https://github.com/devicelab-dev/maestro-runner)** | Open-source, lightweight CLI test runner alternative for Maestro mobile UI test workflows; 100% free with no JVM overhead. | Android 5.0+ (API 21+), iOS 15.0+ | BrowserStack, Sauce Labs, LambdaTest, TestingBot |
| **[Appium](https://github.com/appium/appium)** | Cross-platform test automation framework for native, hybrid, and mobile web apps utilizing the W3C WebDriver protocol. | Android, iOS, Windows, macOS | All major cloud device farms |
| **[Maestro](https://github.com/mobile-dev-inc/maestro)** | Simple and flexible UI automation framework for mobile apps using clean declarative YAML syntax. | Android, iOS, React Native, Flutter | Local devices & cloud farms |
| **[Detox](https://github.com/wix/Detox)** | Gray-box end-to-end testing and automation framework designed for React Native mobile apps. | Android, iOS | Local emulators/simulators & cloud |
