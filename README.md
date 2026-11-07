# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 2.0.1

Released November 7, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_2.0.1_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v2.0.1/LeanPractice.Divorce_2.0.1_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_2.0.1_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v2.0.1/LeanPractice.Divorce_2.0.1_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_2.0.1_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v2.0.1/LeanPractice.Divorce_2.0.1_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 2.0.1

- Fixed: version 2.0.0 didn't go out as an update. This update brings everything it changed, listed below.

Version 2.0.0, which didn't go out as an update:

- Case documents now says at the top what it's doing: reading the files, the AI assistant sorting them (how many
  are done, with Stop), or why sorting is waiting and what to do about it. A case with no names for the parties
  yet says so, with a button to enter them; sorting starts by itself once they're in. A pause, such as the AI
  service limiting requests, shows there too, with Try again.
- Each file not sorted yet reads "Not sorted yet" in grey and says whether it's waiting for the AI assistant or
  being read by it, in place of an orange "Unsure".
- "Needs your attention" now asks whose a file is only once sorting has finished, so it lists only what's left
  for you. Files that couldn't be read (password-protected, too large, not downloaded from iCloud) show right away,
  so you can deal with them while the rest is sorted.
- Fixed: a citation in the AI assistant's answer that quoted words with brackets, such as "401(k)", showed part of
  its link as text and marked only part of the words on the page.
- When a statement in the linked folder is password-protected, the AI assistant now tells you to type its password
  under Needs your attention on Case documents, instead of suggesting you save an unlocked copy.
- The AI assistant's answers name worksheet lines the way the worksheet does, such as "Daniel's bonus", instead of
  internal names such as "parties.B.income.bonus".
- Fixed: after you accepted some of the AI assistant's changes, its next answer could say they had changed nothing,
  because it took the new values for ones that had always been there. It is now told which values your accepts
  replaced.
- Fixed: in the evening (from 7 pm, or 8 pm in summer), the worksheet took today's date to be tomorrow, so the term
  sheet and the MSA draft were dated a day ahead. They now use the date on your computer.
- Fixed: the term sheet showed a child's new age all day before the birthday.
- Fixed in the newer calculations: the calculations use today's date in place of a support start date, filing date
  or cash-out date the case doesn't have, and that is now the date on your computer too. In a case with no support
  start date, a child turning 18 the next day dropped out of child support in the evening. Also, a child born on
  March 1 of a leap year now turns 18 on March 1; before, the worksheet counted the child as 17 that day.
- Fixed: in the newer calculations, a child of 19 to 23 marked as still in school in Step 1 now brings the $500
  credit for other dependents to the parent who claims the child, in the income tax estimate and in Child tax
  benefits. The child already counted for head of household.
- Fixed: in the newer calculations, when the remaining child alternates, a child whose claim you haven't chosen yet
  now counts as remaining, so the other child stays with the parent you chose instead of alternating from the first
  year.
- Fixed: in the newer calculations, an income tax estimate for a year other than 2026 didn't say it uses the 2026
  tax tables. It now does.
- Fixed: in the newer calculations, the reason given for head of household said "children under 19" when one of
  them was over 19 and still in school.
- Existing cases get those calculation fixes when you apply the newer calculations ("Newer calculations are
  available" at the top of the case). Until then, they calculate as before. Applying them changes a figure only in
  the situations above.
- Fixed: for some March birthdays, "Support ends (age 18)" in Step 1 showed the day before the 18th birthday.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
