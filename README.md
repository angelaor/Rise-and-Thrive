# Rise & Thrive

A daily 15-minute yoga practice with a meditation timer, all on one page. Each day of the week has its own routine: a 2-minute warm-up, a 10-minute core sequence done in two rounds, and a 3-minute cooldown. Every pose has a photo, a countdown timer that chimes when time is up, and a check-off, so you can follow along without leaving the page. A streak counter and a monthly calendar keep track of the days you practice, and the page cheers you on when you finish a day and when you complete a full week.

**View the page:** https://angelaor.github.io/Rise-and-Thrive/

Everything is in one `index.html` file with no build step, so it runs on GitHub Pages or any static host.

## Using the page

| Feature | What it does |
| --- | --- |
| **Text size** | Choose **Small**, **Medium** or **Large** at the top of the page |
| **Meditation** | Above the daily yoga, choose **5, 10, 15, 20, 25 or 30 minutes** and press **Start**. **Pause** and **Reset** are there too, and a chime sounds three times when your time is complete. Meditation days show in the calendar. |
| **Today's practice** | When today's practice isn't done yet, a banner at the top says so. Press **Start now** to jump to it. |
| **Day picker** | Opens that day's routine. There are 7 routines that repeat every week. |
| **Round 1 / Round 2** | Switches between the two rounds of the core sequence. Each round shows a ✓ once every pose is done. |
| **Timer** | Tap a pose's time to start the countdown, and tap it again to cancel. A chime plays at the end, and your screen stays on while a timer runs so your phone doesn't lock mid-pose. |
| **ⓘ How to do it** | Tap the small **i** on any pose photo to see a short description of how to do the pose, with a tip for an easier version. Tap it again to close. |
| **Check-offs and reps** | Tick each pose as you finish it, or use **–** and **+** to count reps. |
| **Streak** | Counts the days in a row you've practiced: any yoga pose ticked off, or a meditation. Skip a day and it starts again. |
| **Great job!** | A cheer when you finish a day, and a celebration when you complete all 7 days. Press **Begin next week** to start the next week fresh. |
| **Activity Calendar** | A month view of your progress. A day you did yoga fills in sage, a day you meditated fills in lavender, and a day you did both is split corner to corner, half sage and half lavender. Tap a day to see which poses you did and how long you meditated (for example, "Meditation for 10 minutes"), and use **‹ ›** to change months. |
| **Daily reminder** | Under **Stay on track**, pick a time and press **Add to my calendar**. Open the file it saves to add a repeating daily reminder to your phone or computer calendar. |
| **Start fresh** | Under **Stay on track**. Been away for a while? Clear your progress, streak and calendar and begin again at Day 1. It asks before clearing anything, and your text size stays the same. |

Your progress, streak and calendar are saved in your browser, so they're still there when you come back. They're saved on that device only, so your phone and laptop each keep their own record.

## Host it on GitHub Pages

In the repository, go to Settings → Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save. The page will be at https://angelaor.github.io/Rise-and-Thrive/ a minute or two later.

## Coming next (phase two)

- **Strength Add-Ons:** pick exercises by muscle group for home or the gym
- **Male demonstrator:** a second set of pose photos

Both are already built into the page and switched off for now. To turn one on, change `strength:false` or `male:false` to `true` near the top of the script in `index.html`.

## Pose pictures

The pose pictures are built into `index.html`, so the page needs no other files to work. The `.png` files in the repository are the original full-size pictures, kept for reference.

## A note on health

This page is for general fitness and wellbeing. It is not medical advice. If you're new to exercise, pregnant, or recovering from an injury, check with a doctor or physical therapist first, and skip any pose that causes pain.
