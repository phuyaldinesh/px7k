# Interview Prep Studio guide (Version 15)

## Your files
| File | What it is | Where it goes |
|---|---|---|
| index.html | The app (home page and interview room) | GitHub (px7k) |
| models.js | Face-tracking data the app needs | GitHub (px7k), next to index.html |
| README.md | Short public description of the repository | GitHub (px7k) |
| my-questions.json | Your private questions | Your laptop only. Never upload it |
| GUIDE.md | This guide | Your laptop only |

Claude feedback page: https://claude.ai/artifact/2BNfxUGdUpvTcvFF4TERSE (also linked inside the app).

## 1. Update the app
1. Go to github.com/phuyaldinesh/px7k.
2. Click **Add file**, then **Upload files**.
3. Drag in **index.html**, **models.js** and **README.md** together, then click **Commit changes**.
4. Wait 2 minutes, open https://phuyaldinesh.github.io/px7k/ and press Ctrl + Shift + R (Mac: Cmd + Shift + R).
5. The bottom of the home page should say **Version 15**.

If face tracking says "Could not load models.js", models.js is missing from GitHub. Upload it again.

## 2. Home page
The colored sections on the left save automatically:
1. **Practice type:** single question, rapid fire, mini mock, full interview day, real interview, English drill.
2. **Interviewer:** voice, read questions aloud, show question text (untick for surprise mode), 2-second countdown (off by default).
3. **Feedback:** live coaching tips, spoken feedback, link to the Claude feedback page.
4. **Video:** record video, and save each video plus a Word file of your answer automatically.
5. **My profile and questions:** drop my-questions.json on the pink box once per browser.
6. **My data:** download or clear scores.

The interviewer voice downloads quietly in the background the first time (about 1 to 2 minutes). The checklist shows when it is ready.

## 3. Interview room
- Left: your animated interviewer (a different person for each role). They speak, blink and nod while you answer.
- Click **Start interview** (Real interview: **Begin interview**). The question is spoken, then recording starts.
- Press **Done** when you finish. In Real interview, press **Done** or the space bar, or stay silent for 7 seconds.
- **Hear question again** repeats the question, even while you are answering.
- **Leave** returns to the home page.

## 4. Downloads
- The video saves to Downloads the moment you press **Done**. It includes the spoken question and your answer.
- A Word file with the same name follows a few seconds later: the question, your answer as bullet points, and your scores.
- Real interview: one Word file with all answers is saved at the end.
- If Chrome asks about multiple downloads, click **Allow**.
- Bullets come from the automatic transcript, so check for mis-heard words.

## 5. Claude feedback (uses your Pro plan, no API key)
1. In the session summary, click **Download Claude feedback pack** (one .json file).
2. Click **Open Claude feedback page** and drop the file on it.
3. Claude scores every answer (content, English clarity, presence) and writes an overall plan.

Claude cannot watch video files, so the pack contains your transcript and still frames from each answer.

## 6. If something goes wrong
- Nothing happens on the page: press Ctrl + Shift + R.
- No transcript: the speech model downloads the first time; allow the microphone (icon in the address bar).
- Interviewer voice shows "!": reload. The browser voice is used meanwhile (not saved in videos).
- New laptop or browser: drop my-questions.json on the pink box again.
