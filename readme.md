# Days Worked — Setup & Usage Guide

**App link:** https://audiorazor.github.io/days-worked/

A simple tracker for logging days worked against your annual contract, with support for multiple tours and stacked days. Your data stays private on your own phone — nothing is shared with anyone else who uses this link.

---

## Installing on iPhone

1. Open the link above in **Safari** (it has to be Safari — Chrome or other browsers won't let you add it to your home screen the same way).
2. Tap the **Share** icon at the bottom of the screen (a square with an arrow pointing up).
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add** in the top corner.

You'll now have an app icon on your home screen. Opening it launches full-screen, with no browser address bar — it works like any other app from here on, including without a signal once it's loaded the first time.

## Installing on Android

1. Open the link above in **Chrome**.
2. Tap the **⋮** (three dots) menu in the top-right corner.
3. Tap **Add to Home Screen** (or **Install app**, depending on your Chrome version).
4. Confirm by tapping **Add** or **Install**.

Same result — a home screen icon that opens full-screen.

**One-time requirement:** the very first time you open it, you need an internet connection so it can load. After that first successful load, it keeps working offline.

---

## Using the app

### Logging a day

- Tap the gear icon and set your **contract days per year** the first time you open the app.
- If you're tracking more than one tour, tap **+ Add tour** to create one, then select it from the pills at the top before logging.
- **You must have a tour selected to log a day** — this keeps every logged day clearly attributed.
- Use the **Log today** card at the top for the fastest path: tap Full, Half, or Quarter.
- Or tap any date directly on the calendar — tapping cycles through Full → Half → Quarter → clear.
- **Hold a date** (about half a second) to open its full detail — add a note, or manage everything logged for that date.

### Jumping back to today

A **Today** button sits between the year arrows below the calendar header — one tap returns you to the current month no matter how far you've navigated away. It dims slightly when you're already there. Today's date is also always marked with a bright ring around it on the calendar, regardless of what color that day is otherwise showing.

### Stacking days across tours

If you were credited for more than one tour on the same date (for example, on retainer for one tour while actively working another), you can log that date under each tour separately:

1. Select the first tour from the pills, tap the date.
2. Switch to the second tour, tap the same date again.

Both entries stack — your total day count adds up all of them. A small **"×2"** badge appears on any date with more than one tour logged, and holding that date shows the full breakdown, with the option to add still more tours to the same day.

### Clearing a whole month

If a month needs redoing (wrong backup imported, batch of mistakes, etc.), a small **"Clear [tour] entries for [Month]"** link appears below the calendar whenever there's something to clear for your currently selected tour. It only touches that tour's entries for the month you're viewing — any other tour's stacked entries on those same dates are left alone. You'll get a confirmation showing exactly how many days it's about to remove before anything happens.

### Notes

- Any day can have a short note attached (visible via long-press, or the note field on the Log Today card).
- All notes for the year are listed together in **Year Summary**.

### Settings (gear icon)

- **Contract days per year** — your annual threshold.
- **Annual salary** (optional) — enables day rate and extra-pay calculations.
- **Advanced** section (tap to expand):
  - **Standard days for pay rate** — only needed if your contract days are prorated (e.g. a partial first year — a new hire starting mid-year, for instance). Leave blank otherwise; this keeps day rate calculating off the normal full-year figure even when the year itself is prorated.
  - **Starting balance** — enter a lump number of days already worked before you started using the app, with an optional date and an optional tour to attribute it to (shows up correctly in the "By tour" breakdown). **Once you've logged any real days for that year, these fields lock automatically** and gray out — this is a safety guard so a later edit can't accidentally bury data you've already entered. It's meant for the one-time catch-up before you started tracking, not ongoing corrections.
- **Tours** — rename, archive, or delete tours here.
  - **Archive** hides a tour from the picker without touching its data — fully reversible.
  - **Delete** actually removes every day logged under that tour, and tells you exactly how many days and how much that'll subtract from your total before you confirm. This can't be undone.

### Employer adjustments

If your employer counts your days differently than you do, use **+ Add employer adjustment** in the stat panel to add or subtract days directly — no need to tap a specific date for it. You can optionally attribute an adjustment to a specific tour so it folds into that tour's number in the "By tour" breakdown too.

### Seeing exactly when you went over

Once you're over your contract days, the stat panel shows not just how far over, but the **exact date** the running total crossed the line — for example "Crossed 245 on Oct 5." It works out the real date based on your actual logged days in order, accounting for any stacking.

### Year Summary (bar chart icon)

- **Check total as of a date** — pick any date and see your cumulative total up through that day, for any year.
- Your total per year against contract terms.
- **By tour** and **Notes** are tucked behind their own "+" toggles to keep the screen short — tap either to expand it.

### Help (? icon)

The **?** icon at the far right of the header opens a quick reference covering logging, tour stacking, getting around the calendar, and the difference between starting balance and employer adjustments — worth a look if something's unclear.

### Hiding pay figures

If a salary is set, an eye icon appears in the header. Tap it to blur your day rate and extra pay before handing your phone to someone else — tap again to bring the numbers back. It resets to visible each time you reopen the app.

### Light / dark mode

Tap the sun/moon icon in the header to switch. It follows your phone's own light/dark setting by default, and remembers your choice after that.

### Colorblind-friendly by design

The three status colors (Full, Half, Quarter) are chosen to stay distinguishable under the most common forms of colorblindness — amber, blue, and purple are each far enough apart in hue that none of them should be confused for another.

### Backing up your data

Since everything is stored only on your device, back up periodically:

1. Settings → Backup → **Export data**. This downloads a file.
2. When saving it, choose **Save to Files → iCloud Drive** (or Google Drive on Android) so you have a copy off the phone.

The app will remind you if it's been more than two weeks since your last export.

---

## If a recent update isn't showing up

This app is a web app added to your home screen, not an App Store app — so updates don't always show up the instant they're pushed, especially on iPhone. If something I've described here doesn't match what you're seeing:

1. **Fully close the app** (swipe it away, don't just leave it in the background) and **reopen it twice**. The first reopen after an update often still shows the old version while the new one loads in quietly; the second is usually when it switches over.
2. Still stuck? Open **Settings → Backup → Check for updates** inside the app — this forces it to check right away instead of waiting.
3. Still nothing after that? Export a backup first, then delete the app icon from your home screen and add it fresh from the link at the top of this guide — this guarantees a completely clean copy. Re-import your backup afterward (Settings → Backup → Import data).

This is a known iOS limitation with home-screen web apps generally, not something specific to this app — Apple's own update-checking for these is just inconsistent.

---

## Sharing this app with someone else

Just send them the same link. Each person's entries are private to their own phone — nothing is shared or synced between users.
