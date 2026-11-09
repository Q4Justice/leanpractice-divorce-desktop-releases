# LeanPractice Divorce: downloads

The desktop app for Florida uncontested dissolutions with children. This page holds the installers and
updates only.

## Download version 3.0.0

Released November 9, 2026. Choose the file for your computer:

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1 or later) | [LeanPractice.Divorce_3.0.0_aarch64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.0.0/LeanPractice.Divorce_3.0.0_aarch64.dmg) |
| Mac with Intel | [LeanPractice.Divorce_3.0.0_x64.dmg](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.0.0/LeanPractice.Divorce_3.0.0_x64.dmg) |
| Windows 10 or 11 | [LeanPractice.Divorce_3.0.0_x64-setup.exe](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases/download/v3.0.0/LeanPractice.Divorce_3.0.0_x64-setup.exe) |

**Mac:** open the `.dmg` and drag the app into **Applications**, then open it from Applications.
The first time, macOS says it can't verify the app. Close that message, open **System Settings ›
Privacy & Security**, scroll down and choose **Open Anyway** next to "LeanPractice Divorce",
then enter your Mac password. You only do this once.

**Windows:** run the setup file. No administrator rights are needed. If Windows says it protected your
PC, choose **More info › Run anyway**.

Step-by-step instructions with screenshots, first-time setup and troubleshooting:
**[Installation guide](docs/INSTALL.md)**.

### What's new in 3.0.0

