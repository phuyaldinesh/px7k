# Interview Prep Studio guide (Version 11)

## Your files
| File | What it is | Where it goes |
|---|---|---|
| index.html | The whole app (home page + interview room) | Upload to GitHub (px7k) |
| my-questions.json | Your private questions | Keep on your laptop. Never upload to GitHub |
| GUIDE.md | This guide | Your laptop |

The Claude feedback page is already online at:
https://claude.ai/artifact/2BNfxUGdUpvTcvFF4TERSE
(There is also a link to it inside the app.)

## 1. Update the app
1. Go to github.com/phuyaldinesh/px7k.
2. Click **Add file**, then **Upload files**, drag in **index.html**, click **Commit changes**.
3. Wait 2 minutes, open https://phuyaldinesh.github.io/px7k/ and press Ctrl + Shift + R (Mac: Cmd + Shift + R).
4. The bottom of the home page should say **Version 11**.

Your saved questions, settings and scores stay.

## 2. Home page (settings)
The colored sections on the left save automatically:
1. **Practice type:** single question, rapid fire, mini mock, full interview day, real interview, English drill.
2. **Interviewer:** voice, read questions aloud, show question text (untick for surprise mode), 2-second countdown (off by default).
3. **Feedback:** live coaching while you answer, spoken feedback after each answer, link to the Claude feedback page.
4. **Video:** record and auto-save videos.
5. **My profile and questions:** drop **my-questions.json** on the pink box once.
6. **My data:** download or clear scores.

The checklist on the right shows what is ready. The interviewer voice downloads the first time (about 1 to 2 minutes).
Then click **Enter interview room**.

## 3. Interview room
- Left: the interviewer (glows while speaking). Right: you.
- **Start answer**, then **Stop** when done. In Real interview: **Begin interview**, then **Done** or the space bar after each answer.
- **Settings** (top left) returns to the home page.

## 4. Feedback
- **Live coaching** (practice modes only): short tips on your video such as "Look at the camera", "Slow down", "Pause instead of saying um", "Time to wrap up".
- **Spoken feedback:** after each answer, the app says your score, what went well and what to fix. In Real interview, it speaks only at the end.
- **Claude feedback (uses your Pro plan, no API key):**
  1. In the session summary, click **Download Claude feedback pack** (one .json file).
  2. Click **Open Claude feedback page**.
  3. Drop the file on the page. Claude scores every answer (content, English clarity, presence) and writes an overall plan.
  Claude cannot watch video files, so the pack contains your transcript and still frames from each answer.

## 5. Why the API key did not work
A Claude Pro plan does not include API access. The API is a separate paid account at console.anthropic.com. You do not need it: use the feedback page instead.

## 6. If something goes wrong
- No transcript: the speech model downloads the first time; check the microphone is allowed (icon in the address bar).
- Interviewer voice shows "!": reload with Ctrl + Shift + R. The browser voice is used meanwhile (not saved in videos).
- Chrome asks about multiple downloads: click **Allow**.
- New laptop or browser: drop my-questions.json on the pink box again.
