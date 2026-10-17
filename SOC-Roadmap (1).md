<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=180&section=header&text=SOC%20Analyst%20Roadmap&fontSize=38&fontColor=ffffff&fontAlign=38)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-shaban-421b17300)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmedAshrafShaban)

![Steps](https://img.shields.io/badge/Steps-11-1f6feb?style=flat-square) ![Phases](https://img.shields.io/badge/Phases-3-8957e5?style=flat-square) ![Labs](https://img.shields.io/badge/Hands--on%20Labs-11-success?style=flat-square) ![Lang](https://img.shields.io/badge/Arabic%20%26%20English-orange?style=flat-square)

</div>

> يا هلا 👋 الرود ماب دي مش مجرد لينكات مرصوصة فوق بعض — دي مسار كامل بيوضحلك كل حاجة تقريبًا في مجال الـ SOC Analyst، هنمشي إن شاء الله عليه بشكل مرتب من النقطة 1 إلى النقطة 11 (وممكن يزيدوا، عادي). وحط في بالك إن كل نقطة بتبني على اللي قبلها، فلو وقفت مع حاجة أو مش فاهمها، اوعى تعديها — لازم تكون فهمتها كويس الأول. ختامًا، بالتوفيق ليكم، وأتمنى تكون الـ roadmap سهلة عليكم.

---

## 🧭 The Path — Follow the Steps in Order

```mermaid
flowchart TB
    START(["🏁 START HERE"]) --> P1
    subgraph P1["🌱 PHASE 1 — Foundations"]
        direction LR
        S1["01<br/>Networking"] --> S2["02<br/>SOC Basics"] --> S3["03<br/>Log Analysis"]
    end
    subgraph P2["🛡️ PHASE 2 — Core SOC"]
        direction LR
        S4["04<br/>SIEM"] --> S5["05<br/>Incident<br/>Response"] --> S6["06<br/>MITRE<br/>ATT&CK"] --> S7["07<br/>Threat<br/>Intel"]
    end
    subgraph P3["🔥 PHASE 3 — Specialized"]
        direction LR
        S8["08<br/>Phishing"] --> S9["09<br/>Malware"] --> S10["10<br/>Threat<br/>Hunting"] --> S11["11<br/>EDR / XDR<br/>SOAR"]
    end
    P1 --> P2 --> P3 --> NEXT(["🚀 NEXT STEPS<br/>DFIR · Certs · Projects"])
    style P1 fill:#0d2240,stroke:#1f6feb,color:#fff
    style P2 fill:#241a3d,stroke:#8957e5,color:#fff
    style P3 fill:#3d1a1a,stroke:#da3633,color:#fff
    style START fill:#238636,color:#fff,stroke:#238636
    style NEXT fill:#238636,color:#fff,stroke:#238636
```

| Phase | Level | Steps | الهدف |
|-------|-------|-------|-------|
| 🌱 **Phase 1 — Foundations** | ![Beginner](https://img.shields.io/badge/Level-Beginner-2ea043?style=flat-square) | 01 → 03 | تفهم الشبكات ودور الـ SOC والسجلات |
| 🛡️ **Phase 2 — Core SOC** | ![Intermediate](https://img.shields.io/badge/Level-Intermediate-d29922?style=flat-square) | 04 → 07 | الـ SIEM والاستجابة للحوادث وMITRE والـ Threat Intel |
| 🔥 **Phase 3 — Specialized** | ![Advanced](https://img.shields.io/badge/Level-Advanced-da3633?style=flat-square) | 08 → 11 | Phishing وMalware وThreat Hunting والأدوات الآلية |
| 🚀 **Next Steps** | ![Career](https://img.shields.io/badge/Level-Career-8957e5?style=flat-square) | After 11 | DFIR، شهادات، ومشاريع |

---

## 📋 Table of Contents

| Step | | Topic | Phase | Video |
|:----:|:-:|-------|:-----:|:-----:|
| **01** | 🌐 | Networking Fundamentals | 1 | 🇪🇬 |
| **02** | 🛡️ | SOC Analyst Fundamentals | 1 | 🇬🇧 |
| **03** | 📜 | Windows & Linux Log Analysis | 1 | 🇬🇧 |
| **04** | 📊 | SIEM (Splunk) | 2 | 🇪🇬 |
| **05** | 🚨 | Incident Response | 2 | 🇬🇧 |
| **06** | 🗺️ | MITRE ATT&CK Framework | 2 | 🇬🇧 |
| **07** | 🕵️ | Threat Intelligence | 2 | 🇬🇧 |
| **08** | 🎣 | Phishing Email Analysis | 3 | 🇬🇧 |
| **09** | 🦠 | Malware Analysis | 3 | 🇬🇧 |
| **10** | 🔍 | Threat Hunting | 3 | 🇬🇧 |
| **11** | ⚙️ | EDR / XDR / SOAR | 3 | 🇬🇧 |

> 🇪🇬 = Arabic video &nbsp;·&nbsp; 🇬🇧 = English video &nbsp;·&nbsp; every step ends with a hands-on 🧪 lab

---

## 🌱 Phase 1 — Foundations

![Level](https://img.shields.io/badge/Level-Beginner-2ea043?style=for-the-badge)

<details open>
<summary>🌐 &nbsp;<b>STEP 01 · Networking Fundamentals</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-01%20%2F%2011-1f6feb?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Foundations-1f6feb?style=flat-square) ![Video](https://img.shields.io/badge/Video-Arabic-orange?style=flat-square)

**1. [Networking Fundamentals Playlist — Emad Nashat (23 videos)](https://www.youtube.com/playlist?list=PL8s4OGp0649_e_Wbz5MlBgW5rBW-9hD0c)** 🇪🇬
بلاي ليست عربية كاملة (23 فيديو) بتشرح أساسيات الشبكات من الصفر بجرافيك احترافي وواضح.
🧪 لاب: [TryHackMe | Introductory Networking](https://tryhackme.com/room/introtonetworking)

➡️ **Next:** Step 02 — SOC Analyst Fundamentals

</details>

<details>
<summary>🛡️ &nbsp;<b>STEP 02 · SOC Analyst Fundamentals</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-02%20%2F%2011-1f6feb?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Foundations-1f6feb?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**2. [BEST Beginner SOC Analyst Roadmap](https://www.youtube.com/watch?v=XswhNZ436tM)** 🇬🇧
شرح عام لدور محلل الـSOC وإزاي تبدأ في المجال ده من الصفر من غير خبرة سابقة.
🧪 لاب: [TryHackMe | Principles of Security](https://tryhackme.com/room/principlesofsecurity)

➡️ **Next:** Step 03 — Windows & Linux Log Analysis

</details>

<details>
<summary>📜 &nbsp;<b>STEP 03 · Windows & Linux Log Analysis</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-03%20%2F%2011-1f6feb?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Foundations-1f6feb?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**3. [CVEs in Windows Event Logs? What You Need to Know](https://www.youtube.com/watch?v=ebmW42YYveI)** 🇬🇧
بيشرح إزاي تلاقي آثار ثغرات معروفة (CVEs) جوه سجلات أحداث وندوز وتربط بينهم.
🧪 لاب: [TryHackMe | Investigating Windows](https://tryhackme.com/room/investigatingwindows)

➡️ **Next:** Step 04 — SIEM (Splunk)

</details>


## 🛡️ Phase 2 — Core SOC

![Level](https://img.shields.io/badge/Level-Intermediate-d29922?style=for-the-badge)

<details>
<summary>📊 &nbsp;<b>STEP 04 · SIEM (Splunk)</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-04%20%2F%2011-8957e5?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Core%20SOC-8957e5?style=flat-square) ![Video](https://img.shields.io/badge/Video-Arabic-orange?style=flat-square)

**4. [Splunk SIEM Explained: A Beginner's Guide In Arabic](https://www.youtube.com/watch?v=H8rH-ogb3mE)** 🇪🇬
شرح مبسط لنظام إدارة الأحداث الأمنية الأشهر عالميًا وإزاي بيجمع ويحلل بيانات الشبكة.
🧪 لاب: [TryHackMe | Splunk](https://tryhackme.com/room/bpsplunk)

➡️ **Next:** Step 05 — Incident Response

</details>

<details>
<summary>🚨 &nbsp;<b>STEP 05 · Incident Response</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-05%20%2F%2011-8957e5?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Core%20SOC-8957e5?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**5. [Incident Response Process Explained](https://www.youtube.com/watch?v=76fuTjzuiLg)** 🇬🇧
شرح عام لمراحل التعامل مع أي حادثة أمنية، من أول ما تتكشف لحد ما تتقفل.
🧪 لاب: [TryHackMe | Investigating Windows 2.0](https://tryhackme.com/room/investigatingwindows2)

➡️ **Next:** Step 06 — MITRE ATT&CK Framework

</details>

<details>
<summary>🗺️ &nbsp;<b>STEP 06 · MITRE ATT&CK Framework</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-06%20%2F%2011-8957e5?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Core%20SOC-8957e5?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**6. [MITRE ATT&CK Framework — Official Video](https://www.youtube.com/watch?v=0BEf6s1iu5g)** 🇬🇧
الفيديو الرسمي من MITRE نفسها بيشرح إطار تصنيف أساليب الهجوم الأشهر عالميًا.
🧪 لاب: [TryHackMe | MITRE](https://tryhackme.com/room/mitre)

➡️ **Next:** Step 07 — Threat Intelligence

</details>

<details>
<summary>🕵️ &nbsp;<b>STEP 07 · Threat Intelligence</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-07%20%2F%2011-8957e5?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Core%20SOC-8957e5?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**7. [2026 Threat Intelligence Index: Ransomware, AI, & Emerging TTP Risks](https://www.youtube.com/watch?v=RKeW4Xd9V9E)** 🇬🇧
تقرير حديث بيستعرض أحدث اتجاهات التهديدات، وأثر الذكاء الاصطناعي على أساليب الهجوم.
🧪 لاب: [TryHackMe | Investigating Windows 3.x](https://tryhackme.com/room/investigatingwindows3)

➡️ **Next:** Step 08 — Phishing Email Analysis

</details>


## 🔥 Phase 3 — Specialized

![Level](https://img.shields.io/badge/Level-Advanced-da3633?style=for-the-badge)

<details>
<summary>🎣 &nbsp;<b>STEP 08 · Phishing Email Analysis</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-08%20%2F%2011-da3633?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Specialized-da3633?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**8. [Phishing Email Analysis](https://youtu.be/8--EU8ngqqs)** 🇬🇧
من أكتر المهام تكرارًا لمحلل المستوى الأول: فحص الهيدر، عدم فتح الروابط مباشرة، وفحص المرفقات في بيئة معزولة.
🧪 لاب: [TryHackMe | Phishing: HiddenEye](https://tryhackme.com/room/phishinghiddeneye)

➡️ **Next:** Step 09 — Malware Analysis

</details>

<details>
<summary>🦠 &nbsp;<b>STEP 09 · Malware Analysis</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-09%20%2F%2011-da3633?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Specialized-da3633?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**9. [Malware Analysis — How to Get Started](https://www.youtube.com/watch?v=sBuxwMAfGnI)** 🇬🇧
مقدمة عملية لإزاي تبدأ في تحليل البرمجيات الخبيثة من غير خبرة سابقة.
🧪 لاب: [TryHackMe | Basic Malware RE](https://tryhackme.com/room/basicmalwarere)

➡️ **Next:** Step 10 — Threat Hunting

</details>

<details>
<summary>🔍 &nbsp;<b>STEP 10 · Threat Hunting</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-10%20%2F%2011-da3633?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Specialized-da3633?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**10. [Threat Hunting](https://youtu.be/VNp35Uw_bSM)** 🇬🇧
شرح عام لفكرة البحث الاستباقي عن التهديدات المخفية جوه الشبكة قبل ما تتسبب في ضرر.
🧪 لاب: [TryHackMe | Carnage](https://tryhackme.com/room/c2carnage)

➡️ **Next:** Step 11 — EDR / XDR / SOAR

</details>

<details>
<summary>⚙️ &nbsp;<b>STEP 11 · EDR / XDR / SOAR</b></summary>
<br>

![Step](https://img.shields.io/badge/STEP-11%20%2F%2011-da3633?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-Specialized-da3633?style=flat-square) ![Video](https://img.shields.io/badge/Video-English-blue?style=flat-square)

**11. [EDR vs XDR vs SOAR Explained](https://youtu.be/TAaRA4ctRL4)** 🇬🇧
أدوات بتراقب الأجهزة وتوقف العمليات الخبيثة فورًا، وتعمل أتمتة لخطوات الاستجابة المتكررة.
🧪 لاب: [TryHackMe | Blue](https://tryhackme.com/room/blue)

🏁 **Done with the 11 steps** — continue to [Next Steps](#-next-steps--after-the-11)

</details>

---

## 🚀 Next Steps — After the 11

### ✅ Job-Ready Checklist
- [ ] فاهم الشبكات كويس وتقدر تقرا Packet أو Log من غير ما تتلخبط
- [ ] اشتغلت على SIEM واحد على الأقل (Splunk مثلًا) وعملت Query بنفسك
- [ ] تقدر تشرح مراحل الـ Incident Response وتربط أي حادثة بـ MITRE ATT&CK
- [ ] حليت لاب لكل نقطة من الـ 11 (مش مجرد فرجة على الفيديو)
- [ ] كتبت Report بسيط لحادثة واحدة على الأقل من اللابات

### 🧬 DFIR Path
الـ DFIR مش نقطة بداية من الصفر — الأغلب بيوصله بعد ما يشتغل SOC Analyst، لإن شغل Tier 1 وTier 2 بيبني خبرة الـ Triage وتحليل السجلات والاستجابة للحوادث اللي الـ DFIR بيعتمد عليها.

| Resource | Type | إيه اللي هتاخده منه |
|----------|------|---------------------|
| [SANS DFIR Course Roadmap & Job Role Matrix](https://www.sans.org/blog/sans-dfir-course-roadmap-and-job-role-matrix/) | 🗺️ Roadmap | ترتيب كورسات DFIR وإيه الكورس المناسب لكل وظيفة |
| [TryHackMe — How to Get Started in DFIR](https://tryhackme.com/resources/blog/how-to-get-started-in-dfir-free-training-tools-and-career-path-in-2026) | 📝 Article | الأدوات والمهارات ومسار الوظيفة |
| [Cybrary — DFIR Operator Series: Overview](https://www.cybrary.it/course/dfir-overview) | 🎓 Course | يعني إيه DFIR، الأدلة الرقمية، وتطور دور المحلل (الوصول الكامل بيحتاج اشتراك) |

### 🎓 Certifications

| Level | Certification | ملاحظة |
|-------|---------------|--------|
| ![Entry](https://img.shields.io/badge/-Entry-2ea043?style=flat-square) | CompTIA Security+ | أساسيات عامة، وكورس Professor Messer بيغطيها |
| ![Entry](https://img.shields.io/badge/-Entry-2ea043?style=flat-square) | TryHackMe SAL1 (Security Analyst Level 1) | مبنية على مسار SOC Level 1 |
| ![Mid](https://img.shields.io/badge/-Mid-d29922?style=flat-square) | TryHackMe SAL2 (Security Analyst Level 2) | تحقيق متقدم وDFIR بسيناريوهات عملية |
| ![Mid](https://img.shields.io/badge/-Mid-d29922?style=flat-square) | EC-Council CND | تدعيم لمسار الـ Network Defense |
| ![Adv](https://img.shields.io/badge/-Advanced-da3633?style=flat-square) | EC-Council CHFI + ECIH | الشهادتين دول هما الـ Capstone لمسار DFIR عند EC-Council |
| ![Adv](https://img.shields.io/badge/-Advanced-da3633?style=flat-square) | GIAC (مرتبطة بكورسات SANS) | معروفة جدًا عند أصحاب الشغل |

---

## 📚 Resources

### 🎬 Courses & Paths

| Resource | Type | Details |
|----------|------|---------|
| [Professor Messer — Security+](https://www.professormesser.com/) | 🎥 Videos | أساسيات الأمن، مناسب للـ Phase 1 |
| [CyberTalents — SOC Analyst L1 Career Path](https://cybertalents.com/courses/cybertalents-soc-analyst-l1-career-path) | 🎓 Full path | 48 درس و55 لاب وحوالي 26 ساعة، بيبدأ بأساسيات الأمن وبعدين وحدة SOC Analyst |
| [Cybrary — SOC Analyst Path](https://www.cybrary.it/) | 🎓 Platform | كورسات ولابات مجمعة (بعضها بيحتاج اشتراك) |
| [MyDFIR — SOC Analyst Roadmap (video)](https://youtu.be/OXzDbxphBuA) 🇬🇧 | 🎥 Video | شرح رود ماب SOC من قناة MyDFIR، وليه نسخة PDF مدفوعة على [Gumroad](https://mydfir.gumroad.com/l/SOC-Analyst-Roadmap) |

### 📖 Books

| Book | Author |
|------|--------|
| Blue Team Handbook: SOC, SIEM | Don Murdoch |
| The Practice of Network Security Monitoring | Richard Bejtlich |
| Incident Response & Computer Forensics | Jason T. Luttgens & Matthew Pepe |
| Applied Incident Response | Steve Antony |

### 🧪 Labs & Practice Platforms

| Platform | بتتميز بإيه |
|----------|-------------|
| [TryHackMe — SOC Level 1](https://tryhackme.com/path/outline/soclevel1) | مسار منظم من الصفر |
| [CyberDefenders](https://cyberdefenders.org/) | تحديات Blue Team حقيقية بأسلوب CTF |
| [BlueTeamLabs (BTLO)](https://blueteamlabs.online/) | تمارين تحليل وDFIR عملية |
| [LetsDefend](https://letsdefend.io/) | محاكاة بيئة SOC حقيقية بالتنبيهات |

---

<div align="center">

⭐ لو الرود ماب فادتك، سيب نجمة على الريبو

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=90&section=footer)

</div>
