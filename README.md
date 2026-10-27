# Life OS Architect

**An AI skill that interviews you and builds a deeply personal Life OS in Notion.**

Not a template. A short, adaptive interview, a portrait of how your life actually moves, and a Notion system where every page exists *because of something you said*.

[English](#english) · [العربية](#العربية)

---

## English

### What it does

1. **Interviews you** with short multiple-choice questions that adapt to your answers. A doctor gets asked about on-calls and recovery days; a student about exams; a freelancer about clients and lumpy income. You never answer an irrelevant question.
2. **Reads your life back to you** in a *Life Portrait*: your archetype (e.g. *Shift Worker × Creator × Lifelong Learner*), your real weekly rhythm, the tensions in your goals, and why past systems failed you.
3. **Shows a Blueprint** before building anything. Every database, view and rule comes with a *"because you said…"*. Anything without a reason is cut.
4. **Builds it in your Notion**, step by step, tests every view with temporary records, deletes them, and never touches anything you already have.
5. **Hands you what you keep**: a short letter explaining why your system looks the way it does, a personal guide in your own words, a first-7-days plan, and one rule to remember.

### What makes it different

- **Day Types** for irregular lives (On-Call, Post-Call, Exam Day, Client Day…) with a capacity-aware *Today* view.
- **Minimum Day**: on hard days the bare minimum counts as a win. Deadlines never move on their own.
- **Season Mode** for exams, Ramadan, a newborn, a launch.
- **Three depths**: Minimal, Balanced, Full. It recommends the one that matches the time you will honestly give.
- **Your language and dialect**, including Arabic dialects, English, and more.
- **No invented data.** It never fills your system with fake goals, tasks or numbers.
- **Checkup mode**: come back after a month and it proposes cuts before additions.
- **No Notion connected?** You get an exact manual build guide plus empty CSV files (headers only) to import.
- **Safe to re-run**: a build log lets it resume after an interruption without creating duplicates.

### Install

**Claude (claude.ai or the desktop app)**
1. Download this repo as ZIP (green **Code** button → **Download ZIP**), unzip it, then zip only the `skills/life-os-architect` folder.
2. Go to **Customize → Skills** and upload that ZIP. (On some versions it is under **Settings → Capabilities → Skills**.)
3. Connect the **Notion** connector in Settings so the skill can build for you.

**Claude Code**
```bash
git clone https://github.com/dr-haider-asaad/life-os-architect
cp -r life-os-architect/skills/life-os-architect ~/.claude/skills/
```

### Use

Start a new chat and say something like:

> Build me a Life OS that fits my life.

or in Arabic:

> ابنيلي Life OS يناسب حياتي.

The deep interview takes about 10 minutes. A quick version (about 4 minutes) is offered at the start; it still asks the two questions that matter most: how much time you can give daily, and why past systems failed you.

### Origin

Built by **Dr. Haider Asaad**, a physician and content creator, from the process of designing his own Life OS around hospital shifts, on-calls and recovery days.

---

## العربية

<div dir="rtl">

### شنو تسوي؟

1. **تقابلك بأسئلة قصيرة بخيارات**، وكل سؤال يتغيّر حسب جوابك. الطبيب ينسأل عن الخفارات وأيام الراحة، والطالب عن الامتحانات، والفريلانسر عن العملاء والدخل المتذبذب.
2. **ترسملك صورة حياتك**: نمطك (مثلاً *Shift Worker × Creator*)، وإيقاع أسبوعك الحقيقي، والتناقضات اللي بأهدافك، وليش الأنظمة السابقة فشلت وياك.
3. **تعرض عليك مخطط قبل البناء**. كل جزء بالنظام وياه سبب: "لأنك كلت…". واللي ما إله سبب ينشال.
4. **تبني النظام بـNotion مالتك** خطوة خطوة، وتختبر كل شي وتمسح بيانات الاختبار، وما تلمس أي شي موجود عندك.
5. **تسلّمك**: رسالة قصيرة تشرح ليش نظامك بهالشكل، ودليل بكلماتك، وخطة أول 7 أيام، وقاعدة وحدة تتذكرها.

### ليش مختلفة؟

- **أنواع أيام** للحياة غير المنتظمة: خفارة، بعد الخفارة، يوم امتحان، يوم عملاء…
- **Minimum Day**: بالأيام الصعبة، أقل شي يُحسب إنجاز، والمواعيد ما تتحرك لوحدها.
- **Season Mode** لرمضان والامتحانات والمولود الجديد.
- **ثلاث مستويات**: بسيط، متوازن، كامل.
- **تحجي بلغتك ولهجتك.**
- **ما تخترع بيانات** أبداً.
- **وضع المراجعة**: ترجعلها بعد شهر وتخفف النظام قبل ما تضيف.
- **ما عندك Notion متصل؟** تطلعلك دليل بناء يدوي دقيق مع ملفات CSV فارغة (بس العناوين) تستوردها.
- **آمنة إذا انعادت**: تكمل من وين وقفت بدون ما تكرر شي.

### التنصيب

نفس خطوات القسم الإنكليزي فوق: ارفع مجلد `skills/life-os-architect` كملف ZIP من **Customize → Skills** (وبعض النسخ من **Settings → Capabilities → Skills**)، واربط Notion.

### الاستخدام

افتح محادثة جديدة واكتب:

> ابنيلي Life OS يناسب حياتي.

</div>

---

### Changelog

- **v1.1**: Quick interview now always asks about daily time and past failures; exact build recipe for the Light/Normal *Today* view; base schema; build log for safe re-runs; CSV files always provided without Notion; tool limits stated per connector; shorter description; updated install path.
- **v1.0**: First release.

MIT License · © 2026 Dr. Haider Asaad
