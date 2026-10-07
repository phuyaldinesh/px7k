# Practice app guide (Version 7)

## The files

| File | Where it goes | Public? |
|---|---|---|
| index.html | GitHub (px7k repository) | Yes, general questions only |
| my-questions.json | Keep on your laptop only | No. Never upload it to GitHub |
| GUIDE.md | Your laptop | No |

## 1. Update the app on GitHub
1. Go to github.com/phuyaldinesh/px7k.
2. Click **Add file**, then **Upload files**.
3. Drag in **index.html** only, then click **Commit changes**.
4. Wait 2 minutes, open https://phuyaldinesh.github.io/px7k/ and press Ctrl + Shift + R (Mac: Cmd + Shift + R).
5. The bottom of the page should say **Version 7**.

## 2. Load your private questions (one time)
1. On the app page, open **Settings and private data** at the bottom.
2. Under **Private question pack**, click **Choose file** and select **my-questions.json**.
3. You will see "Imported" with 27 questions. Your name, specialty and background are filled in.
4. Type the program name (for example, Driscoll Children's Hospital) and click **Save settings**.

The questions stay inside Chrome on this laptop. They are mixed into mock interviews and appear under **My questions**. Click **Show points to include** to see the key facts for each one.

## 3. Automatic Claude scoring (optional, recommended)
Without this, content gets a quick estimate, and you can click **Copy answer for Claude** and paste the answer into a Claude chat.

To score every answer automatically:
1. Go to console.anthropic.com, sign in, add a small amount of credit under Billing.
2. Open **API Keys**, click **Create Key**, copy it.
3. In the app, paste it into **Claude API key**, tick **Score each answer with Claude automatically**, and click **Save settings**.

Each scored answer costs a small amount from that credit. The key is saved only in this browser. Do not share the laptop's Chrome profile.

## 4. Practice types
- **Single question:** pick a category and practice one at a time.
- **Rapid fire:** 8 quick questions. The next question starts by itself 4 seconds after each answer. Press **Pause** to stop the auto-advance.
- **Mini mock:** 6 questions across the interviewer types.
- **Full interview day:** about 25 questions in order: Program Director, Associate Program Director, Faculty (rapid fire), Faculty, Resident, Program Coordinator, closing. Plan about 60 to 90 minutes. Press **End session** any time to see your summary.
- **English clarity drill:** read 8 pediatric sentences aloud. Words that were not understood are underlined, so you know exactly which words to practice.

## 5. Spoken questions and video
- **Read questions aloud:** the interviewer voice asks each question, then recording starts after a 2-second countdown. Change the voice in Settings.
- **Show question text:** untick it to practice like a real interview (listen only). Click **Show question** if you need to read it.
- **Hear question:** repeats the question.
- **Record video:** after each answer, watch yourself under **Watch your answer**. In the session summary, click **Play** next to any answer.
- Videos stay on the laptop and are deleted when you reload the page. Click **Download video** to keep one (.webm file; opens in Chrome or VLC).

## 6. How each answer is scored (0 to 100)
- **Content:** structure, specific examples, insight, fit with pediatrics. Scored by Claude, or a quick estimate marked with *.
- **English clarity:** pace, fillers, pauses, how well two speech systems agree on your words, and Claude's grammar and word-choice review. Accent is not penalized.
- **Delivery:** eye contact, eye rolls, looking up, smiling, tension, head movement, voice energy, answer length.
- **Overall:** content 45%, English 25%, delivery 30%.

All scores are saved in **Progress over time**. Click **Download my results (CSV)** to open them in Excel.

## 7. If something goes wrong
- No transcript: wait for the speech model download the first time, and check the microphone is allowed (icon in the address bar).
- Eye-roll counter shows "n/a": reload the page with Ctrl + Shift + R.
- Moving to a new laptop or browser: import my-questions.json again and re-enter your API key.
