# ✍️ علّم Claude طريقة كتابتك — عشان محدش يعرف إن البوست ده AI

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20PROMPT-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Prompt على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20NICHE%20%C2%B7%20TEXT-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Prompt على طول — املا الخانات والصقه في Claude.</b></p>

الناس بقت بتعرف البوست المكتوب بالـ AI من أول سطر: نفس الـ Structure، نفس الجمل، نفس الـ Emojis.
الحل إنك تدّي Claude كتاباتك انت، يطلّع منها **"بصمة"** أسلوبك، وتحفظها مرة واحدة في Styles أو في الـ Project Instructions — ومن ساعتها كل حاجة يكتبها هتطلع بصوتك انت.

هنا هتلاقي **الـ Prompts اللي بستخدمها بالظبط**، وكل واحد معاه شرح بيعمل إيه وامتى تستخدمه.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: جهّز الـ Samples بتاعتك

1. اختار **٣ أو ٤ حاجات انت كاتبها بإيدك** — Emails، Scripts، بوستات، Captions. الأحسن تكون متنوعة ومكتوبة قبل ما تستخدم الـ AI.
2. حطهم في ملف واحد أو الصقهم ورا بعض، وافصل بين كل واحد والتاني بـ `---`.
3. افتح Claude وابدأ Chat جديد (أو جوا Project لو هتحفظ الـ Style في الـ Instructions).

📚 شرح الـ Styles الرسمي من Claude: https://support.claude.com/en/articles/10181068

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

كل الـ Prompts اللي تحت بتستخدم نفس الخانات دي — املاها مرة وانسخها في أي Prompt.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك أو اسم البراند | Steven Ayman |
| `[CONTENT TYPE]` | انت بتعمل إيه / مجالك | AI Automation agency, reels عن Claude و n8n |
| `[AUDIENCE]` | بتكلم مين | أصحاب البيزنس الصغير في مصر |
| `[LANGUAGE]` | لغة الكتابة | Egyptian Arabic with English tech words |
| `[PLATFORM]` | الكلام ده هيتنشر فين | Instagram reels script / LinkedIn post / Email |
| `[YOUR SAMPLES]` | الـ ٣–٤ حاجات اللي انت كاتبهم، مفصولين بـ `---` | (الصق كتاباتك هنا) |
| `[TOPIC]` | الموضوع اللي عايز تكتب عنه | إزاي Claude يرتبلك الـ Inbox |
| `[YOUR TEXT]` | نص مكتوب بالـ AI عايز تحوّله لأسلوبك | (الصق النص هنا) |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل — املا والصق

املا الخانات، الصق الـ Prompt ده في Claude، وهيطلعلك الـ Style جاهز تحفظه.

```
Here are my details:
- Name: [YOUR NAME]
- What I do: [CONTENT TYPE]
- Audience: [AUDIENCE]
- Language: [LANGUAGE]
- Main platform: [PLATFORM]

Below are writing samples I wrote myself, separated by ---.
Your job is to learn MY voice so that anything you write later sounds like me, not like AI.

Do this in order:

1. STYLE DNA — Analyze the samples and describe my voice in detail:
   - Tone and energy (e.g. friendly, direct, sarcastic, hype)
   - Sentence length and rhythm, how I open and how I close
   - Exact language mix: dialect, which words I keep in English, how I spell them
   - Words and phrases I repeat (quote them exactly from the samples)
   - How I structure a piece (hook, problem, solution, steps, CTA…)
   - Emojis: which ones, how often, where — or none
   - Punctuation and formatting habits (line breaks, bullets, CAPS, numbers)
   - How I talk to the reader (you / انت / حضرتك…)

2. NEVER DO — List the things that are NOT in my writing and would make it sound like generic AI:
   phrases, emojis, structures, transitions, words. Be specific.

3. STYLE INSTRUCTIONS — Write a ready-to-paste instruction block (max ~350 words),
   written as direct instructions to an AI ("Write like this… Never…"),
   including 2–3 short example lines in my voice that you write yourself (not copied).

4. TEST — Write one short [PLATFORM] piece about "[TOPIC]" using those instructions.

5. ASK ME — End with 3 questions about anything you're unsure of in my style,
   so I can correct you before I save it.

Do not invent traits that aren't in the samples. If the samples disagree with each other, tell me.

SAMPLES:
[YOUR SAMPLES]
```

