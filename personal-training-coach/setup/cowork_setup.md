# Setup Guide — Claude Cowork Project (Desktop, Full Features)

*Use this guide if you use Claude Desktop on Mac or Windows and want Claude to automatically update your session log and generate PDF reports.*

---

## Requirements

- Claude Desktop app installed (Mac or Windows)
- Pro or Max plan (Cowork consumes more usage than standard chat)
- 20 minutes to complete setup

---

## Step 1 — Fill In Your Client Profile

Open `CLIENT_PROFILE.md` in any text editor and fill in every section. Be thorough — especially the health flags and equipment sections.

Save the file when done.

---

## Step 2 — Create Your Local Coaching Folder

Create a folder on your computer called `my-training-coach` (or any name you prefer). Copy these files into it:

- Your completed `CLIENT_PROFILE.md`
- `SKILL.md`
- `SESSION_LOG.md`

This folder is your coaching workspace. Claude will read and write to files here automatically.

---

## Step 3 — Create A New Cowork Project

1. Open Claude Desktop
2. Click the **Cowork** tab
3. Click **Projects** in the left sidebar
4. Click the **+** button to create a new project
5. Select **"Start from existing folder"**
6. Navigate to and select your `my-training-coach` folder
7. Name the project "Personal Training Coach" or your name

---

## Step 4 — Set Standing Instructions

1. Inside your new project, find the **standing instructions** or **project instructions** field
2. Open `COACH_INSTRUCTIONS.md` in a text editor
3. Select all the text and copy it
4. Paste it into the standing instructions field
5. Save

---

## Step 5 — Start Your First Session

Open the project and type:

> "I'm ready to start. Please review my profile and design my training program."

Claude will read your CLIENT_PROFILE.md from your folder, ask any clarifying questions, establish your baselines, and build your complete program. This first session takes 20–30 minutes.

---

## Ongoing Use

**Every morning:** Open the project and post your weight.
> "April 20 — 181 lbs"

Claude will automatically update SESSION_LOG.md in your folder.

**After training:** Post your session results.
> "Monday Push A — Bench: 4×8×175lb, Incline DB: 4×10×45lb, Duration: 75 min, Energy: 8/10"

Claude will assess your session and update SESSION_LOG.md automatically.

**Every four weeks:** Claude will prompt your rebaseline. Take measurements and retest lifts. Claude will update your profile and log automatically.

**Generating PDFs:** Ask Claude any time:
> "Generate a PDF training plan for this week"
> "Create a PDF nutrition plan"
> "Generate my rebaseline comparison report as a PDF"

Claude will save the PDFs directly to your `my-training-coach` folder.

---

## Scheduled Tasks (Optional)

Cowork supports scheduled tasks. You can set up:

**Daily weight reminder:**
> "/schedule daily at 7am — Remind me to post my morning weight"

**Weekly summary:**
> "/schedule weekly on Sunday at 8pm — Generate a weekly training summary from my session log"

**Rebaseline reminder:**
> "/schedule on [date] — Remind me that rebaseline day is coming up this week"

---

## Tips For Cowork

- Keep the Claude Desktop app open and your computer awake when Claude is working on a task
- Claude will ask for confirmation before making significant changes to your files
- You can use the mobile app to assign tasks to Cowork while you're away from your computer — Claude will complete them and the results will be in your folder when you return
- Check your `SESSION_LOG.md` periodically to verify Claude's updates look correct

---

## Usage Note

Cowork sessions consume significantly more usage than standard chat — roughly 20x. If you're on a Pro plan ($20/month), you may hit your limits faster with heavy daily use. Max plan ($100/month) is better suited to daily coaching use.

---

## Troubleshooting

**Claude can't find my files:** Make sure the folder is correctly linked to the project. In project settings, verify the folder path.

**Session log isn't being updated:** Claude should update it automatically. If it's not happening, ask: "Please update my SESSION_LOG.md with today's session."

**The program doesn't feel right:** Tell Claude directly. Claude will adjust.

**I closed the app mid-task:** Reopen the app and check what Claude completed. Ask Claude to resume if anything was left unfinished.
