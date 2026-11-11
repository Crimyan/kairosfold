# Kairosfold

**Job applications, CVs built from a library of blocks and posting timers – in one place, on your own computer.**

**[⬇ Download Kairosfold 1.5.1 for Windows](https://github.com/Crimyan/kairosfold/releases/download/v1.5.1/Kairosfold_1.5.1_x64-setup.exe)** · [All releases](https://github.com/Crimyan/kairosfold/releases) · [Polska wersja opisu](README.pl.md)

> Works offline, no account, no cloud. Your data stays on your computer. Interface in English and Polish (follows your Windows language, switchable in Settings).

## What it does

- **Applications** – track every CV you send: statuses, interviews, follow-ups. Silent applications automatically become **Ghosted** (after 30 days) and move to the archive (after 60). Add a new application by pasting the job ad, a link (Pracuj.pl, LinkedIn, ArtStation, Skillshot, Hitmarker, Work With Indies, SmartRecruiters…) or a screenshot (offline text recognition). Pay in other currencies is converted at the exchange rate of the day the offer was posted, and interviews can be set in the company's time zone.
- **Companies and blacklist** – Kairosfold warns you before you send a CV to a company that doesn't pay, ghosts everyone or asks for free "tests". You already applied there? An ad keeps coming back for months? You'll see it. Share your blacklist with friends (export/import).
- **Library and CV builder** – your experience, skills and tools as reusable blocks with versions. Import an existing CV (PDF/DOCX), build base CVs and tailored copies for a specific offer, 6 templates, ATS check, cover letter, PDF export. Designing in InDesign? Name the frames in your own layout and Kairosfold fills them in (.idml), or export a CSV for Data Merge in InDesign or Affinity.
- **Commissions** – inquiries from VGen, DMs, emails or referrals on one board: quote, deposit, in progress, delivered, paid. Payments and instalments, revision rounds included in the price, deadlines on the Today screen, and which of your posts bring work.
- **Posting** – timers for Reddit, Discord, Facebook groups and forums: when you can post again, text variants and images, a step-by-step posting session with the clipboard.
- **Today and Calendar** – interviews, follow-ups and drafts in one view; month, week and list; export to Google Calendar / Outlook (.ics); Windows notifications with quiet hours.
- **Reports** – status pie chart, funnel (sent → reply → interview → offer), applications over time, which job boards and which CVs get replies, commission income by source; CSV and PDF export.
- **Browser extension** (Chrome, Edge, Opera, Brave, Firefox) – on any job ad click the Kairosfold icon: see the role, company, pay and warnings (blacklist, "you already applied", "this ad keeps coming back"), then **Add to queue** or **Open in Kairosfold** with all fields filled in – also on LinkedIn while you're logged in.
- **Ctrl+K** – search everything and run commands. **Import** old applications from Excel/CSV. **Daily backups** with one-click restore.

## Install

1. Click **[Download Kairosfold 1.5.1](https://github.com/Crimyan/kairosfold/releases/download/v1.5.1/Kairosfold_1.5.1_x64-setup.exe)** (or open [Releases](https://github.com/Crimyan/kairosfold/releases) and pick `Kairosfold_…_x64-setup.exe`).
2. Run the downloaded file. It installs for your user only – no administrator rights needed.
3. Windows SmartScreen may say *"Windows protected your PC"* (the installer is not signed with a paid publisher certificate). Click **More info → Run anyway**.
4. Kairosfold starts after installation. You'll find it in the Start menu; closing the window hides it to the tray (reminders and timers keep working) – quit it from the tray icon menu.

Requirements: Windows 10 or 11, 64-bit.

## Browser extension

The extension ships with Kairosfold. In Kairosfold open *Settings → Browser extension* and click **Show folder**, then:

- **Chrome / Edge / Opera / Brave:** open `chrome://extensions` (`edge://extensions`), turn on **Developer mode**, click **Load unpacked** and pick that folder.
- **Firefox:** open `about:debugging` → *This Firefox* → **Load Temporary Add-on** → `manifest.json` from the folder (until a signed version is published, it stays until Firefox restarts).

Then click **Connect browser** in Kairosfold and type the 6-digit code into the extension window. The extension talks only to Kairosfold on your computer (127.0.0.1).

## Updates

Kairosfold checks for a new version shortly after start and every 6 hours. When one is available, a **"↑ Install …"** button appears in the sidebar; click it and Kairosfold updates and restarts. Your data is kept. You can also check manually in *Settings → Updates*. Only the version file in this repository is requested, nothing about you is sent.

If you choose a currency to convert pay into (*Settings → Currencies*), Kairosfold downloads exchange rates: from the National Bank of Poland for PLN, otherwise from the Frankfurter service (ECB data). Only currency codes and dates are sent. You can turn this off.

## Your data

Everything is stored in `%APPDATA%\app.kairos.desktop`. Daily backups go to the `backups` folder there – or to any folder you choose in *Settings → Backups* (e.g. OneDrive). To move Kairosfold to another computer, restore a backup file there.

To uninstall: *Windows Settings → Apps → Kairosfold → Uninstall*. Your data folder stays until you delete it.