**بيعمل إيه؟** بيحلّل كتاباتك، يطلّع قايمة بالحاجات اللي بتعملها والحاجات اللي عمرك ما بتعملها، ويكتبلك Instructions جاهزة تلصقها في Styles أو في الـ Project — ومعاها تجربة عشان تشوف النتيجة قبل ما تحفظ.

---

## 💬 الـ Prompts خطوة بخطوة

## 🧬 1. استخرج بصمة أسلوبك (Style DNA)

ده الـ Prompt اللي في الريل — استخدمه أول مرة وانت معاك الـ Samples بس.

```
I'm [YOUR NAME]. I create [CONTENT TYPE] for [AUDIENCE] in [LANGUAGE].
Below are 3–4 things I wrote myself, separated by ---.

Analyze them and write my "Style DNA":
- Tone, energy and personality
- Sentence length and rhythm
- How I open a piece and how I end it
- My exact language mix (dialect, English words I keep, spelling)
- Phrases and words I repeat — quote them exactly
- Emoji and punctuation habits
- How I structure ideas
- How I address the reader

Only describe what you can actually see in the samples. Quote evidence for each point.

SAMPLES:
[YOUR SAMPLES]
```

**بيعمل إيه؟** بيطلّعلك وصف دقيق لأسلوبك، وكل نقطة معاها دليل من كلامك انت — فتقدر تتأكد إنه فاهمك صح.
**نصيحة:** لو قالك حاجة مش حقيقية عنك، صحّحها له فورًا قبل ما تكمّل.

---

## 🚫 2. قايمة "ممنوع" — اللي بيفضح الـ AI

```
Based on my samples and the Style DNA above, write a "NEVER DO" list:
everything that would make a text sound like generic AI instead of me.

Include:
- Phrases and transitions I never use
- Emojis I never use (or say "no emojis" if I don't use them)
- Structures I never use (e.g. "In today's world…", three-part lists everywhere, a summary at the end)
- Words that are too formal or too "translated" for [LANGUAGE]

Format: a short bullet list, each item one line.
```

**بيعمل إيه؟** بيعمل قايمة سودا بكل الحاجات اللي بتخلي الناس تقول "ده AI" — ودي أهم من نص الـ Style نفسه.

---

## 🎨 3. حوّلها لـ Custom Style جاهز

```
Turn the Style DNA and the NEVER DO list into custom style instructions
I can paste into Claude Styles ("Use custom instructions").

Rules:
- Write it as direct instructions to an AI ("Write…", "Always…", "Never…")
- Max 350 words
- Include 2–3 short example lines in my voice (write new ones, don't copy my samples)
- Start with one line that sums up my voice
- Language of the writing: [LANGUAGE]
```

**بيعمل إيه؟** بيديك النص اللي هتلصقه في الـ Styles جوا Claude.
**نصيحة:** في Claude، من قايمة الـ Styles اختار "Create & edit styles" ← "Create custom style". تقدر كمان ترفع الـ Samples هناك مباشرة وClaude يعمل الـ Style لوحده — بس الـ Prompt ده بيديك تحكّم أكتر في النتيجة.

---

## 📁 4. نسخة للـ Project Instructions

```
Rewrite the style instructions as Project Instructions for a Claude Project
where I write [PLATFORM] content about [CONTENT TYPE] for [AUDIENCE].

Add:
- Who I am and who I'm talking to (one line each)
- The style rules
- The NEVER DO list
- "Before giving me any final text, re-check it against the NEVER DO list and fix anything that breaks it."

Keep it under 400 words.
```

**بيعمل إيه؟** لو انت شغّال جوا Project، الـ Instructions دي بتخلي كل Chat جوا الـ Project يكتب بأسلوبك من غير ما تختار Style كل مرة.

---

## 🧪 5. اختبره قبل ما تحفظه

```
Using my style instructions, write a [PLATFORM] piece about "[TOPIC]".

Then, under it, add a short check:
- Which of my style rules you applied
- Anything in the text that might still sound like AI
- One line you're least sure sounds like me
```

**بيعمل إيه؟** بتشوف النتيجة الحقيقية، وClaude بنفسه يقولك فين ممكن يكون لسه "شكله AI".
**نصيحة:** اقرأها بصوت عالي. لو حسيت إن مفيش حد بيتكلم كده، قوله يصلّحها.