- Calculation versions are named by their number and the date they took effect ("calculation version 2026.14,
  in effect November 7, 2026") on the Law tables page, under each step and in the newer calculations review, the
  same number the case list shows.
- Under each step, a shorter note: the calculation version, the date it took effect and a link to Law tables. The
  statutes the calculations follow are now listed at the top of the Law tables page, and the worksheet's own version
  is in Settings.
- Fixed: while viewing an earlier version of a case in History, the line under each step and Law tables named the
  case's current calculation version; they now name the version the earlier one was calculated with.
- Fixed: Law tables, for a case whose calculation version this copy of the app doesn't have, now says the figures
  shown are the newest version's, not the ones the case was calculated with.
- Court forms: the court's own PDF forms, filled from the case. A new Court forms item, under Case documents,
  lists the forms the case needs: the child support guidelines worksheet (Form 12.902(e)) and each party's
  financial affidavit (Form 12.902(c), the long form). Each opens on its own screen with every page filled in and,
  beside the pages, Save PDF, how the form is served, and what still prints blank, each blank numbered on its page
  with a link to where you enter it. The saved PDF is the court's form, still fillable, so anything missing can be
  typed into it.
- On the child support worksheet, click any figure to see how Child support works it out. The notice of filing and the
  certificate of service are filled too: who files, how and when it is served, and on whom.
- The financial affidavit comes with Exhibit A, a schedule of the assets and liabilities from Equitable
  distribution, in place of the form's own tables, as the form allows. The app doesn't fill the short form,
  12.902(b), for a party under $50,000 a year.
- When the case changes after you save a form, Court forms says which lines changed, so you can save a new copy or
  keep the one you saved.
- Step 1 asks for what the forms need: the division, which party is your client, each party's e-mail, phone,
  occupation, employer and last year's income, and opposing counsel's address, phone and e-mail. Settings has a
  place for your name, Florida Bar number and contact details, for the notice of filing you sign.
- Step 2 can list each party's expenses line by line, as the financial affidavit does, with their creditors. A case
  entered with one figure per group keeps its figures: what isn't on a line yet shows as "Left to split".
- Step 3: each debt's creditor, and the ownership percentage of a business interest.

- Fixed: on Macs with an early version of macOS 12 (Monterey), the agreement terms and the MSA draft couldn't be
  built when a parent claims two or more children for taxes.

- Taxes have their own step, Step 6, between Parenting plan and Child support: who claims each child, each spouse's
  federal income tax after the divorce, this year's returns and refunds, and the tax on assets sold or cashed out.
  Child support is now Step 7, Agreement terms Step 8 and the MSA draft Step 9.
- The income tax line can deduct the estimate, worked out from filing status and dependents and kept up to date as
  income, overnights or who claims a child change, or the federal income tax withheld. Taxes shows the child support
  each choice gives. While the estimate is picked, the income tax line on Income and expenses shows it, locked, and
  the withheld figure is kept for when you switch back.
- The tax worksheet shows both spouses side by side, from the income on Income and expenses to the estimated tax.
  The estimate now subtracts what is taken from pay before tax: health premiums, mandatory retirement and the
  voluntary 401(k), 403(b) or 457, which the pay stub helper fills. Filing status and taxable income from a return
  can be overridden there.
- Cases saved before this version keep their calculations. Open "Review changes" to see what the newer ones change
  for the case, usually the income tax estimates, and apply them to use the estimate on the income tax line.
- The income tax estimate counts half of self-employment tax and the qualified business income deduction for
  business income, and Calculate on Income and expenses puts the self-employment tax in the FICA rows. Above $201,750 of
  taxable income it asks for the figure from the return. Business income from an S corporation can be marked as not
  subject to self-employment tax.
- On Income and expenses, FICA is two rows, Social Security and Medicare, as on the pay stub and the financial
  affidavit's lines 19 and 20, and both count in the deductions. Calculate, beside each spouse's FICA rows, works out
  FICA on wages (from the pay stub when its pay matches the wages, otherwise from the wages) and the self-employment
  tax on business income, each split in two, and "Use these figures" fills the rows. With business income, a warning
  under the rows says when they hold less than that. The AI assistant can fill the Medicare part too.
- Fixed: on older calculations, the income tax estimate now says that with business income it is likely too high,
  and points to taxable income from the return.
- Fixed: someone born on January 1 now counts as 65 for the year before their 65th birthday, as the IRS counts it,
  so the income tax estimate includes the extra standard deduction and the senior deduction.
- Fixed: for someone born late in a month, 59½ is now the last day of the month six months after their 59th birthday
  when that month is shorter (born August 31: February 28), so a retirement account cashed out on those days isn't
  charged the 10% penalty.
- Fixed: a spouse filing separately after living apart all year has Social Security taxed as for a single person,
  from the date of separation on Case and parties.
- Fixed: when deductions are larger than a spouse's other income, the rest now comes off the depreciation on a rental
  sold, taxed at up to 25%, before the gain taxed at 0% or 15%.
- Case documents now reads Word and Excel files (.docx and .xlsx): the AI assistant searches them, cites the page,
  and shows a spreadsheet page as a grid with the cited cells marked. A Word file is read as Word shows it with its
  tracked changes accepted, without its comments or hidden text, and says when it has any.
- Excel files are read in full: hidden sheets, rows and columns are read too and marked as hidden, so the AI
  assistant's totals match the spreadsheet's own. It totals rows exactly, for example every Publix purchase or each
  month's spending, and says whether its total matches the sheet's own SUM or SUBTOTAL.
- Word and Excel files already in a linked folder are read the next time you open the case. A password-protected
  Word or Excel file, or an older .doc or .xls file, is listed under "Needs your attention" with what to do.
- You can attach Word and Excel files to a question for the AI assistant.
- Learning from a past MSA reads each row of a table in a Word file as one paragraph.
- Fixed: a citation the AI assistant put in bold text showed as its link, not as a button that opens the page.

[All versions](https://github.com/Q4Justice/leanpractice-divorce-desktop-releases/releases)

## Updates

The app checks this page for new versions. When one is available it shows a banner; choose
**Install and restart**. Your cases are saved and backed up first, and stay where they are.

## Your data

Cases are saved as files on your own computer (Documents › LeanPractice Cases unless you choose another
folder in Settings). Nothing is sent to this page.
