<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=180&section=header&text=SOC%20Analyst%20Roadmap&fontSize=38&fontColor=ffffff&fontAlign=38)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-shaban-421b17300)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmedAshrafShaban)

![Steps](https://img.shields.io/badge/Steps-11-1f6feb?style=flat-square) ![Phases](https://img.shields.io/badge/Phases-3-8957e5?style=flat-square) ![Labs](https://img.shields.io/badge/Hands--on%20Labs-11-success?style=flat-square) ![Lang](https://img.shields.io/badge/Arabic%20%26%20English-orange?style=flat-square)

</div>

> يا هلا 👋 الرود ماب دي مش مجرد لينكات مرصوصة فوق بعض — دي مسار كامل بيوضحلك كل حاجة تقريبًا في مجال الـ SOC Analyst، هنمشي إن شاء الله عليه بشكل مرتب من النقطة 1 إلى النقطة 11 (وممكن يزيدوا، عادي). وحط في بالك إن كل نقطة بتبني على اللي قبلها، فلو وقفت مع حاجة أو مش فاهمها، اوعى تعديها — لازم تكون فهمتها كويس الأول. ختامًا، بالتوفيق ليكم، وأتمنى تكون الـ roadmap سهلة عليكم.

---

## 🧭 The Path

```mermaid
flowchart LR
    A["🌱 Phase 1<br/>Foundations<br/>(1 → 3)"] --> B["🛡️ Phase 2<br/>Core SOC<br/>(4 → 7)"]
    B --> C["🔥 Phase 3<br/>Specialized<br/>(8 → 11)"]
    C --> D["🚀 Next Steps<br/>DFIR + Certs + Projects"]
    style A fill:#1f6feb,color:#fff,stroke:#1f6feb
    style B fill:#8957e5,color:#fff,stroke:#8957e5
    style C fill:#da3633,color:#fff,stroke:#da3633
    style D fill:#238636,color:#fff,stroke:#238636
```

| Phase | Level | Steps | الهدف |
|-------|-------|-------|-------|
| 🌱 **Phase 1 — Foundations** | ![Beginner](https://img.shields.io/badge/Level-Beginner-2ea043?style=flat-square) | 1 → 3 | تفهم الشبكات ودور الـ SOC والسجلات |
| 🛡️ **Phase 2 — Core SOC** | ![Intermediate](https://img.shields.io/badge/Level-Intermediate-d29922?style=flat-square) | 4 → 7 | الـ SIEM والاستجابة للحوادث وMITRE والـ Threat Intel |
| 🔥 **Phase 3 — Specialized** | ![Advanced](https://img.shields.io/badge/Level-Advanced-da3633?style=flat-square) | 8 → 11 | Phishing وMalware وThreat Hunting والأدوات الآلية |
| 🚀 **Next Steps** | ![Pro](https://img.shields.io/badge/Level-Career-8957e5?style=flat-square) | بعد 11 | DFIR، شهادات، ومشاريع |

---

## 📋 Table of Contents

| # | 🔖 | Section |
|---|---|---------|
| 1 | 🌐 | أساسيات الشبكات |
| 2 | 🛡️ | أساسيات دور محلل SOC |
| 3 | 📜 | تحليل سجلات الأنظمة (Windows/Linux) |
| 4 | 📊 | إدارة الأحداث الأمنية (SIEM/Splunk) |
| 5 | 🚨 | الاستجابة للحوادث الأمنية |
| 6 | 🗺️ | إطار MITRE ATT&CK |
| 7 | 🕵️ | استخبارات التهديدات |
| 8 | 🎣 | تحليل رسائل التصيد الاحتيالي |
| 9 | 🦠 | تحليل البرمجيات الخبيثة |
| 10 | 🔍 | البحث الاستباقي عن التهديدات |
| 11 | ⚙️ | أدوات الحماية والاستجابة الآلية (EDR/XDR/SOAR) |

---

## 🌱 Phase 1 — Foundations

<details open>
<summary>🌐 &nbsp;<b>1. أساسيات الشبكات</b></summary>
<br>

**1. [قائمة تشغيل: أساسيات الشبكات — عماد نشأت](https://www.youtube.com/playlist?list=PL8s4OGp0649_e_Wbz5MlBgW5rBW-9hD0c)** 🇪🇬
بلاي ليست عربية كاملة (23 فيديو) بتشرح أساسيات الشبكات من الصفر بجرافيك احترافي وواضح.
🧪 لاب: [TryHackMe | Introductory Networking](https://tryhackme.com/room/introtonetworking)

</details>

<details>
<summary>🛡️ &nbsp;<b>2. أساسيات دور محلل SOC</b></summary>
<br>

**2. [BEST Beginner SOC Analyst Roadmap](https://www.youtube.com/watch?v=XswhNZ436tM)** 🇬🇧
شرح عام لدور محلل الـSOC وإزاي تبدأ في المجال ده من الصفر من غير خبرة سابقة.
🧪 لاب: [TryHackMe | Principles of Security](https://tryhackme.com/room/principlesofsecurity)

</details>

<details>
<summary>📜 &nbsp;<b>3. تحليل سجلات الأنظمة (Windows/Linux)</b></summary>
<br>

**3. [CVEs in Windows Event Logs? What You Need to Know](https://www.youtube.com/watch?v=ebmW42YYveI)** 🇬🇧
بيشرح إزاي تلاقي آثار ثغرات معروفة (CVEs) جوه سجلات أحداث وندوز وتربط بينهم.
🧪 لاب: [TryHackMe | Investigating Windows](https://tryhackme.com/room/investigatingwindows)

</details>

---

## 🛡️ Phase 2 — Core SOC

<details>
<summary>📊 &nbsp;<b>4. إدارة الأحداث الأمنية (SIEM/Splunk)</b></summary>
<br>

**4. [شرح Splunk SIEM للمبتدئين بالعربي](https://www.youtube.com/watch?v=H8rH-ogb3mE)** 🇪🇬
شرح مبسط لنظام إدارة الأحداث الأمنية الأشهر عالميًا وإزاي بيجمع ويحلل بيانات الشبكة.
🧪 لاب: [TryHackMe | Splunk](https://tryhackme.com/room/bpsplunk)

</details>

<details>
<summary>🚨 &nbsp;<b>5. الاستجابة للحوادث الأمنية</b></summary>
<br>

**5. [Incident Response Process Explained](https://www.youtube.com/watch?v=76fuTjzuiLg)** 🇬🇧
شرح عام لمراحل التعامل مع أي حادثة أمنية، من أول ما تتكشف لحد ما تتقفل.
🧪 لاب: [TryHackMe | Investigating Windows 2.0](https://tryhackme.com/room/investigatingwindows2)

</details>

<details>
<summary>🗺️ &nbsp;<b>6. إطار MITRE ATT&CK</b></summary>
<br>

**6. [MITRE ATT&CK Framework — الفيديو الرسمي](https://www.youtube.com/watch?v=0BEf6s1iu5g)** 🇬🇧
الفيديو الرسمي من MITRE نفسها بيشرح إطار تصنيف أساليب الهجوم الأشهر عالميًا.
🧪 لاب: [TryHackMe | MITRE](https://tryhackme.com/room/mitre)

</details>

<details>
<summary>🕵️ &nbsp;<b>7. استخبارات التهديدات</b></summary>
<br>

**7. [2026 Threat Intelligence Index: Ransomware, AI, & Emerging TTP Risks](https://www.youtube.com/watch?v=RKeW4Xd9V9E)** 🇬🇧
تقرير حديث بيستعرض أحدث اتجاهات التهديدات، وأثر الذكاء الاصطناعي على أساليب الهجوم.
🧪 لاب: [TryHackMe | Investigating Windows 3.x](https://tryhackme.com/room/investigatingwindows3)

</details>

---

## 🔥 Phase 3 — Specialized

<details>
<summary>🎣 &nbsp;<b>8. تحليل رسائل التصيد الاحتيالي</b></summary>
<br>

**8. [Phishing Email Analysis](https://youtu.be/8--EU8ngqqs)** 🇬🇧
من أكتر المهام تكرارًا لمحلل المستوى الأول: فحص الهيدر، عدم فتح الروابط مباشرة، وفحص المرفقات في بيئة معزولة.
🧪 لاب: [TryHackMe | Phishing: HiddenEye](https://tryhackme.com/room/phishinghiddeneye)

</details>

<details>
<summary>🦠 &nbsp;<b>9. تحليل البرمجيات الخبيثة</b></summary>
<br>

**9. [Malware Analysis — How to Get Started](https://www.youtube.com/watch?v=sBuxwMAfGnI)** 🇬🇧
مقدمة عملية لإزاي تبدأ في تحليل البرمجيات الخبيثة من غير خبرة سابقة.
🧪 لاب: [TryHackMe | Basic Malware RE](https://tryhackme.com/room/basicmalwarere)

</details>

<details>
<summary>🔍 &nbsp;<b>10. البحث الاستباقي عن التهديدات</b></summary>
<br>

**10. [Threat Hunting](https://youtu.be/VNp35Uw_bSM)** 🇬🇧
شرح عام لفكرة البحث الاستباقي عن التهديدات المخفية جوه الشبكة قبل ما تتسبب في ضرر.
🧪 لاب: [TryHackMe | Carnage](https://tryhackme.com/room/c2carnage)

</details>

<details>
<summary>⚙️ &nbsp;<b>11. أدوات الحماية والاستجابة الآلية (EDR/XDR/SOAR)</b></summary>
<br>

**11. [EDR vs XDR vs SOAR Explained](https://youtu.be/TAaRA4ctRL4)** 🇬🇧
أدوات بتراقب الأجهزة وتوقف العمليات الخبيثة فورًا، وتعمل أتمتة لخطوات الاستجابة المتكررة.
🧪 لاب: [TryHackMe | Blue](https://tryhackme.com/room/blue)

</details>

---

## 🚀 Next Steps — بعد ما تخلص الـ 11

### ✅ Checklist قبل ما تقدم على أي وظيفة
- [ ] فاهم الشبكات كويس وتقدر تقرا Packet أو Log من غير ما تتلخبط
- [ ] اشتغلت على SIEM واحد على الأقل (Splunk مثلًا) وعملت Query بنفسك
- [ ] تقدر تشرح مراحل الـ Incident Response وتربط أي حادثة بـ MITRE ATT&CK
- [ ] حليت لاب لكل نقطة من الـ 11 (مش مجرد فرجة على الفيديو)
- [ ] كتبت Report بسيط لحادثة واحدة على الأقل من اللابات

### 🧬 مسار DFIR (التحقيق الجنائي الرقمي)
الـ DFIR مش نقطة بداية من الصفر — الأغلب بيوصله بعد ما يشتغل SOC Analyst، لإن شغل Tier 1 وTier 2 بيبني خبرة الـ Triage وتحليل السجلات والاستجابة للحوادث اللي الـ DFIR بيعتمد عليها.

| المصدر | النوع | إيه اللي هتاخده منه |
|--------|-------|---------------------|
| [SANS DFIR Course Roadmap & Job Role Matrix](https://www.sans.org/blog/sans-dfir-course-roadmap-and-job-role-matrix/) | 🗺️ خريطة رسمية | ترتيب كورسات DFIR وإيه الكورس المناسب لكل وظيفة |
| [TryHackMe — How to Get Started in DFIR](https://tryhackme.com/resources/blog/how-to-get-started-in-dfir-free-training-tools-and-career-path-in-2026) | 📝 مقال | الأدوات والمهارات ومسار الوظيفة |
| [Cybrary — DFIR Operator Series: Overview](https://www.cybrary.it/course/dfir-overview) | 🎓 كورس | يعني إيه DFIR، الأدلة الرقمية، وتطور دور المحلل (الوصول الكامل بيحتاج اشتراك) |

### 🎓 الشهادات المقترحة

| المستوى | الشهادة | ملاحظة |
|---------|---------|--------|
| ![Entry](https://img.shields.io/badge/-Entry-2ea043?style=flat-square) | CompTIA Security+ | أساسيات عامة، وكورس Professor Messer بيغطيها |
| ![Entry](https://img.shields.io/badge/-Entry-2ea043?style=flat-square) | TryHackMe SAL1 (Security Analyst Level 1) | مبنية على مسار SOC Level 1 |
| ![Mid](https://img.shields.io/badge/-Mid-d29922?style=flat-square) | TryHackMe SAL2 (Security Analyst Level 2) | تحقيق متقدم وDFIR بسيناريوهات عملية |
| ![Mid](https://img.shields.io/badge/-Mid-d29922?style=flat-square) | EC-Council CND | تدعيم لمسار الـ Network Defense |
| ![Adv](https://img.shields.io/badge/-Advanced-da3633?style=flat-square) | EC-Council CHFI + ECIH | الشهادتين دول هما الـ Capstone لمسار DFIR عند EC-Council |
| ![Adv](https://img.shields.io/badge/-Advanced-da3633?style=flat-square) | GIAC (مرتبطة بكورسات SANS) | معروفة جدًا عند أصحاب الشغل |

---

## 📚 Resources

### 🎬 كورسات ومسارات شاملة

| المصدر | النوع | التفاصيل |
|--------|-------|----------|
| [Professor Messer — Security+](https://www.professormesser.com/) | 🎥 فيديوهات | أساسيات الأمن، مناسب للـ Phase 1 |
| [CyberTalents — SOC Analyst L1 Career Path](https://cybertalents.com/courses/cybertalents-soc-analyst-l1-career-path) | 🎓 مسار كامل | 48 درس و55 لاب وحوالي 26 ساعة، بيبدأ بأساسيات الأمن وبعدين وحدة SOC Analyst |
| [Cybrary — SOC Analyst Path](https://www.cybrary.it/) | 🎓 منصة | كورسات ولابات مجمعة (بعضها بيحتاج اشتراك) |
| [MyDFIR — SOC Analyst Roadmap (فيديو)](https://youtu.be/OXzDbxphBuA) 🇬🇧 | 🎥 فيديو | شرح رود ماب SOC من قناة MyDFIR، وليه نسخة PDF مدفوعة على [Gumroad](https://mydfir.gumroad.com/l/SOC-Analyst-Roadmap) |

### 📖 كتب

| الكتاب | المؤلف |
|--------|--------|
| Blue Team Handbook: SOC, SIEM | Don Murdoch |
| The Practice of Network Security Monitoring | Richard Bejtlich |
| Incident Response & Computer Forensics | Jason T. Luttgens & Matthew Pepe |
| Applied Incident Response | Steve Antony |

### 🧪 لابات ومنصات تمرين

| المنصة | بتتميز بإيه |
|--------|-------------|
| [TryHackMe — SOC Level 1](https://tryhackme.com/path/outline/soclevel1) | مسار منظم من الصفر |
| [CyberDefenders](https://cyberdefenders.org/) | تحديات Blue Team حقيقية بأسلوب CTF |
| [BlueTeamLabs (BTLO)](https://blueteamlabs.online/) | تمارين تحليل وDFIR عملية |
| [LetsDefend](https://letsdefend.io/) | محاكاة بيئة SOC حقيقية بالتنبيهات |

---

<div align="center">

⭐ لو الرود ماب فادتك، سيب نجمة على الريبو

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=90&section=footer)

</div>