---

## 🔁 6. حوّل أي نص AI لأسلوبك

```
Rewrite the text below in my voice using my style instructions.
Keep the same meaning and facts. Don't add new claims.
Remove anything on my NEVER DO list.
Platform: [PLATFORM]. Language: [LANGUAGE].

TEXT:
[YOUR TEXT]
```

**بيعمل إيه؟** عندك بوست أو Email مكتوب بالـ AI؟ بيقلبه لكلامك انت من غير ما يغيّر المعنى.

---

## 🔍 7. افحص أي Draft: شكله AI ولا لأ؟

```
Score this draft from 1 to 10 on how much it sounds like me (10 = 100% me)
and from 1 to 10 on how much it sounds like generic AI.

Then list every line that sounds like AI, explain why in a few words,
and suggest a rewrite in my voice for each one.

DRAFT:
[YOUR TEXT]
```

**بيعمل إيه؟** بيديك "مراجعة" سريعة قبل ما تنشر، ويشاور على السطور اللي هتفضحك بالظبط.

---

## 📱 8. نفس الصوت — منصات مختلفة

```
Keep my core voice, but write short adjustments for each platform:
- Instagram reel script
- Instagram/Facebook caption
- LinkedIn post
- Email to a client

For each one: length, how formal, emoji use, structure, and one example opening line in my voice.
Add these as a "Platform notes" section to my style instructions.
```

**بيعمل إيه؟** انت مش بتكتب الـ Email زي الـ Caption — ده بيخلي الـ Style يعرف الفرق من غير ما يضيّع صوتك.

---

## 🛠️ 9. حدّث الـ Style لما يغلط

```
You wrote this: "[YOUR TEXT]"
This is NOT how I write. Here is how I would say it: "[YOUR SAMPLES]"

Update my style instructions so this mistake doesn't happen again.
Show me only the lines you changed or added.
```

**بيعمل إيه؟** كل ما Claude يغلط في أسلوبك، بتصلّح الـ Style مرة واحدة والغلطة متتكررش — وبكده الـ Style بيتحسّن مع الوقت.

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

```
أنا [اسمك] وبعمل محتوى عن [مجالك] لـ [جمهورك].
هديك تحت ٣–٤ حاجات أنا كاتبهم بإيدي، مفصولين بـ ---.

عايزك:
١. تحلّل أسلوبي: الـ Tone، طول الجمل، بفتح وبقفل إزاي، الكلمات اللي بكررها، الـ Emojis، والكلمات الإنجليزي اللي بسيبها زي ما هي.
٢. تكتبلي قايمة بالحاجات اللي عمري ما بعملها وبتخلي الكلام شكله AI.
٣. تكتبلي Instructions جاهزة ألصقها في الـ Styles، بحد أقصى ٣٥٠ كلمة.
٤. تجرّب تكتب بوست قصير عن [الموضوع] بأسلوبي.
٥. تسألني ٣ أسئلة عن أي حاجة مش متأكد منها.

متألفش حاجات مش موجودة في كلامي.

كتاباتي:
[الصق كتاباتك هنا]
```

---

## ⚠️ نصايح مهمة

- **الـ Samples لازم تكون كلامك انت فعلًا** — لو اديته حاجات كاتبها بالـ AI، هيتعلّم أسلوب الـ AI تاني 😅
- **نوّع الـ Samples**: Email + Script + بوست أحسن من ٤ بوستات شبه بعض.
- **راجع قبل ما تنشر**: الـ Style بيقرّب الكلام منك، بس انت اللي بتقرر في الآخر.
- **امسح أي بيانات خاصة** (أسماء عملاء، أرقام، Emails) من الـ Samples قبل ما تديها لـ Claude.
- **حدّث الـ Style** بالـ Prompt رقم ٩ كل ما تلاقي غلطة — كل تصليح بيقرّبه منك أكتر.

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| كل البوستات شبه بعض ومكشوفة إنها AI | كل بوست بصوتك انت |
| بتعدّل كل حاجة Claude يكتبها بإيدك | بتكتب الـ Style مرة واحدة وخلاص |
| نفس الـ Emojis ونفس الـ Structure | Emojis وطريقة كلام بتاعتك انت |
| بتشرح أسلوبك من الأول في كل Chat | محفوظ في Styles أو في الـ Project |

---

لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
