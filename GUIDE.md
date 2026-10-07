# Practice app guide (Version 10)

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
5. The bottom of the page should say **Version 10**.

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
- **Real interview:** feels like the real day. No question text, no timer, no tips, no scores in between. Press **Begin interview**; each interviewer speaks, recording starts immediately, and you answer. Press **Done, next question** (or the space bar), or stay silent for 7 seconds, to move on. Press **End interview** to stop early. All scores, videos and feedback appear at the end.
- **English clarity drill:** read 8 pediatric sentences aloud. Words that were not understood are underlined, so you know exactly which words to practice.

## 5. Spoken questions and video
- **Read questions aloud:** the interviewer voice asks each question, then recording starts. By default each interviewer has a different voice. Change it in Settings.
- **Complete videos:** each downloaded video contains the spoken question, then your answer, with the question shown as a caption. The first time, the interviewer voice downloads (about 1 to 2 minutes). Until it is ready, a browser voice is used and that question's audio is not in the video (the caption still is).
- **Show question text:** untick it to practice like a real interview (listen only). Click **Show question** if you need to read it.
- **Hear question:** repeats the question.
- **Record video:** after each answer, watch yourself under **Watch your answer**. In the session summary, click **Play** next to any answer.
- **Auto-download videos** (on by default): every answer video saves to your Downloads folder as soon as you press Stop, named with the date, time and question. The first time, Chrome may ask to allow multiple downloads: choose **Allow**.
- To save videos manually: click **Download video** under any answer, **Download** next to an answer in the session summary, or **Download all videos** to save the whole session. If Chrome asks, choose **Allow** multiple downloads. Files are .webm and open in Chrome or VLC.
- Videos stay on the laptop and are deleted when you reload the page unless you download them.
- In the summary, **Review** opens the full feedback for any answer.

## 6. Getting more feedback from Claude
Claude cannot watch video files, so the app makes a feedback pack instead:
1. After a session, click **Download Claude feedback pack** in the summary (or **Download for Claude** under one answer).
2. Your Downloads folder gets one .md file (questions, answers, scores, measurements, and the request to Claude) and one image per answer with 6 still frames from it.
3. Open a new Claude chat, attach the .md file and the images (up to about 20 images per message), and press send.

## 7. How each answer is scored (0 to 100)
- **Content:** structure, specific examples, insight, fit with pediatrics. Scored by Claude, or a quick estimate marked with *.
- **English clarity:** pace, fillers, pauses, how well two speech systems agree on your words, and Claude's grammar and word-choice review. Accent is not penalized.
- **Delivery:** eye contact, eye rolls, looking up, smiling, tension, head movement, voice energy, answer length.
- **Overall:** content 45%, English 25%, delivery 30%.

All scores are saved in **Progress over time**. Click **Download my results (CSV)** to open them in Excel.

## 8. If something goes wrong
- No transcript: wait for the speech model download the first time, and check the microphone is allowed (icon in the address bar).
- Eye-roll counter shows "n/a": reload the page with Ctrl + Shift + R.
- Moving to a new laptop or browser: import my-questions.json again and re-enter your API key.
