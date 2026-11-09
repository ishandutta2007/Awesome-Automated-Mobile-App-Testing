# Awesome-Automated-Mobile-App-Testing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **pricing is fragmented across plans**, and the open-source side is one project.



## What the search results actually contain



**SaaS pricing (usable, with caveats):**



| Platform | Entry pricing | Verified detail |

|---|---|---|

| **Sauce Labs** | **Virtual Device Cloud $149/mo annual** ($199 monthly); **Real Device Cloud $199/mo annual** ($249 monthly); Live Testing $39/mo  | Unlimited automated minutes on Virtual; 500 visual snapshots; 1–5 concurrent sessions  |

| **AWS Device Farm** | **$0.17/device-minute** pay-as-you-go; **Unlimited $250/mo per device slot**; first **1,000 minutes free**  | Per-slot pricing covers unlimited tests and remote sessions  |

| **Perfecto** | **From $83/month** (manual testing)  | Automated testing plans not surfaced  |

| **BitBar (SmartBear)** | **€45/parallel/mo annual** (Live Testing); **€202/parallel/mo** (Unlimited)  | Unlimited minutes and users on all plans; **free for open source**  |

| **Firebase Test Lab** | **$5/hour physical device; $1/hour virtual** (Blaze)  | Spark: 30 min/day physical, 60 min/day virtual free  |

| **TestGrid** | **$199/seat/month** (Starter)  | 34+ AI agents included; no per-agent fees  |

| **HeadSpin** | **From $49/month** (CloudTest Lite)  | Higher tiers at $100/mo  |

| **Kobiton** | **$83/month**  | Third-party listing  |



**What is missing:**

- **No pricing** for BrowserStack App Automate specifically. The pricing page returned screenshot and accessibility tier data, not App Automate rates .

- **No pricing** for Digital.ai Continuous Testing.

- **No star counts** for the open-source project surfaced.



## Open-source: what actually exists



**maestro-runner** (devicelab-dev/maestro-runner) is the only open-source project surfaced .



| Feature | Detail |

|---|---|

| **What it is** | Open-source Maestro alternative for mobile UI test automation; "100% free, no features behind a paywall" |

| **Platforms** | Android 5.0+ (API 21+), iOS 15.0+; real iOS devices, simulators, emulators |

| **Cloud integration** | BrowserStack, Sauce Labs, LambdaTest, TestingBot via Appium driver |

| **Drivers** | DeviceLab (default, ~2x faster than UIAutomator2), UIAutomator2, Appium |

| **Execution** | Parallel execution with dynamic work distribution; single binary, no JVM |

| **Reports** | HTML, JUnit XML, Allure-compatible |



**maestro-runner is a test runner, not a device farm.** It executes tests on devices you already have or cloud devices you already pay for. **Do not present it as a replacement for BrowserStack App Automate or AWS Device Farm.**



**No star count was surfaced.** Do not invent one.



## What I recommend



**Split into two honest categories:**



**1. SaaS Device Farms & Cloud Testing** (proprietary):

- **Sauce Labs** — Virtual $149/mo, Real $199/mo, Live $39/mo 

- **AWS Device Farm** — $0.17/device-min, Unlimited $250/slot/mo 

- **Perfecto** — from $83/mo 

- **BitBar** — €45/parallel/mo, free for open source 

- **Firebase Test Lab** — $5/hr physical, $1/hr virtual 

- **TestGrid** — $199/seat/mo 

- **HeadSpin** — from $49/mo 



**2. Open-Source Test Runner**: **maestro-runner** — executes tests across local devices and cloud providers; not a device farm itself .



**Mark BrowserStack App Automate and Digital.ai as "pricing not surfaced"**—the results do not contain their rates.



**Flag the pricing model differences explicitly:** per-concurrent-session (Sauce, BitBar), per-device-minute (AWS, Firebase), per-seat (TestGrid), and per-month-tier (Perfecto, HeadSpin) produce incomparable costs at the same test volume.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate BrowserStack App Automate pricing, invent star counts for maestro-runner, or claim it replaces commercial device farms.
