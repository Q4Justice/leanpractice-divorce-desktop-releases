# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 3.1.0

Released November 16, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_3.1.0_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.1.0/LeanPractice.Divorce_3.1.0_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_3.1.0_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.1.0/LeanPractice.Divorce_3.1.0_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_3.1.0_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.1.0/LeanPractice.Divorce_3.1.0_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 3.1.0

- Mandatory disclosure, checked and counted. Case documents has two new tabs beside its files. The Disclosure
  checklist shows each party's Form 12.932 items a to r with a status (complete, to confirm, gaps, missing, waived or
  none), the documents that count, and what is still needed: the months of statements missing for each account, the
  pay stubs missing by pay date, the tax years, insurance cards and notes. Each item cites its part of Rule 12.285,
  and the look-back counts from the date the party's documents are served. Mark an item none or waived, or waive
  items b to r for both parties at once. The Worksheet check tab puts every income, asset and debt figure beside what
  its documents show, with the accounts found in the files that aren't on the worksheet, a credit report's included;
  keep a figure with a note, or use the documents' figure in one click. Under Needs your attention, "Documents that
  disagree" lists statements in different files that don't chain, overlap or don't add up, and a tax return whose
  wages don't match its W-2s. On Steps 1 to 3 each figure shows its source documents and, where they show a figure,
  a calculator comparing the two. Nothing is sent to the AI assistant for any of this.
- Fixed: on a Mac, Case documents' status line ("Getting ready to sort…", "The AI assistant is sorting and typing…")
  could squeeze to one word a line and run over what follows it, the new tabs among them.
- Case documents: a document that lists several vehicles or accounts keeps each one, and you can correct, add or
  remove them: a vehicle valuation printout or a registration renewal (each vehicle's VIN, value and trade-in value),
  a combined checking and savings statement, a household brokerage statement, a mortgage statement with a home
  equity line, and a credit report (each account's number, balance and kind, and what the report says about it); a
  page of 1099s from several payers, and a composite 1099 (each payer with its account and the forms it sent); a
  property tax bill for several parcels, and a group life certificate with several coverages.
- The MSA draft step is set aside while the agreement terms are reworked. Agreement terms is now the last step,
  Step 8, and still ends with the term sheet, which you can copy or download as text or Word. Your firm template,
  clause library and each case's drafting choices stay saved in your cases folder, and History still lists the MSA
  drafts you saved.
- Fixed: a financial affidavit attached to the AI assistant filled in one total for each group of expenses, never the
  affidavit's lines. The assistant now proposes each expense on its own line in Step 2, what each "Other" line is,
  the number of automobiles and each payment to a creditor, and the group totals follow from the lines you accept.
- Fixed: Case documents tagged a married-filing-separately tax return Joint because it names both spouses and, like
  every Form 1040, prints the words "Married filing jointly" beside the other filing statuses. A return is now Joint
  only when its married filing jointly box is checked in a fillable PDF; otherwise a return naming both of you is
  Unsure, for the AI assistant or you to decide. A filled-in 1040 whose names are in its first and last name boxes is
  now read too, so a separate return is no longer tagged as the spouse's. Folders already linked are checked again
  when the case opens.
- Case documents now says what each file is: a pay stub, a W-2, a bank statement, a 401(k) statement, a deed and 34
  other kinds, with its key detail (the bank and the last 4 digits of the account, a tax year, an employer and pay
  date). A new Type column and filter show them, with counts. Standard forms are typed on your computer at once; with
  your firm's AI key, the AI assistant reads every file once to confirm the type and find the details.
- A file holding several documents (a year of statements, a W-2 with statements behind it, both spouses' pay stubs
  scanned together) is counted document by document, each with its own type and whose it is. A file of different
  people's documents reads Mixed. Open a file to see and correct its documents, split or join them.
- Each file's details are shown beside its pages, with the page each came from and whether it was checked: a value
  must be printed on its page, a statement's opening balance must match the last one's closing balance, and when your
  computer and the AI assistant read a figure or a type differently, the AI assistant's reading is used when it is
  sure (it says how sure, from 0 to 100) and its words are on the page; otherwise Needs your attention shows both. A
  value the AI assistant isn't sure of is listed there too. Only the last 4 digits of
  any account number are kept. Your own type and details are saved in the case and always win.
- Fixed: a document addressed to you both with middle initials ("Daniel J. & Camille R. Moreau") is now seen as naming
  both of you, not only the second name, and an account held "with right of survivorship" is seen as joint.
- What Needs your attention asks about a file is also shown when you open the file, beside its pages, with the same
  buttons, so you can look at the page and decide there. The words each value was read from are links that show
  them on the page. Amounts are shown as money, and a document's dates (its period, pay date and the date of its
  balance) are date fields.
- Scanned pages and photos in Case documents can now be searched. With your firm's AI key, the AI assistant reads
  the words on each scanned page once, and its search finds them, saying they were read from a picture. Open a
  scanned page to see the text read from it under the picture. For folders linked before this update, Case documents
  asks before sending their scanned pages.
- Equitable distribution: each bank, retirement or investment account, and each debt, has an Account line for the
  institution (a debt's creditor) and the last 4 digits, used to match statements to the account.
- Fixed: after you imported a case file exported by an earlier version, History showed the update to the current
  format as "Changes saved without version history (an earlier page version or another tool)". It now says
  "Updated from data format 2 to 3", or "Filled fields added in a newer version", as it does when you open an
  older case.
- Fixed: when the cases folder couldn't be reached for a while, as when a network drive or cloud folder goes
  offline, the app kept saying it wasn't saving even after the folder was back, and the case list stayed empty. It
  now notices within a few seconds that the folder is back, and says so.
- Fixed: when the cases folder went away while the app was open, as when a network drive is disconnected, the case
  list said "No cases yet." and nothing said the folder was gone. It now says the cases folder can't be read, and
  the cases come back by themselves when the folder does. An edit made meanwhile is no longer taken for a case
  deleted somewhere else, and the app never makes a new, empty cases folder where the old one was.
- Fixed: Exhibit A of the financial affidavit said "Only the last four digits of account numbers are shown." even
  when a description held a full account number. It no longer says so: the court forms print what you typed.
- Equitable distribution (Step 3) and Income and expenses (Step 2) point out an account number or a social security
  number typed in full in text the court forms print: an asset's or debt's description, a debt's creditor, a creditor
  on the affidavit's payments to creditors, other income, and an "Other" expense line's note. "Keep last 4" keeps only
  its last four digits (Chase checking ••9012), as the financial affidavit asks, and "Remove" takes a social security
  number out (•••-••-••••), as Florida's Rule 2.425 asks. Nothing is shortened unless you click. Amounts, dates, years
  and ZIP codes aren't flagged.
- Fixed: adding a Step 3 debt as a creditor on Step 2 takes the last four digits of the account number in its
  description, not of a year typed after it, and never of a social security number.
- A new case starts in the county you chose last on this computer, with its circuit, instead of Miami-Dade. Settings
  shows the county new cases start in and can change it.
- Case and parties: find the county by typing any part of its name, and the circuit fills in from it. A case whose
  circuit doesn't match its county says so, with a button to correct it.
- The Eleventh Circuit's Special Affidavit and Miami-Dade's class for children are named only on Miami-Dade cases.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
