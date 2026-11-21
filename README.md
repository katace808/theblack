# The Black — Personal Health & Study AI

An AI companion for Android that lives on your phone: it tracks your **food and protein**, plans and logs your **gym workouts**, helps you **learn the words from the books you read**, sets **reminders**, remembers what you tell it, keeps your **important documents** locked behind your fingerprint, and talks with you by **voice**.

**[⬇ Download the latest APK](../../releases/latest)** · Android 8.0 or newer · free

---

## What it does

### 🍽 Food & body (Fit tab → food)
- **Log food by just saying it:** “I had 3 eggs and 2 rotis”, “breakfast was poha”, “lunch: dal rice and curd”. Strong on Indian food, gym foods, packaged brands and restaurant chains.
- **📷 Photo of your plate**, **🏷 barcode scan** (Open Food Facts) or **🧾 photo of the nutrition label** for exact numbers.
- Tap any item to **change the grams**; every macro scales. Supplements like creatine are logged too (0 kcal).
- **Goals for cut / maintain / lean bulk / bulk**, worked out from your body stats, with protein set for your goal.
- **📈 Weekly coach:** compares what you ate with what the scale did to find your *real* maintenance calories and tells you if your pace is right.
- **💊 Daily check-off** for creatine, pre-workout, caffeine (editable), recent foods, saved meals, weight trend, and 🎉 confetti when you hit your goals.

### 🏋️ Gym (Fit tab → gym)
- **Build a plan** in 3 taps (2–6 days a week, gym / dumbbells / no equipment, beginner → advanced): full body, upper/lower or push-pull-legs.
- **Or import your own program**, e.g. from ChatGPT as JSON, **with a picture for each exercise**. Paste it in chat, use 📥 import, or share it to the app.
- Log every set (kg × reps), **rest timer** with vibration, and it tells you **when to add weight**. PRs, history, strength progress.
- Swap any exercise (machine busy? no barbell?), add your own pictures, say **“rest today”** and the workout simply waits for tomorrow.

### 📖 Words (from your books)
- **📷 Scan a page:** it finds the words you **underlined** (and suggests hard ones), explains each one **in that sentence**, with a memory hook.
- **Spaced repetition** review (2 minutes a day), word of the day, ✨ **story mode** (a short story written with your words), streaks.
- Your **bookshelf with real covers**, words grouped by book and language. Works for **Russian and Mandarin** words too, with the reading and a native voice.

### ⏰ Your assistant
- **Reminders:** “remind me to call mom at 6”, “every day at 8 am take creatine”, “remind me tomorrow morning to pay rent”. A notification with ✅ done / ⏰ snooze.
- **Memory:** “remember that my locker code is 4512”, “remember this”. It uses what it knows when you chat.
- Chat about anything, ask about a **photo** or your **screen**, play music, set timers and alarms, open apps, flash, screenshots.
- **🗣 Voice mode:** a hands-free conversation; also a language tutor for **Russian and Mandarin**.
- **🔒 Docs vault:** scan or save documents (ID cards, marksheets, tickets…). Fingerprint to open, “show my aadhaar” to find one, share or make a PDF.

---

## Install

1. Open **[Releases](../../releases/latest)** on your phone and tap **`TheBlack-x.y.z.apk`**.
2. When asked, allow **“Install unknown apps”** for your browser (only the first time), then **Install**.
3. Updates: download the newer APK and install it over the old one. Your data stays.

> Android may warn that the app is from an unknown developer. That's normal for apps that aren't from the Play Store.

## Set up (2 minutes, free, no card)

The Black uses AI services that give you a **free personal key**. Your keys stay on your phone.

1. **Gemini key** (the main brain + natural voice): go to **[aistudio.google.com/apikey](https://aistudio.google.com/apikey)** → *Create API key* → copy it. In the app: **Me → ✨ AI brain → 2️⃣ paste key**.
2. **Groq key** (voice mode, the 🎙 mic, fast photo and food reading): go to **[console.groq.com/keys](https://console.groq.com/keys)** → sign in → *Create API key* → copy it. In the app: **Me → ✨ AI brain → paste Groq key**.
3. **Me → tap your name**, and **Fit → 🎯 goal**: add your name, weight, height, age and goal.
4. Optional:
   - **Phone control** (screenshots, music auto-play, “what's on my screen?”): Android **Settings → Accessibility → The Black phone control → On**.
   - **Side-button assistant:** Settings → Apps → Default apps → Digital assistant app → The Black. Then hold the side button to open it listening.
   - Allow **notifications** so reminders and the word review can reach you.

With only a Gemini key, everything works except voice mode and the mic (they need Groq). With only a Groq key, everything works but chat is simpler.

## Things to say

| | |
|---|---|
| Food | “I had 2 eggs and toast” · “breakfast was poha” · “scan a barcode” · “undo” · “how much protein left” |
| Body | “start cutting” · “switch to lean bulk” · “how's my bulk going?” · “my weight is 70 kg” |
| Gym | “what's my workout today” · “bench 60kg 3x8” · “my PRs” · “rest today” · “make me a workout plan” |
| Words | “new word lugubrious” · “what does ennui mean” · “scan my book page” · “review my words” |
| Assistant | “remind me to call mom at 6” · “what are my reminders” · “remember that…” · “remember this” |
| Phone | “play lofi on spotify” · “set a timer for 10 minutes” · “flash on” · “take a screenshot” · “show my aadhaar” |

## Privacy

- **Everything you log stays on your phone:** food, workouts, words, reminders, memories, documents. There's no account and no server of ours.
- What you **ask the AI** (a message, a food photo, a page you scan) is sent to the AI service whose key you added (Google Gemini or Groq) to get the answer.
- Barcodes go to **Open Food Facts** and book titles to **Open Library** (for nutrition data and covers). Nothing else is sent anywhere.
- The docs vault needs your **fingerprint**. Uninstalling the app deletes all its data.

## Permissions, and why

Microphone (voice) · Camera (food, pages, documents) · Notifications (reminders, word review) · Alarms (reminders on time) · Contacts & phone (only if you say “call …”) · Accessibility (optional phone control).

## Good to know

- AI can make mistakes. Calorie numbers are estimates, and this is **not medical advice**.
- Free AI keys have daily limits. If one runs out, the app switches to the other key automatically.
- Built for Android 8+ (tested on Android 16, Samsung One UI 8).
