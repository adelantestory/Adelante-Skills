# Personal Training Coach — AI Coaching Framework

A goal-agnostic personal training and nutrition coaching framework for Claude AI. Works with any fitness goal — strength building, body recomposition, weight loss, endurance, mobility, or general health. Designed for ongoing coaching conversations that build context over time.

---

## What This Is

This framework turns Claude into a personalized fitness coach that:

- Designs a training program tailored to your goals, equipment, schedule, and physical limitations
- Builds a nutrition plan based on your calorie and protein targets
- Tracks your sessions, weight trend, and strength progression over time
- Adjusts your program every four weeks based on your rebaseline measurements
- Adapts to travel, illness, schedule disruptions, and changing goals
- Protects your long term health — never programs around injuries or chronic pain

This is not a one-time plan generator. It is an ongoing coaching relationship that evolves as you get stronger, your goals shift, and your life changes.

---

## How It Works

The framework is five files. Each one has a specific job:

| File | Purpose |
|---|---|
| `COACH_INSTRUCTIONS.md` | Defines the coaching methodology — paste this into your project system prompt |
| `CLIENT_PROFILE.md` | Your personal data — fill this in once, update as things change |
| `SKILL.md` | The coaching playbook — program design, nutrition, progression rules |
| `SESSION_LOG.md` | Running record of your sessions, weight, and measurements |
| `README.md` | This file |

---

## Setup — Two Paths

### Path A — Claude.ai Project (Mobile Friendly)

Best for people who primarily use Claude on their phone or in a browser. Works on any Claude plan.

**Step 1 — Create a new Project in Claude.ai**
Go to claude.ai → Projects → New Project. Give it a name like "My Training Coach."

**Step 2 — Set the system prompt**
Open the project settings. Copy the entire contents of `COACH_INSTRUCTIONS.md` and paste it into the project instructions field.

**Step 3 — Upload your files**
Upload your completed `CLIENT_PROFILE.md` and `SESSION_LOG.md` to the project. Claude will read these at the start of every conversation.

**Step 4 — Start coaching**
Open the project and say: *"I'm ready to start. Please review my profile and design my training program."*

**Ongoing use:**
After each session, paste your results into the conversation. Claude will give you an assessment and tell you what to do next. At the end of each conversation, Claude will present a SESSION_LOG entry for you to copy into your SESSION_LOG.md file and re-upload.

---

### Path B — Cowork Project (Desktop, Full Features)

Best for people using Claude Desktop on Mac or Windows who want Claude to automatically update their session log and generate PDF reports. Requires Pro or Max plan.

**Step 1 — Create a local folder**
Create a folder on your computer called `my-training-coach`. Copy all four files into it. Fill in CLIENT_PROFILE.md with your personal data.

**Step 2 — Open Claude Desktop → Cowork → Projects → New**
Select "Start from existing folder" and point it at your `my-training-coach` folder.

**Step 3 — Set standing instructions**
In the Project settings, copy the contents of `COACH_INSTRUCTIONS.md` into the standing instructions field.

**Step 4 — Start coaching**
Type: *"I'm ready to start. Please review my profile and design my training program."*

**Ongoing use:**
After each session, tell Claude what you did. Claude will automatically update your SESSION_LOG.md file and can generate PDF training plans and nutrition plans directly to your folder.

---

## First Session — What To Expect

Your first conversation will be an intake session. Claude will:

1. Review your CLIENT_PROFILE.md and ask any clarifying questions
2. Establish your baselines — either from existing data or by designing a rep test protocol
3. Design your training program based on your goal, schedule, and equipment
4. Build your nutrition plan based on your calorie and protein targets
5. Explain the progressive overload rules and rebaseline schedule

This first session typically takes 20–30 minutes of back and forth. After that, daily sessions are quick — post your results, get your assessment and next session guidance.

---

## Ongoing Coaching — How To Use It Day To Day

**Every morning:**
Post your weight. Claude tracks the trend and flags if adjustments are needed.

**After every training session:**
Post your results in this format:
```
Session: Push A — Monday April 14
Bench press: 4×8×175lb
Incline DB press: 4×10×45lb
Duration: 75 min · Energy: 8/10
Notes: Lower back felt tight on last two sets
```

**Every four weeks:**
Claude will prompt you to do a rebaseline — take all your measurements and retest your key lifts. Claude recalculates your working weights and updates your program based on your progress.

---

## Updating Your Profile

When things change — new equipment, a health issue, a goal shift, a travel period — tell Claude directly in conversation. Claude will recommend updates to your CLIENT_PROFILE.md. In Cowork, Claude updates the file automatically. In Claude.ai, Claude will show you the updated text to paste in.

---

## Supported Goals

This framework supports any fitness goal. Tell Claude your goal during intake and the program adapts accordingly:

- **Muscle building** — caloric surplus, hypertrophy rep ranges, progressive overload focus
- **Body recomposition** — maintenance calories, moderate weights, definition focus
- **Weight loss** — caloric deficit, preserving muscle, cardio integration
- **Strength building** — strength rep ranges, periodization, compound movement focus
- **Endurance** — cardio programming, race preparation, hybrid training
- **Mobility and health** — corrective exercise, flexibility, joint health, low impact
- **General fitness** — balanced program for overall health and energy

---

## Equipment Flexibility

The program works with whatever you have. During intake Claude will ask what equipment is available and design entirely around it. Common setups supported:

- Full commercial gym
- Home gym with barbell and rack
- Dumbbells only
- Resistance bands only
- Bodyweight only
- Hotel gym
- Any combination of the above

---

## Health and Safety

This framework takes a conservative approach to health flags. If you have chronic pain, previous injuries, or medical conditions — tell Claude during intake. Claude will design around them, not through them. Movements that aggravate existing conditions are replaced with safe alternatives.

This framework is not a substitute for medical advice. For serious health conditions, consult a physician before starting any training program.

---

## About This Framework

Built from a real four-week coaching engagement that developed the methodology through practical application — program design, nutrition planning, travel adaptation, injury management, and ongoing progression tracking. The goal-agnostic version generalizes that methodology so it works for any person with any fitness goal.

**Repo:** github.com/[your-handle]/personal-training-coach
**License:** MIT — free to use, modify, and share

---

## Questions and Contributions

If something doesn't work as expected, open an issue. If you improve the framework, submit a pull request. The more people use and refine this, the better it gets for everyone.
